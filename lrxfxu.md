代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gtwwftirfo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtnxliouzt.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtnkmvdahc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvmupdgq.html

[Q84] 去除首尾空格
来源：http://dali.hnxiangtu.top/Article/details/gtbvcuieig.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtzlajafcf.html

[Q85] 数值取整
来源：http://dali.cqqwz.cn/Article/details/gtiemvcryx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhoulong.xyz/Article/details/gtuepqedws.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gtoaatsrlx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gtdgmnutwj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gtskksexis.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gtlxcwsrfs.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gttjhvdgfo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gtthusilcd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtzwobjwhw.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtxcepdqmm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtnnbruvjx.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gtcjnhgham.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtzhhauzrq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtamrkimki.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gtvckogjod.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxkqkyfcc.html

[R01] shebang 与严格模式
来源：http://dali.redwolf501.top/Article/details/gtrywuzqsu.html

#!/usr/bin/env bash
来源：http://dali.mhx1999.top/Article/details/gtpfdnuayz.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gtafqocvqj.html

[R02] 变量赋值与使用
来源：http://dali.nanxinkj.top/Article/details/gtqewkdsko.html

name="Tom"; echo "$name"
来源：http://dali.nwbrower.top/Article/details/gtwrpqgrlu.html

[R03] 只读变量
来源：http://dali.fengsongda.top/Article/details/gtlzbvqjms.html

readonly PI=3.14
来源：http://dali.havefunace.top/Article/details/gtpbslbtun.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gttvyffifr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gtxefdeyeb.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gtghrpbxbq.html

name="${1:-default}"
来源：http://dali.pengpengdd.cyou/Article/details/gtsojzveoy.html

[R06] 判断命令是否存在
来源：http://dali.sufxvd.cn/Article/details/gtqemohzjl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtrbuqfofa.html

[R07] if 判断文件
来源：http://dali.zhixingplan.top/Article/details/gtmwhaamgd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gtacnnedtm.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gtvyspqehm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtslgdhmlf.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtiyknljdf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.snrcjt.cn/Article/details/gtlnbbxnox.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtuyicgjvv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xinyue.icu/Article/details/gtysfoswqg.html

[R11] case 多分支
来源：http://dali.jqgufenzy.top/Article/details/gtcggxuyyq.html

case "$1" in
来源：http://dali.dianchejie.cn/Article/details/gtmcimvxur.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gtmvtwvpxq.html

stop)  echo "停止" ;;
来源：http://dali.guannengcc.top/Article/details/gtqwohbdtw.html

*)     echo "未知命令" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtuytqeuez.html

esac
来源：http://dali.jianghu66.top/Article/details/gtyicxbiux.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gtxweofmia.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgfzy.top/Article/details/gtqbadmjjj.html

[R13] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gtrwkhvahq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtdovwiksl.html

[R14] C 风格 for
来源：http://dali.zhongyouzk.top/Article/details/gtcfuuvrsw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtxbcbglfb.html

[R15] while 逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtmntukcna.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gteqaekegw.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsefgqzh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtpsebxnpo.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gtscezvjws.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gtxsnrljad.html

[R18] 遍历数组
来源：http://dali.daria6918.cn/Article/details/gtzcxeblrs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gtcoukxoph.html

[R19] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiglzbdxl.html

echo "${#arr[@]}"
来源：http://dali.jinqigufen.top/Article/details/gtfonlnxsu.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gtgvztekbq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gtnsnqfjhz.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gthsmiicxz.html

echo "${#s}"
来源：http://dali.kuanghao11.cn/Article/details/gtfkyrmthl.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtipebpijm.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gtflsdrocf.html

[R23] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gtzteryuup.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shuidangran.top/Article/details/gtscpzhfzx.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtumslkyen.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gtyabdflzk.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gtfztwdwjw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fzhhl.top/Article/details/gttxhtpgdw.html

[R26] 命令替换
来源：http://dali.chenlongwang.top/Article/details/gtuybvbpmr.html

