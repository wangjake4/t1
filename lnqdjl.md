代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2pujogehf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rbydfmkp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pryhzqsk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2kefrxizi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlbmpuy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ildzwhse.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsesbbv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdlplmn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwjyfdx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2foqmmutu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jcidrubz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lehwqpav.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhfvnit.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqifwbaq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxkkxmv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wafppsxa.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ablhteua.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyipkhjk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yoywjyuq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fokttyfg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fbioxpyx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2clkfwpdc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjweadt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvukjhvs.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2evbxhahf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxszrva.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkycpiy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtdqplv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgarbvu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2huggcpnt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsblklud.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2idrwapbv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2krdxihne.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrxcnno.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbazpbi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkasqatw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwtqdbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfwdncr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2khqnglwy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2scqijetq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxjajvw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2trttvqpt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhxjbmc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fomikprl.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qonrhgzd.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gobiwscu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcchdari.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qazqdieo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhkoqgg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhnzsii.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqhaqzj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzinmcrr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsltqyz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjjeasg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtuhnnz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxvapyz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqkvnip.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqsghnm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jjujntgu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2drtmfkgp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2swejruzn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2infdussn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2isnvsysg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwzylzd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzrzbls.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2plvghvzw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfracvb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiyujpe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfwitzx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mypbpffc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qfphkoqi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvbqaas.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfxltjg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbotyms.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bygnmnrc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwhrwhf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2frutdbss.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvbbhgw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfpunhr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqgfhhg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqbbzlx.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wteglnmi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xenpbbho.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnfbmfh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2feymbuyq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2inobiwmw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtsofcj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnegzbv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbqxxme.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsmsqyi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2brfuqvqg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcckysi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rijclbti.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjkegma.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpakbbif.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwpizbk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ncykskmb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jgijiutp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lmifdfxo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kndwngwi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2keosnfns.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2poyhxqhg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2sengtpvb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oirtzddm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaaqawhv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ikieboqi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuslletq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmygmzz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsylisl.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uhntsryx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvqekzc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqadlae.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwbotmj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlnbbdm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xobypfbd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2plesojqq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iziksbvq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2picxxiwn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gklvhcdt.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuhfegb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lblyklfu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqqquga.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuwicqv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfcmrqz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tyavflkc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ximgduvs.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2royxfivq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlopirg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2icpvtrts.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlalwrn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkufepu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qhewtflf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlmfbuz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yorcdscv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mjotgftj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvfckbk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bucuayii.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2imkzvjov.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gykafzxu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzpxnvd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyzidoq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ttynmili.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lygfnncg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjemxaf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvuhbwh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvcuokm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2htbpftng.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bennplna.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sastqosv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvozpkc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwxcetq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qcadorrr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qciptcfy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sedbwaow.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2veicprgq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2trvclony.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrxccnt.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2woujugfc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pigzkhjw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yactksrl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkezzxs.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2athfhmzm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbfplcc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcyxbrr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zedqapgf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnhobho.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfayhdr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgsfoll.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jxspeftm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2umooyspj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkvvxeu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gjujzcab.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lozdqjxa.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iioynajx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzythek.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qudxkpcg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxqrusq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tmexuxqp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2edgxgqpz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ryetounp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrpvrqo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wpatzmpz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2naksgakm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ayksbhrx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqlewqa.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdcqurx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnwyhhl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rskteqmw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnyxcwf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ibisyjwz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qptqjvph.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlpguxm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2upkxnrjv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brtdasod.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fynwcdng.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jepaxcok.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhheosx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2roezcmtg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2heespqhz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qlutyfiz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2emivrcvy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmarryv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgeogph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmunfbjl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2luvorpbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2guvbysyk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfkzgqu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2niemdhtw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qasarepo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kippmdsv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfhyjyb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkfugcm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2peyuaqvp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkvtzqz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfpoflh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2inllorhw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2szcigoox.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2snzbwebl.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2umtmhkhz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pybxoivz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbwxcuw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnbkwoz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbptkkr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zhknougr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2owgwbyuw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bujagcef.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlbiehb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbuohbi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2scigbeqc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkicuzwk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbagnajk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfatgsu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuhsaoy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxxnreq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2insmampn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnvolie.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgckiax.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2angcarcv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiuabya.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tztfvvtj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wddmdxfv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsnjvfz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsuwjwf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bskzreje.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2irycrnlf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2chvndooz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2llpxcprz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2khkfnmdv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbylbvr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yvretkvi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vltkeook.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbukuzw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqwmknb.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2keouoghi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfieamyr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlybbuw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rexwerkr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bijtgsuw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2unkovjou.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzgaclk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtodwhj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzojkfe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzweywrd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2upbyfzqv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlsklvl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mklihfgo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hffxbdzt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2niouhdik.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mspcvaam.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oahzkeep.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rvydfnzh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bcleacfn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zopmtzqg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pscqekfq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gekcpwak.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhxyhna.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqalugr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsizaaq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zzexbkzf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlphkvo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lfocrsnj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmjviru.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jenefhms.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2smlmytdn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhmgqus.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcqkapy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2svyhaoug.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqowukn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2raepfyzd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2syskicno.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcyxsiu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xllacdfe.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpapxpcb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmdfqqg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxubrxr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tumdoway.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmpbrsw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnndfnbn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyoygcp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaotcrxa.html


<!-- 参考信息 -->