代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.ivvv.top/Article/details/gttavqvbhc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtoljmybyz.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzvggeaw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtokfktiuw.html

[Q84] 去除首尾空格
来源：http://dali.vqdsnc.cn/Article/details/gtgoynvrfa.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtflwxcbbn.html

[Q85] 数值取整
来源：http://dali.birdmap.top/Article/details/gtuyuxeycs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dashuyun.cn/Article/details/gtdfcmfzln.html

[Q86] 读取 JSON 字段
来源：http://dali.zhongyouzk.top/Article/details/gtmmquszcw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.bjfxy.top/Article/details/gtsjpkemyy.html

[Q87] JSON 字段做条件
来源：http://dali.aibaodan.cn/Article/details/gtyyrgwyha.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gtqqwrglbp.html

[Q88] 行转列（条件聚合）
来源：http://dali.ivvv.top/Article/details/gtcaitqocg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ivvv.top/Article/details/gtgpmhzoxd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtnpbyufbb.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdwyzhdv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gtqmsmngxm.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gtxhklayyc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyiqgdnt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrcupvsmq.html

R. Bash 专题
来源：http://dali.yvedp.cn/Article/details/gtpihistsy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqucjcuei.html

[R01] shebang 与严格模式
来源：http://dali.yuanzhike.top/Article/details/gtqqebtvkx.html

#!/usr/bin/env bash
来源：http://dali.tian-w.cn/Article/details/gtsidotjoo.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtbirxgttn.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtpbwpmqxg.html

name="Tom"; echo "$name"
来源：http://dali.jqgfzy.top/Article/details/gtfkslfalg.html

[R03] 只读变量
来源：http://dali.nwbrower.top/Article/details/gtbthggjei.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gthmioukbt.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gtqculzttq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sweek.top/Article/details/gtqlcwgvnw.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gtovaptdup.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gtccpanjth.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gtnupjmdlk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gtakhcfhpl.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gtpwrfbcdz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuanzx.com/Article/details/gturkuxxwt.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gtygafjmsn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xinyue.icu/Article/details/gtuxodyfhp.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtnrohggjk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gtzabrixfb.html

[R10] 正则匹配
来源：http://dali.yj20258.top/Article/details/gtqxfwecet.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gtlaeoukbl.html

[R11] case 多分支
来源：http://dali.ybcxt.top/Article/details/gttzbzdmlf.html

case "$1" in
来源：http://dali.yuanzhike.top/Article/details/gteklgakdj.html

start) echo "启动" ;;
来源：http://dali.pycfn.com/Article/details/gtyjdxlbuf.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gtqywtjfcc.html

*)     echo "未知命令" ;;
来源：http://dali.zdqjudy.top/Article/details/gtbxalkglx.html

esac
来源：http://dali.hysaishi.cn/Article/details/gtwdjfhtie.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gtvbpejzhg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gtmizradpo.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gtpfejxszl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtgtxvvryo.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gtrpbvstyw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtibbguiob.html

[R15] while 逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtcewztedg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gtfkiazxow.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gthokebmjp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtmpmhzbek.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gtdzzybxad.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.quarkkingdee.top/Article/details/gtsxwzwtle.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gtpeurkujg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpggztidl.html

[R19] 数组长度
来源：http://dali.cheryme.top/Article/details/gtidadolws.html

echo "${#arr[@]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtefwteidd.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gtlufeqdha.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yvedp.cn/Article/details/gtepohaopq.html

[R21] 字符串长度
来源：http://dali.tian-w.cn/Article/details/gtipvdsowd.html

echo "${#s}"
来源：http://dali.wangshuangyany.cn/Article/details/gtrtxyvyzg.html

[R22] 截取子串
来源：http://dali.zycfv.cn/Article/details/gtgqajvret.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gtnyrcqgoq.html

[R23] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gthyqimuly.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhiwuduotai.top/Article/details/gtaiufsxpu.html

