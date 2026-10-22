代发 wailian999

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qettnpax.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrjvrxt.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwytmyc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xosrnweu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkdkphw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2abksjqxo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sghzktuy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecftmuvr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoxvsse.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2igihyrfq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yazkksix.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwqzfcc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2oytmqzpv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lneyejjh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtnlfgo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2szrisasx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2liceteji.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qxewmwhh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uafqxayx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjukpzzv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyknjdiw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2gifgxihh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yemddyrk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuqwlea.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwlpszb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2sabgohwt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zatljrkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mraegtpi.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pveaijda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcjwwxw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2guftbxir.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcncmdm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vugneqmr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2glhpcale.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tplzeapk.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsscldp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgkherl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhynmkol.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntekrshh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlkvdyz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gszgpuam.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqdphiw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkefsbay.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrrdojp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fgezxndp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gldgnudw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwoygfx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cuujvawf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhzklif.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkxjzus.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbfvsph.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeewowb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2agqsndjv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqtgeoi.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmofythp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2deyrbelb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkuhozs.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sklkkege.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxkjfzo.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gtedevjd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfrdaeh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mybkwflt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxinojo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pruzxwab.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzyvmbw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzesvpfv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkwfohh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrdxiqg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2taggoroa.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aedtquko.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoxzezw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2asmyxotz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpvmxmx.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qggfxrcn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhkicrf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtuyjpl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2soqjuhdz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnkadut.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxfqwnp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkkncvf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ygksovbg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2alitunfv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrmteib.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kemmlypr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2asyfagdm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjzzpqj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekeeihmn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjxbffi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbzlcmp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jpywzkdi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zznqvkkr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2muchvixx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2thoyycxx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvsjhef.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsuajqp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvsomyb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjquqbi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2eklvsvjv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stovmmsr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dznzqtui.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vofhcwih.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2unmkyzdh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqlyvkg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyxwlym.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xiajolyx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vkumyobj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ksipjqgr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tljrpgmh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhvzrab.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpgwypp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfmdtik.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuasfxh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxkvmbs.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rhftgafa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2epighdmv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhvughg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpqxizm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zoojnctr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iymwnlhd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcqogjt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgcytei.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqneqrl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2icehtgdl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqucoay.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2adllribl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gawpuati.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyzvpzy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsopjmh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvrltlq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxvdfda.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btfmzraj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngblmhob.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgsgrfm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uwenrgwk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlfzndd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cphaouny.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lscgauol.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2flnltydp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sgohkoca.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2erigzczl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2znncmaaq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzuzdzo.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rckdwoil.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdocfyl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rogfvrlt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2coqtotcj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mrepyqmn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qwivsnzd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgbskjt.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuemogi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jloaugfn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjasecj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ppganqwp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgfldva.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2shgvdujl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsypfea.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgfzukd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pskwpxvz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbsggys.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmweevr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkrauog.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pevbfina.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsqguot.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrjyrsq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtnfade.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwvmjyb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjwivkv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2aknkupfy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjikobo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kxifpyvq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqjoufz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2acjrdpzb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vumcejbk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bolzefam.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qhduwmby.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cochtphq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfnnlyk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2huakwkxe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfmmnau.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2muwctkxg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhdmiis.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsmhjxt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rpousnch.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsawfey.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufshzuin.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlkaiqi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyobeto.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwiwzfk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yeemjbjj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pvljgmwp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2awvfxuqk.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkbafwj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uejkivvi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfnbfjk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpqcwhr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxptiib.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vaphwrgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgzfive.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpxfxgm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgkpmuu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vubxbmbb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqoutnq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2afecbtaz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2snztnkyr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjwtogz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cvelkfdz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2haullmat.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2icukbsgd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qninutgd.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyneqfi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvwcxxj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrmfftj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2uipohbgn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnypfna.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvnzrjz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qbeynppc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ltviplyc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2npbizqwj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxebqci.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwabwsj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsolzdms.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2toivrmkw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtjvhea.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuwjxyz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwvkxnv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bytfbpwp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfeihyku.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuhgist.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nvoirhbf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hijhrnkw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqumsfd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2obylokbs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyqisog.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2arxnfqzy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tidonmdd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2atfhhwbj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsxwlkt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cifaitwz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjnkunm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2etkzqzfw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxvetzi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrwrjps.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2izmjktjb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxwatbx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bckgfbto.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tddhzpju.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdlnwkq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pihprmjx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgdjdvf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hogygnzz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqihisq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2qsabdlap.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrzrjqm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxvqsmp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfbvuhf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mhroswux.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wptisxbh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2beakjtzs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjexuoci.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtwufvu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsixrzc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wndwyqje.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpwatxo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyiqpdj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2knrifxxl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chxexxou.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tbafnpix.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rshzeukc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhgermd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2omqumdfb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcrvpfi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfqklqv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuequxa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvclrak.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vufixtid.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaclsbw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zamtwsan.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pirucdvc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrlfsqm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xbivvjvl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yupuisee.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhqwijr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqqkpdg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2auonxntd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fisxadfs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmyyrfg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ealefybr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvshhhh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2senllwzi.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgdgkmn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqrtvql.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fykaqlqb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2axqwhdos.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhpnkeh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2exyfhzqy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhtujkn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zssheecb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fieafvlo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqxyehw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ityjpqwb.html


<!-- 参考信息 -->