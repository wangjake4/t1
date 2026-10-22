代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gt2ssogrvxw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gt2qrnnutth.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2zfpmadun.html

[Q89] 判断表是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2lejlsprp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gt2kyajakkk.html

[Q90] 生成序号列
来源：http://dali.gaohongyu789.top/Article/details/gt2udyuqqxi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shuidangran.top/Article/details/gt2yvxylsoi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2vrgywhvi.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gt2ffapvnep.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ttqdhsts.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gt2eudhwwej.html

#!/usr/bin/env bash
来源：http://dali.svipenyu.cn/Article/details/gt2dwmssxxc.html

set -euo pipefail
来源：http://dali.zhengqikj.top/Article/details/gt2qrbpcuvs.html

[R02] 变量赋值与使用
来源：http://dali.meibo888.top/Article/details/gt2avoxtlrj.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gt2hgavjmgy.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gt2agbyfjjh.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gt2icjcarhf.html

[R04] 位置参数
来源：http://dali.haohaochexian.top/Article/details/gt2btnzyhhf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gogol.net.cn/Article/details/gt2qknkkfpe.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gt2pbgwxclb.html

name="${1:-default}"
来源：http://dali.gaohongyu789.top/Article/details/gt2ozmngcvd.html

[R06] 判断命令是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgoafjtm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gt2akksdmtf.html

[R07] if 判断文件
来源：http://dali.snrcjt.cn/Article/details/gt2mzgsqugu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gt2zyssibjt.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gt2jyuzaaya.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zycfv.cn/Article/details/gt2zbvtmcge.html

[R09] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gt2fkllnwoz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gt2pvqpebte.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gt2gqhgneqy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gt2nqlueojv.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gt2higggwqh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtnerio.html

start) echo "启动" ;;
来源：http://dali.shuidangran.top/Article/details/gt2pajhdoqt.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gt2objwfqlg.html

*)     echo "未知命令" ;;
来源：http://dali.birdmap.top/Article/details/gt2ljmbtaiq.html

esac
来源：http://dali.nanxinkj.top/Article/details/gt2qhehslez.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gt2qlwsqxru.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ojsuvwwn.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gt2ioqhamjv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gt2qpydcvxt.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gt2lpoxdzvg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gt2iiprqtpu.html

[R15] while 逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2euwmmtrz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ppjwa.cn/Article/details/gt2tdmaxjaj.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gt2hoigfcmd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2oiygdots.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gt2dtzepxha.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gt2rvfpgxrf.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gt2bblyhhym.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gt2gqyywdpc.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gt2kicklieb.html

echo "${#arr[@]}"
来源：http://dali.nanxuanxn.top/Article/details/gt2gsvgqfmi.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gt2tfkyqqls.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.birdmap.top/Article/details/gt2pkkjxxia.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gt2ewoccryk.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gt2jsezydtn.html

[R22] 截取子串
来源：http://dali.sweek.top/Article/details/gt2fldcmnlm.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gt2smmwcjhb.html

[R23] 字符串替换
来源：http://dali.cheryme.top/Article/details/gt2nlepgccw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gt2ourttyol.html

[R24] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grptxest.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rdbuqjqt.html

[R25] 去后缀 / 去前缀
来源：http://dali.gaohongyu789.top/Article/details/gt2eooafham.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gt2pyeumvle.html

[R26] 命令替换
来源：http://dali.jqgfzy.top/Article/details/gt2nmuhezez.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gt2edzknpjh.html

[R27] 算术展开
来源：http://dali.zhengqikj.top/Article/details/gt2bmyvymlu.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2mqupocnl.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sqhwyxnc.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gt2aufpwlcv.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2rprhyjgs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gt2odvugcwn.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gt2fbeblwhn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gotoacloud.top/Article/details/gt2xjbdaohx.html

[R31] 局部变量
来源：http://dali.yj20258.top/Article/details/gt2rxsujcuv.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qusecgdh.html

[R32] 参数个数校验
来源：http://dali.mhx1999.top/Article/details/gt2zbuopwiv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2varokupq.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gt2iobrfzhk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zycfv.cn/Article/details/gt2omuuhfbs.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gt2vvmtjgtl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gt2rcbphqti.html

[R35] 后台执行并等待
来源：http://dali.chenlongwang.top/Article/details/gt2asibmhln.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gt2jumqfjzh.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gt2qaknwlkr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gt2fyhoxugr.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gt2hrepoxjy.html

files=$(ls -1)
来源：http://dali.birdmap.top/Article/details/gt2pvlwholh.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vawfwovq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenjidiqi.icu/Article/details/gt2tqnkxqlz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gt2vrgjxmlk.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gt2csgzqyuj.html

[R40] 追加写日志
来源：http://dali.zycfv.cn/Article/details/gt2ocirrqst.html

echo "log" >> out.log
来源：http://dali.zhixingplan.top/Article/details/gt2qxmcpvjf.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gt2atgapqek.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gt2bgrjoaso.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gt2puvmbifq.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gt2lisweqmr.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gt2tyqogaim.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gt2pizzuidj.html

