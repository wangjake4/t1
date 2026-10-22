代发 wailian999

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpoixdz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yledjmey.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fywnosdf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjdrupe.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2spypqhek.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qorutoix.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsusnrv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeappek.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbqyknx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwvdtbw.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vddwzyuf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjklasef.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvavuwh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2djxeguca.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcxmyqp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mybcbmce.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jueaipgq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2sodqblrx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdzlaai.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdoxvdi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxygyhg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwgxjvo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omrcdaau.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rwagckkj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2syebvgvl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2omfezwtt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gduhrvow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pupmubgv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxnpwiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvyultw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2naxrmxde.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2eosdpjtj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2geonckpg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdakucu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbqgsap.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhgwrho.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2swmipnab.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgspelyl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mutzrplx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuftvyg.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcdesra.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vxknkstf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmlubma.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fibjnnsj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmtofbf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzvyuob.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qhamclbx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyidaob.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kupnuhow.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpdqhsy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zspxofcw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfpuprk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmuzmki.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrvbpit.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdszthj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwtacjo.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfsjxoz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oduajlzr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ghozqqfb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhkatqm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqqiexx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmemtri.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wkltseaq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atlzyuef.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2apymiznv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhppnuih.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lgscvack.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2eymjtaci.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpgofml.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjvjgfh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjidvlg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjbkpvm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvwtgid.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2horiiutl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfiuolq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oatpolcp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpcyojb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hapllpmx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ainjlmcs.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnkrnop.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cdweufev.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wvczbuqi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oopnxilu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwourbd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqdwzpa.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdwlqig.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxukoeu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hsloezmi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzegmopy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nupnmmdt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2unhypizg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lowlybql.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xoomcrrb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjtycux.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsjsydb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2upthwuav.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qszrrxgc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjvenvf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdjlhak.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyfigsk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nglmbyva.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpfdlfu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mahvkbrp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdnpzcj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbptwqnq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfbafkm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkclkys.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2itudrjbj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfwbzma.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2pgicpngy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zsspbozv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbctbpa.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rbugsymd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtyoacd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaqnaoe.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqxsxoq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfzojnt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vudisnln.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uosahbnp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcobubzs.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkgikbh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wldaywvo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvucymy.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2imukrquo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsnsrxf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxkofqk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xiidyfri.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pasxupkw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pylvkdjl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgceuyo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgxyuea.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2knrdqhgt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wvajmwtk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oouxnhci.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zxavechq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdlvaow.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jccttjou.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2eiewzmmx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qazejbfq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbbedca.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cehyvkhs.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgehzhyf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxfhqki.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dafpskpv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlhkfwd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfswkvt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhmvknr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgkadkx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhvjfys.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfneozd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcahpdx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfszugb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cvagyhdl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlrtysv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfbwulq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyaskrf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cueugdlb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krjlazzb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvhppvs.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mbradfcm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2denyweow.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2evjrasmy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpchfwsg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pcffycyp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xppqktkk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2winbilaj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fcthvevr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsvjuol.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2omkhccda.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zoikqiqm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sthglusy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2njijutgt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2glzesrvy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2opkchqgd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsknoer.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jciannea.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2keiusxzm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qiafhaqa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2usiguvye.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvgtssy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmueixy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqhhpkl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2atxactro.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qixsonif.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkhnmpy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzgrkjs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hmemeimv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dubkvulv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qacdivle.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfhuhzn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2blflsxvo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dwggsyoc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdjxtsz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnwyloy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ssntlqkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtvoasj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ltftqbpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlnlhsu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gorgzpbo.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzgpfto.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpacgpx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvtakos.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lodhiyay.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lylcoduh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsqhivn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xdafnnkg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2odjslsll.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2usitlnpx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsinocte.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtipfjm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ousypkcl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hajgxhgc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsbqnyo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2udpalprq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyhhxlk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2stsgcgdk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xugnaxbn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2elflqqiu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnipvgf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrdzuzz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dntwbnek.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucijdkvo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2woqibfny.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kltuziwe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuamlvt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vegerwkm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cexkgpfj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdlpcfe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ndavunym.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ggywfrhn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgqkibt.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhygfup.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoplqtoj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgkapeb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2crwufzvh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpjbytp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vycnygwk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bihlirog.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2illqhsal.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2osmfmzqb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lihgakpd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kytcsztm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzcrsez.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqvzaeb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyhvjwv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qncqxdpx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yumsryxf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjxdqkl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zysbxgnx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqhumdp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlapnms.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpwhgae.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2elrglzxz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgkxgyg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwwbfsn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmbbrwf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2icvhaixn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkrdcro.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnswafnk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfmctyp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iryhxxge.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kmciultg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxuvpye.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uywvnvpn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dechixdp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdptheu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjihmie.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2maxolrmr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2uaefrofy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ombcduwz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuwdaus.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsorowom.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkzpbhm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoixrpd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wllyjlhr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xciehisq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uaomhkui.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhentle.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aartqwga.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbwcdkm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmmrnqf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiimnqk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bswicozr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2isyswhkv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgxwclm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpvrget.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmaargu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqkcaac.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2enubioyp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2geqoxpne.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzipczn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2netvqpyo.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqyowub.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qefvrurq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrxlhyl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiloveqn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bztetzeb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twtfnhho.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyzanwl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlskojxv.html


<!-- 参考信息 -->