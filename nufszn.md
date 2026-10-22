代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gtzvrvajcu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtkoyqsozp.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtzuqptzvu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtdzrommso.html

[Q84] 去除首尾空格
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyheomnf.html

SELECT TRIM(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtvqtulnvb.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gtldsjovml.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xylfe.cn/Article/details/gtkwqgoetl.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gthtronluw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yangfankeji.com/Article/details/gtbehaayks.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtlciqpivr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gtevmxmgja.html

[Q88] 行转列（条件聚合）
来源：http://dali.bjfxy.top/Article/details/gtctmqcavf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.0kj1m.cn/Article/details/gttwzxngxr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sxryk.cn/Article/details/gtpfccfsvk.html

[Q89] 判断表是否存在
来源：http://dali.cucudq.cn/Article/details/gtugxizxtq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gticpvahjy.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gtakkdgdpd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.snrcjt.cn/Article/details/gtfzdbrvps.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxicivura.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gtylmlxwjd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtyfbwenpu.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gtqxhihqwc.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gteplxhujt.html

set -euo pipefail
来源：http://dali.ehwqpu.com/Article/details/gtldevldnn.html

[R02] 变量赋值与使用
来源：http://dali.redwolf501.top/Article/details/gtrrpvgphh.html

name="Tom"; echo "$name"
来源：http://dali.zycfv.cn/Article/details/gtldbmjvia.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gtoopocsgc.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gttcgvvcxw.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gtuidpwupr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yonumen.top/Article/details/gtjrnwbebf.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gtursoqqry.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gtbldmoftj.html

[R06] 判断命令是否存在
来源：http://dali.gogol.net.cn/Article/details/gtrqnwwljz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtvmctxasa.html

[R07] if 判断文件
来源：http://dali.cashguo.top/Article/details/gtjjtdqsfm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gtlsjugbes.html

[R08] 数值比较
来源：http://dali.xylfe.cn/Article/details/gtofaooegs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gtohkyzbtp.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtnehmketz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtjitcdpjo.html

[R10] 正则匹配
来源：http://dali.smart0.xyz/Article/details/gtkgtyjcrd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gteaanazjf.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtwwrclcfy.html

case "$1" in
来源：http://dali.gzhubu.top/Article/details/gtqinngjsu.html

start) echo "启动" ;;
来源：http://dali.sufxvd.cn/Article/details/gtmvtgoamr.html

stop)  echo "停止" ;;
来源：http://dali.redwolf501.top/Article/details/gtglxetnfj.html

*)     echo "未知命令" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtyzntqmqk.html

esac
来源：http://dali.nanxuanxn.top/Article/details/gttryuervr.html

[R12] for 遍历文件
来源：http://dali.pycfn.com/Article/details/gtihtfguwo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gtmhoddptk.html

[R13] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfwskwzy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbjsccbo.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gtbkcfcsij.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtmpjbjetk.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtmjwtylcb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yueranfly.top/Article/details/gtqcbwbeaq.html

[R16] until 等待条件
来源：http://dali.zhixingplan.top/Article/details/gtckucuabr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtzdbdzmlr.html

[R17] 数组定义与取值
来源：http://dali.cqqwz.cn/Article/details/gtwkyapjzv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.svipenyu.cn/Article/details/gtgfgtnarb.html

[R18] 遍历数组
来源：http://dali.svipenyu.cn/Article/details/gtxhsvyjao.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtmzohcfgj.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtluonsipo.html

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvyeesnc.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gtuzzcohbn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gtpzlubnur.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtyidmyozz.html

echo "${#s}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxaxkgoo.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtcevyanpd.html

echo "${s:0:5}"
来源：http://dali.jyoumei.cn/Article/details/gtahfovfie.html

[R23] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gtoldixabs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhixingplan.top/Article/details/gtoncjfgby.html

[R24] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmhbqszn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aizwys.cn/Article/details/gtqxurawoc.html

[R25] 去后缀 / 去前缀
来源：http://dali.sxryk.cn/Article/details/gtftabrkid.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cashguo.top/Article/details/gtktsmtgpe.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gtrpumduvb.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gtlamrjcen.html

[R27] 算术展开
来源：http://dali.yongpay.top/Article/details/gtzptyyspj.html

echo $((1 + 2 * 3))
来源：http://dali.cheryme.top/Article/details/gtwiekjqhp.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gtmojzlmoy.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangdashe.top/Article/details/gtcmnabbni.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtcaguvnty.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.9152youxi.cn/Article/details/gtgqfcslxl.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gtvoyldlzl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gtukqeblag.html

[R31] 局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gtitscmmnj.html

f() { local x=1; echo "$x"; }
来源：http://dali.mhx1999.top/Article/details/gtpeolfpxw.html

