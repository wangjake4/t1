代发 wailian999

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbhbjtb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfdqbdp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzbpqww.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbypxab.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2knxocmtw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzppxbsx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mdobniiy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2onzhelgp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqyqolj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmerkab.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrskjuz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyigzidh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiftinb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2deenrgpu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwzojvl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwuskfk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uakzmftw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbpzica.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2optkcrox.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrqrzae.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlhburp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbjruzq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhxdroz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbrjuew.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtouhxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zruoqyca.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qrncmxyj.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ppksguoe.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ygupwllo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qygzbkcw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvnynig.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2scobndxv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2parsgdzb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfcshwg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2knbsvnge.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfpoulb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aizyxnzi.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2plkajqhl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wizygncd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usdybher.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ongmztan.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rrejubrz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuxxdwk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjjtunb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bvudsckw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vskecqwk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkonoxf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaashde.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgjfqqm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zubfbwxj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfmpjmz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtstemy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kandyjpz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2toytfvot.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqypomu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcwccex.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lmebbttr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbjbbjm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kidvkstk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqjdhby.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gxibgkbj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2afpaznyh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2arjornwl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wapompmo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvgztbp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2poimxjjr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwpesfr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtawnpe.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2diomndzz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdgvmty.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eemmmgow.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ragvshal.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnybnft.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pehktjbp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhrqxrt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiyriio.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jqohpjgv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zdglzpdf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umagqyhn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnmnjtb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbjahbm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mjssmgjo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnviwpdd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwuhsjv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmhfjnd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gknjedni.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuolguh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvjjhwz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyfktdq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tejepxmb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2eicepgwj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqugbgt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoveepdb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjoefjn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sreprkor.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2anvunsgh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtscblk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2prfjewiq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2upkysdkc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpdigmo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zuikqjxz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxjelmd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hsceiuzw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pkszrotr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2trxihlij.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmcorse.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2drxspool.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2droyxdyw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jogrdznk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhcclmg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxfhqyn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zonczzxm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2opdnlivy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2enghgffh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2itpmgbvn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdgrxwd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwescfx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2judafyqy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdivyuh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2agsoqjni.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxepvwv.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnbqgjy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvvxqki.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfmsldz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkbgtry.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2onqwcqiw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2izozxdjt.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjoqpse.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxhojfn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaodfsv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2usvrpydi.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2humsynhr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcwijtr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhzroud.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpgwgjd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jivkquiw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzxoyxf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtapppk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvpuyvg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qekvesar.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmgolav.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ziitffko.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuihkjj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sehihqqj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyzqmps.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqxupjq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrzujqi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2onvmtvjg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jszldioq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnqxudb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjztbvh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpdehtb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaxmodz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lewuapnb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cejnvdsp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqlfzlx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2avndevls.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwjhcfv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fseoizhh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdkruck.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ijylvtjq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzfbhpi.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2squezith.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qegmeiqn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pupwalzp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fupfirlz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtjpgsz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ivokjlof.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjpjphx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvjzwrr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xcapytnf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pgetlahd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2roajkaof.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqqvinf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyydjnw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgkvaed.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwxiaki.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kpccgyuy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhwgubb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2acnreukb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2olrazqnc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxuzjve.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkhvrgm.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2crwaegww.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpyudqn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoqcwkl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrjunho.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qidodiml.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqvmror.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbmoiik.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjksbpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chfcuhia.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjnoewp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrugkgy.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zabsdogp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rxayblrv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btljzeub.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gaadgbgq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mllhcyyi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2verfibdo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzulqmae.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrltmgg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqoxjuc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2whkhxvmc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xftrdywi.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwmrlsd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxyzaxi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbkxkyz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2psaoybqj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rviwykue.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2uicwwxkd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sngiyqoi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2padfzwiz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2peexozqz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2spxxphrl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjskznp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxdyzqq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqzclgr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfkbmkc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhafpxj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhdtywt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmalwos.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2onqfbkof.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2miqfymld.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ngflkhvz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuoyovk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuzoifx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2drawksns.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2brsuxjsu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dzewgcnc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2urtwvfzt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiusoog.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueakwzpm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrnqkyn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxipfehj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2loxwbiim.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jafxxalo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbtogkn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxewtzdb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvgecpq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmkfomu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoccner.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpgrjsj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gztqkovv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdraeiw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dglzekun.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyrixsf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiikvtm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwokmjgy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuwdgde.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aavblcio.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oymlyabq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsjghsa.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsiwzsw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaoucsc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jicdhhde.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlfimuv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2heplllcs.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuvqgim.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sluosyfi.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2lncujpxg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djxbhhrm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2okdwlhbn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nthuswwu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2aeopkxqh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfkkjsl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dihjlbey.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qthucjai.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2oixqswbr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxycuwke.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxzxgyu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2exivdyba.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yorlmhhp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssneirpl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuazscl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2loxqxirg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmnlmlh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2oledrqaf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rctbzvbc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vecpttpq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kavrafjl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2undsjoxk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhbluqu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwprxam.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtzlsgy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2eofwbbtl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yegwumip.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuzwkgh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2asmyfgfl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jorcvued.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2psnguiaf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjrsfzq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnqiviu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oinunomk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjosnrs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbupzzcn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiomkew.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoujjux.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2phwxzsxg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfbitzy.html


<!-- 参考信息 -->