[R44] 按修改时间查找
来源：http://dali.quarkkingdee.top/Article/details/gt2vqyhaiwm.html

find . -mtime -7 -type f
来源：http://dali.gzhubu.top/Article/details/gt2hdgdcaxt.html

[R45] 批量删除
来源：http://dali.guowangkeji.top/Article/details/gt2ffmbsumh.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gt2pnripttn.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gt2qzivypsz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gt2vfzxqchz.html

[R47] sed 单行替换
来源：http://dali.ppjwa.cn/Article/details/gt2wjqehhlg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aizwys.cn/Article/details/gt2dqpmyjfm.html

[R48] awk 取指定列
来源：http://dali.havefunace.top/Article/details/gt2plxkcrlf.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2dpmuoewj.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gt2gbrtrkwz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.andypj.xyz/Article/details/gt2cpdcgvgp.html

[R50] awk 求和
来源：http://dali.xuanzx.com/Article/details/gt2odpznyjv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2afpdrmur.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gt2lnnlhhcv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ydzc1.top/Article/details/gt2acuntvuh.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gt2pcdmbpfe.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2gkgvcmss.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gt2aoyfeekg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gt2azryoqvk.html

[R54] 比较两个文件
来源：http://dali.dashuyun.cn/Article/details/gt2jmmjwhah.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gt2ucqsopxt.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gt2lzrsqsqx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sufxvd.cn/Article/details/gt2uyxjcuvq.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gt2wpepkmxa.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gt2pyjdssnw.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gt2pkajmhsm.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gt2uupacoan.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iixbfknb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gt2bjsndsip.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2uffbgacs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.316326.xyz/Article/details/gt2srhlpeif.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2uciqowch.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gt2jvoeoqps.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gt2bziikyjo.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gt2tfpegubu.html

[R62] 找最占空间的文件
来源：http://dali.0kj1m.cn/Article/details/gt2vouyokkt.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gt2rnpgntqw.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gt2ucqqnqlj.html

free -h;  ps aux | grep nginx
来源：http://dali.xinyue.icu/Article/details/gt2obffcfgv.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gt2ldkhrkzk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xailanhj.html

[R65] 查看端口占用
来源：http://dali.jlsjyb.cn/Article/details/gt2wzdhurme.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.smart0.xyz/Article/details/gt2aksmkoii.html

[R66] 定时任务
来源：http://dali.yj202588.top/Article/details/gt2xhqetemp.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gt2ceybccbc.html

[R67] 生成随机十六进制串
来源：http://dali.haohaochexian.top/Article/details/gt2feexdoyp.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gt2hjyqxpkp.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gt2renwirjg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iftuowts.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gt2rdyilduw.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gt2obzofdye.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gt2lomjrutr.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gt2uckgwxpy.html

[R71] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gt2itbyhtlf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gt2wswemsmz.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vicicpli.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2qkkruyno.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gleszmkt.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gt2kwmzsuax.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gt2euudfqqb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrhlgjtj.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gt2orogayxn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gt2wylurrlf.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gt2sbzmccvk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gt2vhsqaqlz.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufgklxfg.html

read -rp "请输入: " ans
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikgoncva.html

[R78] 交互式菜单
来源：http://dali.jianghu66.top/Article/details/gt2urtukqee.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gt2ukklmpxr.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gt2vrlnhdvb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gt2dynrazrf.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gt2ctbszniz.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gt2raeiizsc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2tpponunm.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gt2omcukhul.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfijllqx.html

[S01] C：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2aeehqyhs.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gt2cbefhyhb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gt2bpxcyqpi.html

[S02] C：变量与格式化输出
来源：http://dali.hammf.cn/Article/details/gt2jqcxuwmx.html

int a = 10; printf("%d\n", a);
来源：http://dali.sysykeji.top/Article/details/gt2bfwuhchb.html

[S03] C：读入整数
来源：http://dali.cqqwz.cn/Article/details/gt2othmmicv.html

int x; scanf("%d", &x);
来源：http://dali.vqdsnc.cn/Article/details/gt2gkqsqalx.html

[S04] C：字符串复制
来源：http://dali.xuetiantiany.cn/Article/details/gt2uxuzqaeh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2qfhznoxv.html

[S05] C：字符串长度
来源：http://dali.zhengqikj.top/Article/details/gt2dzrecdwn.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2qiuvhotb.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2btdrptse.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gt2ggkivqxk.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gt2zdvsmexe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gt2gkmwaggw.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gt2wuldomzf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gt2dgqewhla.html

[S09] C：结构体定义与初始化
来源：http://dali.zhengqikj.top/Article/details/gt2lqizmwcr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sxryk.cn/Article/details/gt2hlalzmtm.html

[S10] C：指针与解引用
来源：http://dali.yuxming.cn/Article/details/gt2gmuxtynp.html

