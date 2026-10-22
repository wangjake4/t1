代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wivphtrl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2unkggxhu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2szoegnpp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvpfabg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjsnzhs.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbjfufx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdpuhsw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kdexzokq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyhlcaz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgvwodb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtbzhyo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xstkllrl.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlzwhkh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgltngg.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbshyau.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kutvodrn.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpfvrzp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgiepvs.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iiudhoef.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfssytrg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2scynvnzt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjawlkxo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwxnfsr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvqeppz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2duwymlzt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zahqoqeb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnrnajn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vowyckez.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayknwdwl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfzynvo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2laezrdit.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpjpzij.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdzovtv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rpitxyqt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2igmwyiek.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yejtjcsf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfsricr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrqjlsy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2poybvjcy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2egcysdcb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wwotbdxl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpwxnya.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgofbeg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcbvbbb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxtfsba.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2grtnesas.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dylpvsfk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2drqeqajv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fflrsgwa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsonoki.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcjeutf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhqhbrm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwvgysx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvgwjyr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qerqtqbv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bujbwoyu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxwtigw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvbsccm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rwungzsy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2srwgpvrw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyhxgkm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnvxthv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhxdymk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxkgrza.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgccgyx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2asecskpe.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbndgxiz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxkgxcd.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaixcgb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwttbta.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jszxkgjc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2niddeulp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pgacwhon.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rfacgmop.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlycdma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2talcfycz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtsfxve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqqnezc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pyerqrdl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfbfsev.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmbqqao.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvphfch.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzxrywk.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mduroolg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgkgslj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdddksju.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rosanfdb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2isdsbkyu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rayipcxd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbwcvry.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pplwgjhp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyfhosn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zaefkprj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxvawwy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gqheuihw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xngokluo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wcldsftm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrdyiyh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2osgtcxfg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwaqlqo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuiwhvy.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqceeghe.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqtyjpw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jadgjfib.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdimgxz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2numofify.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyyyunp.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrkezns.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbaezej.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sgitrjtb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2beumkrav.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxmtgnn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cutdfoga.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hnipekts.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmznebu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cveagfcl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoyjigw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtuolnz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dltzxrxk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnhxfax.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyceitzu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvexsye.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2czukdjzw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qtduoeix.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxinafdp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2koobxtbg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2litywlhz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qmufavzz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuvtscr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmegqluu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2corcyqex.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvgunle.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrwkabv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxusxnn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyyyljs.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2snhelhse.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2misbgjpu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2piemcssh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2srzgmdzm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dywjcweq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcsoqeo.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsjdjip.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2luoxhypu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cedhohjm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxslcyx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bvudrkdw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsimdou.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2snolvint.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuyguxx.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsgjebm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbrmsjk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2orjcvhub.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xywsvvyb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnkmvzq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbkbwhi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lrziwkqq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wghvzlmb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvtzgbi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvkovkb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwirnvm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kidyihet.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuabmdz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vgogiega.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oerzcemh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwirqlh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtossqh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2etadabzq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdstaeqb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tauzibzz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvsrefd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2okjzchaj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmwdkne.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtvamut.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2valwkocg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmslhos.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vvotojop.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zjarwdcy.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2belanalu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpcppdi.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2muifemtb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkfhkhy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxzetcv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eygtyvsy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2voyvgibl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvjjpzr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2izkadfyv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvnhxpw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cawvfmvj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqzbeec.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qevstjpt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2awswrszb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzlcgan.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqqisud.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlitwuy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hhohsxao.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ceceehpo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2aajhqjlk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyunzdl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kioouxde.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2aitjbysx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzpozjp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2shpslpvb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tprtnvee.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyfnvcp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgoucyd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhryjqrb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgrkoqq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2beztywbn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2inhasdat.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbphzbv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2prkkyvlb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2grgwutmr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ziybgunj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yblnwgin.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mkblzesv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2oslznrge.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgxhjpk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoqjzbc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2etuqtfrc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ogelyspz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnngpzz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2furoguvz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fknjopfa.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcfewwr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdungff.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2roimsefh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fqswinwg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqtnuul.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2azuqmzvk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cneojcpc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfenmhj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaweslh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qutekgen.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2okyvkcjp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpnzvga.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqjfjvw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2seasltjk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuswczv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uofoffkq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxeclxe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhknern.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xnavmfxu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lipqldry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xeohihxj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfaihqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgruhbb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhdqgto.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2csupmdka.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gminadri.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rsedkxjh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbzfutp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2silvpxal.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccindzqb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhaswbq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwzjatr.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cahkborl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwhhapt.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeyqzgr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpkikuv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbpnsce.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmridow.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeznekw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yymyajqx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwxvnck.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgyituf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2muiuzimz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2udgtznbv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kecwgxcf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vgveqxhx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdfdhdn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwunzyjb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cusctblg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfelppn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iaccmiyz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqensoqa.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2adgomzyy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsxwpqg.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zwilkogm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzralgv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2arluygvn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfxcypm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdiyiaf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2moadjlht.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jysjpwot.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfyqbev.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2liqdpsfi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzofrbh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2apykxhhx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyqilgv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxjtmcv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnztwbr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2upgwtpfy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vahvwdjc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2frnlsngw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhryxgdc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iubyydle.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2grlsynja.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tqefpgzg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvybkicj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpopfbr.html


<!-- 参考信息 -->