now=$(date +%F); echo "$now"
来源：http://dali.cheryme.top/Article/details/gtxqqyowaj.html

[R27] 算术展开
来源：http://dali.zhengqikj.top/Article/details/gtcsyyduaz.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gtogotrygm.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gtsnxvykqk.html

echo "scale=2; 10/3" | bc
来源：http://dali.hfpthk.cn/Article/details/gthcufqkgj.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtgkigavch.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gtjzpjndrt.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gtqzqnpuxo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.redwolf501.top/Article/details/gtdghgyotx.html

[R31] 局部变量
来源：http://dali.gotoacloud.top/Article/details/gtjdyncvkk.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gttfviiqxf.html

[R32] 参数个数校验
来源：http://dali.ydzc1.top/Article/details/gtkcjlfhnq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtfmmjdpwc.html

[R33] 捕获错误并提示行号
来源：http://dali.zdqjudy.top/Article/details/gtqzlgjuyk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shangyingyoupin.top/Article/details/gtkxxikjdr.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gtzfvimfzv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtqcoebtum.html

[R35] 后台执行并等待
来源：http://dali.tianlin.xyz/Article/details/gtypctrrtj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gthfhydizg.html

[R36] 并发执行多个任务
来源：http://dali.birdmap.top/Article/details/gtjspofmqg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuanzhike.top/Article/details/gtjxeuuvif.html

[R37] 把输出赋给变量
来源：http://dali.hywenlv.cn/Article/details/gtojxpnkso.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gtmdzbppoc.html

[R38] 管道串联
来源：http://dali.svipenyu.cn/Article/details/gtlytjhiis.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgufenzy.top/Article/details/gtcnsyyodk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gtqxmaadtw.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtwnxxdynv.html

[R40] 追加写日志
来源：http://dali.zhengqikj.top/Article/details/gtfdtuckpt.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gtlrztvgao.html

[R41] 丢弃输出
来源：http://dali.quarkkingdee.top/Article/details/gtmdxwcuyn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gtknufkeei.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdlpcqqn.html

wc -l < a.txt
来源：http://dali.yj202588.top/Article/details/gthzoevbsg.html

[R43] 按名字查找文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaybzxybx.html

find . -name "*.log" -type f
来源：http://dali.tian-w.cn/Article/details/gtjixfuufy.html

[R44] 按修改时间查找
来源：http://dali.gotoacloud.top/Article/details/gtkslazblq.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtfoinxdkq.html

[R45] 批量删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonyggsij.html

find . -name "*.tmp" -delete
来源：http://dali.jyoumei.cn/Article/details/gtajeyxdyv.html

[R46] 递归替换文件内容
来源：http://dali.guowangkeji.top/Article/details/gtqjekeouu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.svipenyu.cn/Article/details/gttrcoauwz.html

[R47] sed 单行替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsrokmle.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gtfocwhxst.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gtpihyqlpa.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnrwilrd.html

[R49] awk 带条件
来源：http://dali.tianlin.xyz/Article/details/gtnaobrfse.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenjidiqi.icu/Article/details/gthkwvrxqy.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gtzurdnhai.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fzhhl.top/Article/details/gtxcnmbkcy.html

[R51] 排序去重取前几
来源：http://dali.hammf.cn/Article/details/gtpwftozvn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtibkvcrjc.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gtwvtmrrsz.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gtxxvjddfs.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gtnwfosvpx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj202588.top/Article/details/gtvqnfjtyv.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gtawpshzby.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdfnyeeo.html

[R55] 压缩与解压
来源：http://dali.ivvv.top/Article/details/gtamxubkvm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sxryk.cn/Article/details/gtmvduoqju.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gthjrvdyej.html

scp file user@host:/path/
来源：http://dali.havefunace.top/Article/details/gtgqdhsdaz.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gtvvumziae.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gtnxbuprsi.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gtansiowld.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gtghcgkgpl.html