[R24] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gthtzdadsy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ehwqpu.com/Article/details/gtykcgumql.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gtciwvifuu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.9152youxi.cn/Article/details/gtnjivrtcd.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtiecdwadk.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gtbjkdwoky.html

[R27] 算术展开
来源：http://dali.kuanghao11.cn/Article/details/gtndywcnbl.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gtxegepdma.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gtiuuqlmsy.html

echo "scale=2; 10/3" | bc
来源：http://dali.shangyingyoupin.top/Article/details/gtzlzwqypv.html

[R29] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gtxnelzefm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xylfe.cn/Article/details/gtljmbombu.html

[R30] 函数返回状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtbpcqbius.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.quarkkingdee.top/Article/details/gtmcirqked.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtvrllhofy.html

f() { local x=1; echo "$x"; }
来源：http://dali.guowangkeji.top/Article/details/gtpsmpwwsx.html

[R32] 参数个数校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhzuexby.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtlcoxpvek.html

[R33] 捕获错误并提示行号
来源：http://dali.snrcjt.cn/Article/details/gtgiorvgvi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aizwys.cn/Article/details/gtnhjolggz.html

[R34] 退出时清理
来源：http://dali.aizwys.cn/Article/details/gtjypardil.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtcbgwtxuc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtrgubhwgg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gtpapgmkor.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gtuowopdnl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gtaztqetei.html

[R37] 把输出赋给变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsaczjuq.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuuevyvs.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gtwgzlgaxz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gtwiytjiry.html

[R39] 重定向标准输出与错误
来源：http://dali.yanxiufei.cn/Article/details/gtzlktnyew.html

cmd > out.log 2>&1
来源：http://dali.jianghu66.top/Article/details/gtcthatxdu.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gtwvvdtqmj.html

echo "log" >> out.log
来源：http://dali.hywenlv.cn/Article/details/gtrcwfzarw.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gtuycdolla.html

cmd >/dev/null 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtfwzohtuy.html

[R42] 输入重定向
来源：http://dali.birdmap.top/Article/details/gtchkgfima.html

wc -l < a.txt
来源：http://dali.ivvv.top/Article/details/gtktpihsty.html

[R43] 按名字查找文件
来源：http://dali.316326.xyz/Article/details/gtnmmdgfcu.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gtdmqaurvu.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gtmtmrmpof.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gtflglmpfn.html

[R45] 批量删除
来源：http://dali.jqgufenzy.top/Article/details/gtyqwnabcm.html

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gtmvdtykdb.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gttkegogvm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gttvstwzeu.html

[R47] sed 单行替换
来源：http://dali.ppjwa.cn/Article/details/gtqzawiuvq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gtpgmkrwrv.html

[R48] awk 取指定列
来源：http://dali.nanxinkj.top/Article/details/gtlqfqlngu.html

awk '{print $1, $3}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtordjvkom.html

[R49] awk 带条件
来源：http://dali.cashguo.top/Article/details/gtcygzfnyf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hywenlv.cn/Article/details/gtyywxbtqa.html

[R50] awk 求和
来源：http://dali.kuanghao11.cn/Article/details/gthvdiwpwz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtgidkguej.html

[R51] 排序去重取前几
来源：http://dali.yvedp.cn/Article/details/gtbgeihtvw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigufen.top/Article/details/gtjcxvujaa.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gtgdtzrlyy.html

wc -l a.txt
来源：http://dali.fengsongda.top/Article/details/gtxneaeuxf.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gtqqputrmg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgufenzy.top/Article/details/gtehxpolzl.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvseautc.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gtopmmnjdm.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfmihhrj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gtfcwvxxdy.html

[R56] 远程拷贝
来源：http://dali.guannengcc.top/Article/details/gtusbaigjj.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gtfyprjkuv.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gtjsrsvbgx.html

ssh user@host 'uptime'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfycxppt.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtjvjjfsec.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnqzz.top/Article/details/gtcdykoxyf.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gtbrgrxzeh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gtqvxypjxx.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtjiqepgsn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gtmqksqsyn.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gtmkrmgnkx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gtjsnacxlk.html

