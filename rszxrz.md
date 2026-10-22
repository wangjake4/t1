代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzemvjv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxneudfl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzhbytq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xclxbbnt.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2clbzqtna.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2sndxitzl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2brfrhjqf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2llihosru.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kiegkekw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnfmsin.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vanpedxk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbxeqlz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tmllnzwy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsntayg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuodupt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsttjnj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ldochjmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hadzqltq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dgalopgm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ephjpbhm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fredsjwb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gulxhvwl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qutwsryd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbssxgs.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzvfevk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hchjslqw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkddjprl.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxgyyhi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rloqzcrb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iezekpop.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chsnihcu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yautamkm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgtyirx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrnlqdm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2btmalxra.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2njsvqund.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2trynhhhy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wxchilof.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2frnbvjvt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2oiohpsdb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rkubdfhb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2obqdyqkc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2smexnvbv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lomzgvab.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfhitas.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqnpdyf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzajhre.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rnumppma.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gpduppuq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2oywbsxow.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dgeebmkq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhlozlf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lowdnarb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiiqdlp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hucvsdpn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kttraxhb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2viieaxlf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ltacevhl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbzupaz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvvndgf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnufltdt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqobmci.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2puaioudh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ksynxurx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zarduttd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bslmurzz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvutqyoc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtlbgld.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwfqhbq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiclwss.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avpavaok.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkzfrrj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjirkiae.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pvblyklo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2atnfmtux.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qwewdndu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kohqjyou.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gimnkaqu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2drycoima.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gifygqsg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwqnqsu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2asmbcxog.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nslvqvtm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfvioxw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzugkhti.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhittok.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvueetqs.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhtfbty.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhkgjig.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2slnepqwj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2domgikpy.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2icrszyyl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfnvpme.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oyikvzyc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzekgbs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2waucdrve.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2btscfmop.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjmnlyl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hznszgtb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2igljtntm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjliqxq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2paxdeufq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwrtvpv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtggfeq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyftqlr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpgieqe.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfhzmic.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wazlarjp.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhgddgp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gibkpagk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2trxiycrj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdzjvhc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ramhbccy.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2abnxbvrd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dsketnpb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lezmebkp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbtzrxw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnckwgj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2illdusqx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbwpkys.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cylbctzn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqdguga.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pglkiury.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpnbgip.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vcivqhpu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2euojcdjj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2novlgvvw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkaxrba.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpzopkf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2osesswfd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2boczurft.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2nzijsght.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2sojkspvk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbqmads.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgnksga.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrfylgx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqwmvva.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pigkhxrl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2emvrbvog.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2txfagkfr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlbmrul.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ipperbur.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgzhfck.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjruetq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqybsmu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqndsfnu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2veguppur.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zlexivps.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdaaetd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbomfos.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcipxvb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tekydrhl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkuhgyr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xfykfrgk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzbwdcn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfpzlmd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlzgpge.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2sparjtjh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxazbjm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmsezgo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tnamnbzp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtapzyk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ofovzika.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dlathbeg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmpiaks.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qonhnldp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnpcljf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxhfktn.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2erkqfmfg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbyytxn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vpniholh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxjivyi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnkvuoj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qeivlgyu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnncofo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpvpjyl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wecicyqf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2eusorbrv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fikdgpcd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2nttixcpj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vjllybbh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2sisntziw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnlouwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqywwca.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwujqxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzxxrwv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfbvlhd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2amjextfg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtzaeqe.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsoapcw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbyobjm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxhqeut.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxkqvgb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwdrvpc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnotwmn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfyteeh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqlwpxg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xegzkjei.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbxcust.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rynjodpt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhesyyr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kipeqybv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lppasxws.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bsygqmbj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyaibqx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2yunsvydo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdkfcan.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhauhhwq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfehqzy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aciqnmcx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cveflbqs.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrhbkxb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciovrbkj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnhervf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zehutsdk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2urpboazy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xgknjmkb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cprxnmdb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2buwmayjq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yqigoxkv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxaeoxr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hawawwyb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcadvqr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwvxjof.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dutkvwfl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2adfwkqne.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hguolehc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxpbaml.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eomtnspu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrfcwne.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrgxyub.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uunlxhwj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpluaowm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekihsatq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2weukcxbz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjcegyo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2triwqfhm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkvxanb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxcnxct.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gomvjmza.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cojyxshz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bghyiqvo.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbakynx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyhoxhi.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgflcutq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2supbotfm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbtbqmx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxlnhrv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hmttewoj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhdgwpx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2voteonkh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjtrigj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdrhigt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wakmjwne.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xqntrycr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2siseswfk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfypdvi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqmdzhn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqvljpv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2talkwxml.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpvfwwe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhterjlx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoatzir.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxylpfex.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgtcyyp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbokiuue.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2smzdxawn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zalpijve.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xusxfimz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhsqdab.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcavepn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hircjxmv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jteiqvcg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsbupcy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxdtlsw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdogcfr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uxstzbyj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rczefaud.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvyayfh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqttjqqh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ayldtndj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyueacp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzzqexj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmebupb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uffdekgw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdetdma.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eiugvioq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnwdewx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsyfscr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hozppxxe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2aevsdwyt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoemwtv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcptpwkc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mjndmirw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kamkxxwv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjvvjaa.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpshnmcd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2anzxpuri.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqxuhvu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cupnowgv.html


<!-- 参考信息 -->