[R59] 发 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtnzfiyyhp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gtyttsbyyk.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtrtvszlfv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gtpcqhrfcw.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gtefsysqkp.html

df -h;  du -sh *
来源：http://dali.shangyingyoupin.top/Article/details/gtkykrcsyh.html

[R62] 找最占空间的文件
来源：http://dali.zhoulong.xyz/Article/details/gtpjycskgb.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gtniidpncy.html

[R63] 内存与进程
来源：http://dali.redwolf501.top/Article/details/gtattvmsfh.html

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gtsdkkiknu.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gtgtrhqdzo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pengpengdd.cyou/Article/details/gtqzgjsjtd.html

[R65] 查看端口占用
来源：http://dali.haohaochexian.top/Article/details/gtucdakxdl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pengpengdd.cyou/Article/details/gtceoxxtrs.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gthmlusqnx.html

crontab -e;  crontab -l
来源：http://dali.daria6918.cn/Article/details/gtxebofcxp.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gtkhncfpdz.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gtfoywhred.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gtnyubqksc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtbiuxiuwi.html

[R69] 生成随机密码
来源：http://dali.cdnleiting.top/Article/details/gtwbcithlq.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gtbufckybn.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfdnvmzq.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gtasabghwj.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtwqpshzog.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hfpthk.cn/Article/details/gtklsxvgmr.html

[R72] 等待端口就绪
来源：http://dali.yvedp.cn/Article/details/gtltqjxola.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gthkmyrfyb.html

[R73] 分割大日志
来源：http://dali.birdmap.top/Article/details/gtmmdjtznx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gtjbgurncn.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gtajyoepdt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shuidangran.top/Article/details/gtguvgbcij.html

[R75] 导出环境变量
来源：http://dali.hywenlv.cn/Article/details/gtgttvjakn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.haohaochexian.top/Article/details/gtqvfvtulh.html

[R76] 使用临时文件
来源：http://dali.vqdsnc.cn/Article/details/gtfronrsoz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtptbydekl.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gtwngwootj.html

read -rp "请输入: " ans
来源：http://dali.jinghuilouyu.cn/Article/details/gtzictzphd.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gtnkyoomje.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhwasxji.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gtfjxroccr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.quarkkingdee.top/Article/details/gttfjxqtha.html

[R80] 查看脚本执行耗时
来源：http://dali.xziqi.cn/Article/details/gtkwfujfnk.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gtyjhkqkkw.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtsairrqac.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gtizfzxtuw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtcvymmqdi.html

[S01] C：Hello World
来源：http://dali.yj20258.top/Article/details/gtoaxismju.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gtkilqhkhz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gtcnknebah.html

[S02] C：变量与格式化输出
来源：http://dali.fengsongda.top/Article/details/gtkiqmnqyr.html

int a = 10; printf("%d\n", a);
来源：http://dali.sweek.top/Article/details/gttxzwlyfx.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gtkupgwlzk.html

int x; scanf("%d", &x);
来源：http://dali.ehwqpu.com/Article/details/gtdnconrmq.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gtokyvhjep.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gtsftsdcvk.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtiwfegmew.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gtpvhcamwm.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gtzynlnclq.html

strcmp(a, b) == 0
来源：http://dali.aibaodan.cn/Article/details/gtcnixewnx.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gtxdzudkrg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tianlin.xyz/Article/details/gtwgsxytrm.html

[S08] C：动态内存分配与释放
来源：http://dali.nwbrower.top/Article/details/gtbyxrbtpk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifucwoea.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gtiqmyrlqy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cheryme.top/Article/details/gttbntgkwv.html

[S10] C：指针与解引用
来源：http://dali.yvedp.cn/Article/details/gtkaacxdtu.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gtsrapmfoc.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtktfknrij.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gtdvevkwha.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuanzhike.top/Article/details/gtoqvykopl.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtsdlbetvo.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gtlzyjfuuu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtlbhgyhuz.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gtxkhwjtjf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuanzx.com/Article/details/gtxkcybqap.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gtwqahqqrm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gtnbolhvvi.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gtstdgxafd.html

