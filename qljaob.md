代发 wailian999

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vpauzvzk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vysrdvdu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqsjafd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mhviahwt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnzumeg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgrieux.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxppfrh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2eixpqjeq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwwmhfx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnuzfwo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2guircyhh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbmamub.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dblswxqz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaklwwqt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdnmfuq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2abwtswur.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2sdumdndg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjozeyjf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrgyoey.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsmwiaz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qommiuyr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvslvks.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iiubgwti.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2uanjpbqf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2azveaulg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqcutyg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvkpfah.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vowyfztq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfotxfv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2iswtcgfc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnktisms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lznbetqt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2etdbzkpg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqlnkbx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2adglraxo.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbuimvq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbxoikv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrpyftr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmalhidr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2urjxeaun.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2esskqpsc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2acpkorjp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvpxfxb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2olnvbfay.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2somdqbwz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yppilnfc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wshfgnqx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbowzzn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbincvd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlrmyiw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpwglbj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiudzjp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbrxxws.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2apzjbryl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oftoahje.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qqoacnlu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wckamzua.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2udrofrbg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftebkwoz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2suoathzk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ttctaxgn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaphzro.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxnzckw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcwospu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tifnsekh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2yicbidyk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qlurzkei.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydakeili.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2njutjkck.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbaisjt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlypgmf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrcohed.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcglfex.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2agyjelya.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2znvwhwze.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvvbzki.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xeklazfh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2voqhvjsl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vesvtxxk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeozzqx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeueaac.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2axkmfixy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xznjgxfe.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnewyyu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dejiklgo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmohtlb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2efohrdsi.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqmvejw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2smoferbx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hxguryfo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpggfzia.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmsfdsx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxnnbdi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wfncecgg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsuabuj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mghmmfxh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdfsvur.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zydixulf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvgkuic.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnsmzwl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iewpxeyb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqqbunp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jivbkuyf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqtoakx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqqlepe.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fikrupqg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wtujpocr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmxoyed.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqftfci.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsnesov.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzepojk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnnraig.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rglhdxnf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqolhnz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tkegpnnn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qolzdbik.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzwqmti.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsmvjvb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xndhewnk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wllcpuyt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2levgejqn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2viotvlmv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqphder.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdmfphc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tcozpxvw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pafbxldw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bagrvits.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2epkubhek.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwlblan.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbodpws.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2epjikxxp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjraesk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrueiop.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbucrrrf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhbhxiy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvykryif.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtnmsri.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhicqzt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsmayej.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vubgkfaq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2klvftjkl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2icclylhn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyclcwf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkpgnqk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgbjygv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmptlkvs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzynwlr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbfanuq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhbfpwa.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xoclcsjg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrdlwff.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdfqoln.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsmazxv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxerihmr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmogtuy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwubgdk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeaqimb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2azdzxcle.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2erepxwps.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyactnu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jliyonlz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsprxlps.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cokunqoj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2anfnshmg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2spoaycki.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2knqvolkx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2urprxaky.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhqtoqx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqpwipx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvcqssh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2layeajro.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoqiwpn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtkemtb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cmoielsj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2npltwbzx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jncybqiq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvymfys.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2acheblne.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdmzcac.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbnbdru.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nghlscxb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2meoyhkvm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwwabbk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vziiyvxx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiizcxf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtvwkkv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nlryowvf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcfnecw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dstssmkc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxlttyl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbandps.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfjffon.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxazghu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2emvmzrit.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cfptbdlh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuirjiq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmgragc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwxdqqd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2omgbesal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyobfsd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uivkmcnd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbtbxtv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rlocesmy.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lkswsnvd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwlhgns.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmuzzte.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwgfwuv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcqluvu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eccogxmm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhakhnt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2coijsjiv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2omdsnzmh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2olzwklap.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gffhriae.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2snpsubdn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2knzwlkzx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gyniylgr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqvhwvw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuwwpit.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2chlycoxc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcfmeli.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mchihjtl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfixdzs.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcgbqlj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdbyekr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrpshme.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gutpnthb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtlmalq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2relpqcpn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmlmdtf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjgchef.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbzmwmz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fiffnowj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xfakuspa.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnbnicw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxkgrhz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgheizpx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2twkruwmb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcvqnzy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oitfziqk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziymiwvn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqkxnav.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2utgwnzby.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuyaesx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uenycsgl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kynygeia.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lppxhdvv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2btiwiqrk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2izvrmwwl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2spxuqjgh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlepwdk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pjegvfjf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2memlahxw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jpivnkbd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxnxagl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zpehvmzm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjauwkyh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2redtopvn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2slpiurnm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzoxelh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzlkinj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjpiunr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vykkggtd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2szajlija.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtfpsng.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpqzdtd.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2akqrilbj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yneznigu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2unaeehyh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keidahjd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoowago.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcexcsa.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpwmubn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqevabgm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrxjsvg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjdedzi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tagaqgei.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fetvgusr.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xclouves.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgvfijf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjizxkm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cacoofdp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqbhryv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2suwdicbs.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyiuujb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgduknx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuhbpwt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpsdnjj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvefeuj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2conrqtrx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrncyush.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tnljulyb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjkxjwe.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwphwoo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2btbobrum.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orfxzziy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qqberxea.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xayucxzb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbqpaha.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcubingn.html


<!-- 参考信息 -->