int *p = &a;  *p = 5;
来源：http://dali.yuxming.cn/Article/details/gt2cuvmerpy.html

[S11] C：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gt2wvnbonsx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gt2nvzijawd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aibaodan.cn/Article/details/gt2zrrqqxdz.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2jtjhkeqq.html

[S12] C：写文件
来源：http://dali.daxiang520.top/Article/details/gt2zhonextv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.birdmap.top/Article/details/gt2hyqhaccg.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gt2vrrdldsg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gt2aajwehbd.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2xvvcrxie.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gt2rqxwpurc.html

[S15] C：类型转换
来源：http://dali.guannengcc.top/Article/details/gt2ftgjhmcj.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gt2leolapgm.html

[S16] C：位操作置位
来源：http://dali.mhx1999.top/Article/details/gt2yyjhijdx.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gt2gvgylome.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2kfvcjupf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dianchejie.cn/Article/details/gt2aihtdvzt.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gt2ccnuqiph.html

int main(int argc, char **argv)
来源：http://dali.zhengqikj.top/Article/details/gt2ojlslyaz.html

[S19] C：快速排序
来源：http://dali.feifeiyinyue.top/Article/details/gt2oolslzvv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gt2bcjpqafc.html

[S20] C：二分查找
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcrqvnow.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2szjszolj.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gt2ajeytxiq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cheryme.top/Article/details/gt2nthnouwc.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gt2dazscnpm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fzhhl.top/Article/details/gt2cnzfcbtc.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gt2hxhuvpua.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tianlin.xyz/Article/details/gt2nbwwqwhj.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2htzlrqly.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gt2kmzjxaqo.html

[S25] C：内存拷贝
来源：http://dali.yuanzhike.top/Article/details/gt2nhldjrsr.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrhvgczk.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gt2vazooaih.html

memset(a, 0, sizeof a);
来源：http://dali.jyoumei.cn/Article/details/gt2hzvgqwdn.html

[S27] C：定义常量
来源：http://dali.gaohongyu789.top/Article/details/gt2cqwlomjn.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2mmutckyj.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gt2buxaleum.html

static int counter = 0;
来源：http://dali.xylfe.cn/Article/details/gt2qjmydkdf.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gt2vbbzcmxv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.meibo888.top/Article/details/gt2qpweupmq.html

[S30] C：头文件保护
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xxzhdzhg.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gt2sxyglwxq.html

#define X_H
来源：http://dali.meibo888.top/Article/details/gt2sybfffyw.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gt2walaizec.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2umzvqamk.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gt2uifuktjy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gt2itqzwiep.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gt2atgjdxwc.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uvsjgzxe.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gt2idqspdjt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gt2kqdbtbmt.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gt2euceqtlz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gt2hegmqxcf.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gt2sfnbpken.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2jcexsqsd.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gt2caxlmlcr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oookoqyd.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gt2pkrbjmuo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gt2jwlgfhix.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gt2xpagfecb.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gt2wcaarshe.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gt2edazsmhi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gt2zrirruhx.html

[S40] C++：查找元素
来源：http://dali.haohaochexian.top/Article/details/gt2elamdxtf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2szwojtnk.html

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gt2thtsfeun.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhrtfsm.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gt2kfhyytxz.html

class B : public Base { public: void f() override {} };
来源：http://dali.vqdsnc.cn/Article/details/gt2nhegfbnu.html

[S43] C++：智能指针
来源：http://dali.kuanghao11.cn/Article/details/gt2cfbptwdl.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gt2iuzjoopf.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gt2njblvtgf.html

void inc(int &x) { ++x; }
来源：http://dali.hnqzz.top/Article/details/gt2zhqnoczn.html

[S45] C++：lambda
来源：http://dali.fzhhl.top/Article/details/gt2sqmrbdsq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhixingplan.top/Article/details/gt2qqqpssux.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gt2dypgqesb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.havefunace.top/Article/details/gt2jjomlbyt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2fnfnmftn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gt2ndxextip.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2frsxxxuw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gt2klwwjizc.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gt2hscabrms.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2vxcedghy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gt2oqjbsvly.html

[S50] C++：格式化数字
来源：http://dali.birdmap.top/Article/details/gt2uyjbjrel.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2ndxrhelv.html

[S51] C++：显式类型转换
来源：http://dali.zhongyouzk.top/Article/details/gt2anbvuopb.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gt2chvpfwhs.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yuobsaor.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrrgojyz.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gt2vnptffmy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhiwuduotai.top/Article/details/gt2velpwdon.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gt2vtrdjerr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.mhx1999.top/Article/details/gt2wfaksdby.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gt2gttcewvl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gt2bfkdlwla.html

[S56] C++：optional
来源：http://dali.ybcxt.top/Article/details/gt2todbjkwf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gt2xhrhaoxw.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gt2tcdvoaoh.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gt2mrsfwvbv.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnkfuznn.html


<!-- 参考信息 -->