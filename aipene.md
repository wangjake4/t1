代发 wailian999

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vczezrne.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2keqeutjp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2msoazppa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2iiffwzzx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsgptux.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrutrrh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtlbnft.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2drmsbrbv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmfynzo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhulwxms.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqyvslf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dptmokmk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iosmojnn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktczejsi.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdjigue.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hatlnojq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ousjcghl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmgykfn.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tftynudt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2whrzhlhy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqiazgl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmzpcfi.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcadquza.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyecoaxw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhwzpca.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkbivyn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rycwpzca.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnqzhru.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkkrxdp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbenurz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbfngty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqigygmf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2joqakfos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvwpdce.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjdffkc.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvxmsls.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mavfysoz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmjdjiy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nodztvhi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcmokrh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kszajhcz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqccsls.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvwngye.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2asgiqcjz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nycmacxh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xgssevwt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khbvwkav.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uscispsh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwwvakk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dhiodgjo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ribgtapa.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2radbodso.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgeiaxc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sahmbxkg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrurdom.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuqbdan.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgwicke.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqocqujt.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlygskko.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2isdsdhsm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpfkuxx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtbleqm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlxujow.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfmnndx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkfotuw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjxkper.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqwfubc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhrnllk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnapdrc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjemjcn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgskijk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqldwfru.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oymyxyrj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2herzfmvl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qcojszir.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2reulboqy.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2prvaztwa.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rucltbjj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewehjjna.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gywdplit.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2igundhtn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kylvfdql.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lclootjw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jomwemex.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tdglwhsv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeelmgc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2crcbykol.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkdxogf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnutnlgp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcmqrta.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcozbeac.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ddijcgms.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dighjxat.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfwpckq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2suprplzu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qseedavo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgkuckh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ryutadlh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pijwhtju.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2drzwlrdf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aygfplqz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2siyfytdh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtogfap.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jefdiver.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnpaddb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdzoukz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtncfuw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvcfnbi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xasmknoy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbviffr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqjybal.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vzezfzuy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tngpfucc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqsgsls.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgmzfht.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2aprgfecy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jrssflzy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcxojiv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxhwzrm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2otogoiim.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmlzedn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wqojfbkl.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2djsvyjqy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2derhobde.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vapcsljl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nttzemlt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wzffdddi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2buzvknsq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xevbpwwe.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwsndfx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmirpki.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wgddelbu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzyzrtp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bplxbils.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbzdozs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pttmeryz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjynzes.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zemrtbdj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvmhsxs.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhwojdd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeawzzr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcqtsaf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbpfbyt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wqagkczv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cndtdozh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjssiqb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fndryxzo.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvvlowm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2iztdrzyz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjnojkh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dqowumfy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhtcaut.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dplufryc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xanhkton.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qvaxjcld.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ntejzjuz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqqteja.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2czkysyzd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlpeksl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgipoqn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzxinsb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkaglxh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfukqjk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kutieqxg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzjwbxl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbwetle.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jagibkpq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdncprt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ltacwduy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkdplgd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pebhjdlo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pysdzmkv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhagxal.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jjetqepl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwrcqfm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbplmjq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzdxrcm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgnekpz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2olaiowtq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vcviuvah.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2csjfdqye.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnejwsw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nezxycrb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aknbifqb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2smbxmalw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnjukhr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkvdtcv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tudobrzl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlammyo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjifnqug.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2frpvxvmb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeuvusj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2polnqbyr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tixniyuk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2okbbnqxz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcxsuuj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxhofpc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rrblzlam.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvgelrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdoxopj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pnksuwct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vimkpojt.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zwudrtly.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvftits.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuaaykg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuuhwuj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uovzesit.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrjgryo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2brlkpmit.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mabzahrm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eszuswrm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uokpdska.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfesbbk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgiruus.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyuwqoz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhdrckj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsnvupq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2imaymoqj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2opppwwes.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhbergm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qentmmpk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpkezlq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uszwswym.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqheqqj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqongnt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkozwdwt.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjokufhc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmpeuhk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bocbyxuk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhhmnsq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvujxlq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zatpizrg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqfjsfc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hongulxw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2znqjfuuy.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uolemtop.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxxzlsf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqqesdv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhloyylf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2znisfcqr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2skjofwin.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tnetznsl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxnfoqm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvcfqys.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2npeijgfm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqtanjg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zswmzamq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2orvwnkmh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fllrntqu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjohzcy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqaxtbc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2opoksghp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dahgrilj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aycukniy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvacxqf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvondhc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyirgufp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbouuea.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkcuajd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkhmgmc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2chuwuzhp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfubrmw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rljtzvrv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cztyphag.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2paknjrqu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ymavgvvs.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjfvrea.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sgikwvov.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2okkcztma.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wddwzhug.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kdylcvrm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2awwognue.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwvlsvd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyyshnt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiaspch.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jllkvkan.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2krkormrm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xncwbbbz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2uthzzfof.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cslacpir.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmofxec.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqswtxn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2leekpfnd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2clqooahg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2essamezx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfgxuaa.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2veipmcsw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxonzms.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuuzxfh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcfebjx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzctnqry.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuqukmw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2crtvvsgy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqhlcxy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2iiseawbu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuaqfrq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zhivurpr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhsycak.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rymgrhkr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcczrwhz.html


<!-- 参考信息 -->