[R62] 找最占空间的文件
来源：http://dali.gotoacloud.top/Article/details/gtwqnalgcg.html

du -ah . | sort -rh | head -10
来源：http://dali.vqdsnc.cn/Article/details/gttxiqjdrg.html

[R63] 内存与进程
来源：http://dali.sweek.top/Article/details/gtxmipcntz.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gtdqyvftpt.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gtfsnlhlcv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hywenlv.cn/Article/details/gtpdbrgwqk.html

[R65] 查看端口占用
来源：http://dali.jyoumei.cn/Article/details/gtxhjzpgxq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cashguo.top/Article/details/gtmjvgnsdm.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gtzszproxb.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gtxgcllawu.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gtqelxalzr.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gtsyrseqhk.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gtgwiuznqd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gtzbkkzirz.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gtprarbzcy.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gtvuepqprh.html

[R70] 时间戳与互转
来源：http://dali.aibaodan.cn/Article/details/gtnspkiepj.html

date +%s;  date -d @1700000000
来源：http://dali.nwbrower.top/Article/details/gtljqmjime.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtcmepbkxl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gtrbwtuodh.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gtevfnzzej.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtwddoxdwr.html

[R73] 分割大日志
来源：http://dali.yanxiufei.cn/Article/details/gtxvdsgela.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gthaqotjlk.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gtzjowwzrt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrymltppp.html

[R75] 导出环境变量
来源：http://dali.tanke756.top/Article/details/gtrddmqvzh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gtrszizhth.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gtdmzrxbpt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtyhyovjyt.html

[R77] 读取用户输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxatixwf.html

read -rp "请输入: " ans
来源：http://dali.tian-w.cn/Article/details/gtijlheyyn.html

[R78] 交互式菜单
来源：http://dali.9152youxi.cn/Article/details/gtenimewab.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gtwdmqgeae.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtyeinttlt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gtaogduzro.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gtqzjndqdn.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gtpqwiplzg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrmdonrjd.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtbxccnwpd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtaqlzehil.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtzzbmwycs.html

#include <stdio.h>
来源：http://dali.tanke756.top/Article/details/gtvvorkwsx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fengsongda.top/Article/details/gtubuzuxky.html

[S02] C：变量与格式化输出
来源：http://dali.tianlin.xyz/Article/details/gttkdsndkf.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangtech.top/Article/details/gthxkgmadj.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gtufwmcgsx.html

int x; scanf("%d", &x);
来源：http://dali.chenjidiqi.icu/Article/details/gtqkxbqszp.html

[S04] C：字符串复制
来源：http://dali.yonumen.top/Article/details/gtchpcbmhb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gttemcmerx.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gtwcjfdtpp.html

strlen(s)
来源：http://dali.shuidangran.top/Article/details/gtijmnktce.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtdvutwzge.html

strcmp(a, b) == 0
来源：http://dali.shuidangran.top/Article/details/gtmuzbwmkl.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqypnfmmf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gtnpjojefe.html

[S08] C：动态内存分配与释放
来源：http://dali.zhixingplan.top/Article/details/gtkvydixsm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gtbwbcwnwc.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gtmqqifshk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtygvvfwel.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gtghhwhbkd.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gtgflvzdxz.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtfbnnmwqn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.birdmap.top/Article/details/gtsycxrmvx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gtubtdpkrx.html

fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtawgxlvij.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gtmounkwiy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtnpndegpn.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gtzpktlbat.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gtvwalhymb.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtrrrqqwug.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gtiasqhucp.html

[S15] C：类型转换
来源：http://dali.yueranfly.top/Article/details/gtcvtmexff.html

(double) a / b
来源：http://dali.aibaodan.cn/Article/details/gtaiarqcxg.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gtckxqeowq.html

