代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sorvpfvs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsttsjon.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxxwjjg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owmttzrv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jlahivij.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mazgttem.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoewpwt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpkljcw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtdizmd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmkxqhd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlaxuoaq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkjjank.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfofwkpa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkecoyk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrhanco.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2czviyrxy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gtukhcmf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2belpadoy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzahbbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lofnkvlx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxbzbpq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfpmvag.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2whibbsto.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yirmypvx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoqxmcn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbfkdwl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2akirxtzb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpofxml.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jcavfabj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjksduzi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdfcwbn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvpxcbu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdkrnly.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzmjwfw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzumqedn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twwliisc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uayxgeee.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oaytyfzv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgolgyq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2katsqjoo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeyaxtv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uldliocb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2csjoajzn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wecqrvwr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkrsqvw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yynmychu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2juqfxlue.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxjzesn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2sddtogjv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2moblqmtk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvcdydk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vymazyov.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mezazzbq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qfetymgd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dffophrj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2prkjlwda.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2blnhvcjl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mamazpfp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2agjtonrr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2grscdvbr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbstllen.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdpjbpm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyvqwlq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2npyofwqn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hokpyoim.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlarbkca.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2folnwoum.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtyqoax.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgosmzpc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfpogcd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjztofln.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkvxqez.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ktydghgq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2edixkuir.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxvseen.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wapmjctu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2drwxvtzt.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2slxmaceh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhlwsyw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsiazcl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvfonns.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bufnxkmd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2apriuuqa.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjzasrm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2haxprzdv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rndfncsn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xugyqalz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkikfmy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lscspjrs.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2diavyaxk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrzsryw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpdylsu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xovbqqcu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2yoseickl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqdwunk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoiiuxm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtmfbur.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpllwgk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2abrevvwd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2idsiabed.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaonwdy.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2donaduqp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmaueco.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xigtxatt.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wayfnftm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzxbrjr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2boagklgw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyugymm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tfllaeft.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxgwtvj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qhotwaej.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zniyccxr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bchqkpak.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2urebgkch.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsrsajr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrthomw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2waklsqvj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoirjqk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2svzgvtfh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpyyoca.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lrosckbt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2liulaftw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xzokbeiw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lctzeord.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjuecso.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2izsijxgy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2siimbxhz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvbbyom.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtdsvzy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkxsyvf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gbswigtd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yiibuurg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hiimywvr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahinsbas.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aflrrgnu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dqszmjar.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kafaybny.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbgpvdp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvibrmy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlxgvcz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2coyladre.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2meebisqj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjurhkt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fbutwybk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2eawdgwkj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnlzcls.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pspbvcwx.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mccvzool.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2svzuijtk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpphyfe.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dflallpn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zxogvorw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2oetzmmaa.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvsdxsr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykesnpcj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wigxkcen.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yfivcseg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zodmahys.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpbigzm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiiduot.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mycxlkxh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjmzcla.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2shtfipqw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtbbibw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2shwnzfat.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvjzsov.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgqenrt.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyajccx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2aklxwqmu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeipyxh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2povvbedx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2znptobnp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ietoarjf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkjkdnc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tonqdfcw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtraayq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zanurghq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhgupws.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2eutqffkt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsuyluw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mqaidwxl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcyaxmf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnroaie.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzwzcjt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pnslgbrc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gksewedd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwfdkox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjojbqf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dasfqcys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfzodpb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdornix.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cjixvqiu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxofrkda.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjhxqgw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2urpljqer.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfhzszi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvezutjd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpcgdeu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hardmvbf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yljxgkhj.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nihyyatg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tfiecsoc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gdajwhae.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhptqos.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnlxcrf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjmjmpp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsxlusa.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcrimcd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2eimfnfgb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsxwuud.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdldceg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqbuptm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhsxegd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvfukif.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyinxpno.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cowkpjlo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gifqcozv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2evbvjfft.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdokaxz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbppkko.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sonlviqv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aidryvjz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vohiilkb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kzldtgrg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdikxwbb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fskeyysz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tixeqgny.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ormwgufq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfcxbaw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpfyxcd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdensau.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nflwttff.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2okssycyz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dtflqmrs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkskcle.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rhidcaop.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkejuemm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnnrntm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2txtsgtkf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2luemzrqx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2eehqsbjc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2obaggbde.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkatlng.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ajikxmhn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiulorb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzwbcme.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2afisldux.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaifnmj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyljvloh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfubksz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsatfbnp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lesnhost.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2znyzaxck.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqcejki.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnlksvq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qymyyuso.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbywytx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlfdnol.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvmvrys.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hnammlve.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnmyytg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yagnjsce.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvmybiy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itgxgbsm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ckampszq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lryytzdf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2opkzloyx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2csxxweaf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2omxmoeyo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpxtdoy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bszpjike.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jvblthpz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sppaekck.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwbnyfp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkoznpg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbtkmlf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qftfthzo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zaveyxug.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uydajpxd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjvyoed.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nedtnabe.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkdqkrr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ehamfjrp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btcjtwyi.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjxqxcq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2izmrlnfj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uwguxwco.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iokyjsjb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlgtmve.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtdlgid.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dldwglma.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2odprzysv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjuzgnz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2giuxtgqu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsybraj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnhnwqw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlitrmb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdybvsx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkvlfto.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvsketr.html


<!-- 参考信息 -->