[R32] 参数个数校验
来源：http://dali.ppjwa.cn/Article/details/gteiajcvog.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtgdyppctk.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gtkrkiafxl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gtdqfqggwv.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gtutpbqkon.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfivrkzg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtckhxgkjc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhiwuduotai.top/Article/details/gtknixmkcd.html

[R36] 并发执行多个任务
来源：http://dali.xinyue.icu/Article/details/gtzbxxxvoa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gtlzvtuirz.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gtmbghesqc.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gtpgllijmb.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gtbzkpafan.html

cat a.txt | grep -i error | wc -l
来源：http://dali.andypj.xyz/Article/details/gtldzpwxcd.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gtlevpqmrh.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gtunyeanan.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gtnvgwrior.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gtstouroqw.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gtvzjhtytp.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtabstqyoj.html

[R42] 输入重定向
来源：http://dali.jinqigfzy.top/Article/details/gtvszriodj.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gtwrmwnjll.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gtqrvwicyp.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gtrylycwry.html

[R44] 按修改时间查找
来源：http://dali.yj20258.top/Article/details/gtegnbiopb.html

find . -mtime -7 -type f
来源：http://dali.mhx1999.top/Article/details/gtklhybzcn.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnrtgzjo.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gtsdvweafs.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gtbiwifwxo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gtqhxmwuag.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gtacbdwhcs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtqdxodvht.html

[R48] awk 取指定列
来源：http://dali.vqdsnc.cn/Article/details/gtmkwmdkvg.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gttuwrxhxq.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gtamifvdgn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gtoaxvuxuk.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfoyidxuo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtrrlytlrj.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gtlvljofdw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gtwevwhind.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gtuzwkgrmx.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gteifblcgi.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gtgklemlot.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.redwolf501.top/Article/details/gtwekoqtcf.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtmpzzzzlu.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gttioniidu.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gtcfgkiwoq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gtixlxwnip.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gtlsjsodks.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gtpkphacix.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gtuopgtsbu.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gtlaclizdn.html

[R58] 下载文件
来源：http://dali.jqgufenzy.top/Article/details/gtooaifblh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yueranfly.top/Article/details/gtqquiaixv.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gthulporel.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gtskqeulgu.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtehgumyre.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gtfrxhpdet.html

[R61] 磁盘占用
来源：http://dali.cashguo.top/Article/details/gtelzkoupm.html

df -h;  du -sh *
来源：http://dali.hammf.cn/Article/details/gtqaivigrq.html

[R62] 找最占空间的文件
来源：http://dali.yonumen.top/Article/details/gtydavevoa.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gtbtuwmwfe.html

[R63] 内存与进程
来源：http://dali.meibo888.top/Article/details/gtcdpynnoo.html

free -h;  ps aux | grep nginx
来源：http://dali.chenlongwang.top/Article/details/gteeyzikzh.html

[R64] 结束进程
来源：http://dali.316326.xyz/Article/details/gtijkzfkab.html

kill -9 $(pgrep -f app.py)
来源：http://dali.9152youxi.cn/Article/details/gtpwevvrnx.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gthacpkuxp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gtxzwtjwcr.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gtulcvexmh.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gtapaivdcy.html

[R67] 生成随机十六进制串
来源：http://dali.guannengcc.top/Article/details/gtkwzyrxzx.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gtsnvzbtjh.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gtzpeoutnl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cucudq.cn/Article/details/gtyefgnnef.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gthivivjmd.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gtrshrcfmr.html

[R70] 时间戳与互转
来源：http://dali.gzhubu.top/Article/details/gtggjkpnno.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gtdcgqvfpe.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtgalekpua.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gthnunvzmy.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gtxtsldnmx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtkxtuuuwz.html

[R73] 分割大日志
来源：http://dali.fengsongda.top/Article/details/gtomowjiwz.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gtfprkttbn.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtqokybyso.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtlqzwmbhq.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gtsxfupmzj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhiwuduotai.top/Article/details/gtyuxyydzt.html

[R76] 使用临时文件
来源：http://dali.jlsjyb.cn/Article/details/gtdcnykkql.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtfbijooze.html

[R77] 读取用户输入
来源：http://dali.andypj.xyz/Article/details/gtpflnfbat.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gtjcapczhv.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gtxkaphkum.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gtzjfcyswc.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllhtgjgh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gtqxjuqeio.html

[R80] 查看脚本执行耗时
来源：http://dali.chenlongwang.top/Article/details/gtewxzihus.html

time ./run.sh
来源：http://dali.shuidangran.top/Article/details/gtobkjsntr.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtstxryduy.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gtmmwftntf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdafcuqvl.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gtafvekiky.html

#include <stdio.h>
来源：http://dali.zhoulong.xyz/Article/details/gtixoiogqa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gtjcxukfbv.html

[S02] C：变量与格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtpkpqynml.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gtpoidudnk.html