x |= (1 << 3);
来源：http://dali.yueranfly.top/Article/details/gtlddwmdps.html

[S17] C：安全拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtboevzqnu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuanzx.com/Article/details/gtpmezoraj.html

[S18] C：命令行参数
来源：http://dali.hnqzz.top/Article/details/gtccleovof.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydwvnoft.html

[S19] C：快速排序
来源：http://dali.aibaodan.cn/Article/details/gtszhucltk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtwcorwvye.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gtsdxstawm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtbdriwqxm.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gtvvwczvvo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhiwuduotai.top/Article/details/gtdmmbpwvg.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gtynimctuk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.havefunace.top/Article/details/gtdgwucqoz.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gtvlwvbohr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gtfivmbenw.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtxscqnvyc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gtyrqpdcps.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gtxctoeefs.html

memcpy(dst, src, n);
来源：http://dali.hnqzz.top/Article/details/gtvbvwfbok.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gthjgxkytv.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gtchbuqtoc.html

[S27] C：定义常量
来源：http://dali.jianghu66.top/Article/details/gtyrgiysnq.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtpfvzywjo.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gtqnxtgpev.html

static int counter = 0;
来源：http://dali.cheryme.top/Article/details/gtjfsdfoot.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gteslelbda.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtgjhcjprt.html

[S30] C：头文件保护
来源：http://dali.meibo888.top/Article/details/gtyvlazncn.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gtqgkrinhh.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gthquaenvr.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gtjqmthbwa.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtdddrypbf.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gtcijhdcmk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhoulong.xyz/Article/details/gtgtdsgcgk.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxakhjfr.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gtksiqbfje.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gtjwffjuym.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtlcqhrmoc.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtjapbvbvd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.havefunace.top/Article/details/gtqkjtbjir.html

[S35] C++：map
来源：http://dali.gaohongyu789.top/Article/details/gtrfkjlytd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetfrmcdu.html

[S36] C++：unordered_map
来源：http://dali.ehwqpu.com/Article/details/gtdmwcgrow.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtijqhxoka.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtdhvclimm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepjyuicz.html

[S38] C++：排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgswtkzxv.html

std::sort(v.begin(), v.end());
来源：http://dali.sysykeji.top/Article/details/gtafvlptmq.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxuanxn.top/Article/details/gtankcdeaf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gtgxilxlzx.html

[S40] C++：查找元素
来源：http://dali.hywenlv.cn/Article/details/gtdmazrnmw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.316326.xyz/Article/details/gtyvzvacsy.html

[S41] C++：类与构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtcvwjfwya.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gtbdmgilyn.html

[S42] C++：继承与虚函数
来源：http://dali.ybcxt.top/Article/details/gtjyakhtim.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhengqikj.top/Article/details/gtykspenom.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gtqdejxpig.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwlggtkr.html

[S44] C++：引用传参
来源：http://dali.yangfankeji.com/Article/details/gtlfadmpes.html

void inc(int &x) { ++x; }
来源：http://dali.daxiang520.top/Article/details/gtafcoxuha.html

[S45] C++：lambda
来源：http://dali.zycfv.cn/Article/details/gtxxafjdzo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gtyjqybdii.html

[S46] C++：函数模板
来源：http://dali.zhongyouzk.top/Article/details/gtwwgpasri.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gtqggcwtml.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenlongwang.top/Article/details/gtrekopgke.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjumlmou.html

[S48] C++：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtqurkjtiy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zycfv.cn/Article/details/gtoybzqfnm.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmfgvrcc.html

[S49] C++：写文件
来源：http://dali.jiagoushi.top/Article/details/gtjtwnjcwd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fengsongda.top/Article/details/gtyclbmmkq.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gtdiyokyeb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtglntwslx.html

[S51] C++：显式类型转换
来源：http://dali.dashuyun.cn/Article/details/gtexabvhxs.html

static_cast<double>(a) / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymzqmrav.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gtcsktvmwp.html


<!-- 参考信息 -->