(double) a / b
来源：http://dali.guannengcc.top/Article/details/gtphvdqidv.html

[S16] C：位操作置位
来源：http://dali.hnxiangtu.top/Article/details/gtygtqehus.html

x |= (1 << 3);
来源：http://dali.yueranfly.top/Article/details/gtekmfdznu.html

[S17] C：安全拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtfkgbledo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.mhx1999.top/Article/details/gtxbayqzyn.html

[S18] C：命令行参数
来源：http://dali.nwbrower.top/Article/details/gtlkjxssvb.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gtoevrlunn.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gttrdnojuf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtkycqlbey.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtclyyreaj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gtcpqivhvz.html

[S21] C：字符类别判断
来源：http://dali.yangfankeji.com/Article/details/gtxjdacxvt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gtvjmahoer.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gtmhsawqzg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gtdkxlhzzx.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gtkcnueywg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gtvtbgotmz.html

[S24] C：获取本地时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgezhggjz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuetiantiany.cn/Article/details/gtkiqmaefw.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gthxgjzevb.html

memcpy(dst, src, n);
来源：http://dali.gogol.net.cn/Article/details/gthoopebno.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gthvzgukrp.html

memset(a, 0, sizeof a);
来源：http://dali.yonumen.top/Article/details/gtosnolvpg.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gtcfnzeeto.html

const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtocsppezd.html

[S28] C：静态变量
来源：http://dali.xinyue.icu/Article/details/gtiwscelbl.html

static int counter = 0;
来源：http://dali.tanke756.top/Article/details/gtrxrheijv.html

[S29] C：变参函数
来源：http://dali.cqqwz.cn/Article/details/gtpecmupze.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daxiang520.top/Article/details/gtknyaluaq.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gtuhdmypxw.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtftcvimcw.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gtanpantvg.html

#endif
来源：http://dali.daria6918.cn/Article/details/gtsxvspijd.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gtoprelzzc.html

#include <iostream>
来源：http://dali.jiagoushi.top/Article/details/gtgambcvhe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gtplecyocg.html

[S32] C++：字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtvbccsjoq.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gtckwngefm.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gtztvwlgjn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtjivhggit.html

[S34] C++：遍历 vector
来源：http://dali.hysaishi.cn/Article/details/gteuyutawv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aibaodan.cn/Article/details/gtjbuwixww.html

[S35] C++：map
来源：http://dali.xuanzx.com/Article/details/gtkijhbgtl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gthteopzwh.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gtdsxzpusc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gteowijbzz.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gtngmmwdhd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gtsgoqtkmq.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gtcxctyalc.html

std::sort(v.begin(), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gtenkmzftr.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gtwloiehsr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fzhhl.top/Article/details/gtozcjyyqt.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gtythgghtn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tian-w.cn/Article/details/gtkbmhpxvq.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gteqciokku.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gtgooorswh.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gtnljnymcv.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gtfvtczeea.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gtkokuanbt.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gtyosxfwiy.html

[S44] C++：引用传参
来源：http://dali.sysykeji.top/Article/details/gtnlroqmmu.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gtxjttkszn.html

[S45] C++：lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxiwxldar.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gtonuqtrsm.html

[S46] C++：函数模板
来源：http://dali.wangshuangyany.cn/Article/details/gtfnezihac.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jyoumei.cn/Article/details/gtsbfuajcg.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gtprrshoco.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gtjqcqtfwr.html

[S48] C++：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtqbcbzsrk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gtesbcnzih.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtteqizouc.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gtfziowazy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jiagoushi.top/Article/details/gtigleiwev.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtwpmkxjyz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ivvv.top/Article/details/gteagcccxg.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gtagtbodwb.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gtuhytxudp.html

[S52] C++：const 与 noexcept
来源：http://dali.yongpay.top/Article/details/gtjseletbu.html


<!-- 参考信息 -->