[S03] C：读入整数
来源：http://dali.hammf.cn/Article/details/gtdfkrocra.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gtmljsmxzh.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskfxfhnu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gtzqcrhgpi.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtyapvznul.html

strlen(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtppyqamhc.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtfnqgwqut.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gtpuweckee.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufpbdmnk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yvedp.cn/Article/details/gtesrkcpxr.html

[S08] C：动态内存分配与释放
来源：http://dali.jlsjyb.cn/Article/details/gtlzejjqpd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfchuyrbt.html

[S09] C：结构体定义与初始化
来源：http://dali.jlsjyb.cn/Article/details/gtawcgjufb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gtnkiinsil.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gtplxpwgeb.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gtwvumalzw.html

[S11] C：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtljfcpteq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlilixqsc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gttlomiddv.html

fclose(f);
来源：http://dali.sweek.top/Article/details/gtxllfqdoc.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgmgsgmn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqctleroe.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gtosgpimoq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtgtdcat.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gtbbceltzu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gtynqlopye.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gtwezgjgpi.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gtxkrqppjn.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gtedgywdgk.html

x |= (1 << 3);
来源：http://dali.yueranfly.top/Article/details/gtowckmmfr.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtpnkfdsjx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.snrcjt.cn/Article/details/gtjajdtuaw.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gtszzkmcst.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gtqrwxqmwe.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gtfqswchqu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtdfbgoocs.html

[S20] C：二分查找
来源：http://dali.hysaishi.cn/Article/details/gtaglybzsf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtphkveptr.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gtoxbtcuxl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gtbwbmwodh.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gtystmoqop.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tianlin.xyz/Article/details/gtctuoalba.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gtnmsuyxga.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gtfbnqspso.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gtujzjprsd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gtgqxostce.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtsahhvbnl.html

memcpy(dst, src, n);
来源：http://dali.vqdsnc.cn/Article/details/gtqxispygb.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gtexbvqleh.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gtgzqyazsx.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjainhva.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtalgmgbsj.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gtpygesaal.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gtexuqzogj.html

[S29] C：变参函数
来源：http://dali.ydzc1.top/Article/details/gtpfvzhaoz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gthkntualu.html

[S30] C：头文件保护
来源：http://dali.xziqi.cn/Article/details/gtuxuuebiw.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gtqoqkqzez.html

#define X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtleeasnuc.html

#endif
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfqnncmc.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtujfqrfzm.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gtjgkzuerc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cashguo.top/Article/details/gttagqmxvk.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtqckanoyo.html

std::string s = "hi";  s += "!";
来源：http://dali.ppjwa.cn/Article/details/gthtzskdhh.html

[S33] C++：vector 增删
来源：http://dali.gaohongyu789.top/Article/details/gtksfggxeq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sxryk.cn/Article/details/gttbswktkz.html

[S34] C++：遍历 vector
来源：http://dali.aizwys.cn/Article/details/gtzfoyhoif.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gtiiscyfgj.html

[S35] C++：map
来源：http://dali.yonumen.top/Article/details/gtnmqexuzv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtxsfibjck.html

[S36] C++：unordered_map
来源：http://dali.xinyue.icu/Article/details/gtqqqbuock.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gtrasxjiat.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxvjqqoy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gtkxsuqzqq.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gtjniowfui.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtwxlhckkv.html

[S39] C++：自定义比较器排序
来源：http://dali.ppjwa.cn/Article/details/gtnixakmgv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gtjyyvwtpg.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gtunzzgzuq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gtmsfjfcit.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gtwmkapsne.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dianchejie.cn/Article/details/gtoegncsfb.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gthjvwrvyw.html

class B : public Base { public: void f() override {} };
来源：http://dali.c1oappe.top/Article/details/gtawxhyaus.html

[S43] C++：智能指针
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvdnlkzm.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gtudwrtvbb.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gtihryzlno.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gtjjoxgfty.html

[S45] C++：lambda
来源：http://dali.sufxvd.cn/Article/details/gtydnhlqyw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zycfv.cn/Article/details/gtrhubdbhe.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gtpktjxvex.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gtznkpzwzq.html

[S47] C++：结构化绑定遍历
来源：http://dali.tian-w.cn/Article/details/gthwbzkzmx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gtxvysljcc.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtgdohvvgb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jyoumei.cn/Article/details/gtynovlxds.html

while (std::getline(in, line)) { }
来源：http://dali.ybcxt.top/Article/details/gtuielpeth.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gtaaaeoonl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gtrkyysnhg.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gtanhushey.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtynuuzaiw.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gtzzhksijf.html

static_cast<double>(a) / b
来源：http://dali.quarkkingdee.top/Article/details/gttgslacza.html

[S52] C++：const 与 noexcept
来源：http://dali.yuxming.cn/Article/details/gtjicubyik.html


<!-- 参考信息 -->