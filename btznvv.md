代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtpxqps.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2islqxqop.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zowlveff.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjviyjr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkzberc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2csilvsib.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2noefsiqk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2muqdqqff.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rekuswfo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuocmac.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xffunivz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2spngonud.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nisbvzdm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmafuqyr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2awxmzvnp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2upiqseqs.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2crnwbvwy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2dfggjzll.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2przfnfdm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfxzodj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxraqha.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2evstiyrn.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tdowfvnz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vegxbocn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2momjtmdh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jljzlqah.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdjvngs.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxxcdre.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmanmsge.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiwnvql.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgyaagl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2umbkvngo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2agcwofas.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pynwdqxi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hsauyqtd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwmungs.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmhvzdy.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqssznf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrabxkj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fusahrux.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2specmhbs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtnmisj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwxjtvt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbqcpsu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mpftevwl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcbhejv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2unbedjtm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2aufvmajw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxnowwi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yapybqjh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzxjnmf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnefiev.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsuuian.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeybsen.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sncharcn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oalyehbc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2woyymfvk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2htxrjlje.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaznxxs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrsgkpa.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgtisda.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcilucr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2iedirlgk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpahlcpy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhcvkpw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tmixajjd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkgsvnm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsgslcu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoexnxbf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2heashpmp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmshqym.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnzadzv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqtsdzx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2goxzkyya.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpolipvp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbzroqm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uivzvunh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmauajx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiwgnwa.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdjvirl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hgakmssz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2eukjukun.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oalmjdia.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qowekscw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkqeoye.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vybdykst.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgwnhfw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgdcahx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rolmadec.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xctgcwzb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcnpvrs.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnaisqe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bsigwepp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vljoiazr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdduyhg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2evavczpv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cqekmiqd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqtrmpo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gglxdbil.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2goxjfyia.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfhmsza.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2epeiksqy.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2isiejnsk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmyiyrn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fioqqgld.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2skaxmwzb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iszzwtew.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lsagfzee.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cgroozhe.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnqvvqg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2quiyqgqy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbtlbme.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gczxwucy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2etcgeobp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwqxqoz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xougbupu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtyvkhm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjtkpks.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vceylfnn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rarhmgyp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbnppcf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gytcktlb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfcwqgo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uceshwyh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqlqqys.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeyxilq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqjawcu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ymupfpzt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfhqqxf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fzejnfty.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjzsbat.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyvfhdi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2itambwaj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uldrflut.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qonkvbml.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lylqhsto.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gonebfju.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlnwouu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2guhtybtl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2emcynpgo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfldabp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjnxxmn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lweviovt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kagxlzxn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbvmaak.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lfocxswg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spryktgh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvsijha.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2muiottbi.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjejeox.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwrxmes.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxeubbr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjenavlz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjadgdr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qldfpeqy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vegznxmo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjpcmvz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zknmhvyc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmtdeji.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jztvavsk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuvxzyt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzvuros.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pftgvsju.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kunnqecp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfzbaif.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qumtdldn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jkusgyvz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lnoyvjme.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pubmdiji.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bvijchiv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjkwikq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqfpkwg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiillsj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kxetuupj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpbjqxl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nshallhd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bczawaeb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pklclfrn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hplgohew.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yacfulln.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2betknunm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yaedujar.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxlpoit.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfapxro.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjhrgtm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2weyrgbwy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fffcotjx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxzfjqy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2msiythtd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrwztbl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ztivsnvm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qofzwqib.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gsajdqno.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kylthloc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gknbpyep.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fciseahr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zghlmkjn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpsnmcv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgbzsfk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzcjbvp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmtrhsz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qozlluci.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qjspzpoa.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwyqwmb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhbccap.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2arygxezp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfyxqmx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2azncthyh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmmgvjc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2prtyjynz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tudmamfa.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vaelufrj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyjgzvv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nshebwmb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsmyygd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vghfstfa.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tivkfnwc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfikhcy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wwromtfq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cbncmhrh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbavheh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2awgddtth.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2offoqfeo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sthnbzge.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfyieqc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vxufanay.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmtbjxm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaqheig.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hthhpjhv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpvziup.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lzewvhgw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxhrntm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrijxnz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nquccywx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpnapib.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnqcpvi.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rdceqjoa.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhtjnag.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlrbvba.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xwelbswr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrjlhzf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxwdobe.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxepjwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjswvghr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmtyolx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ublmhrui.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kckjivbu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2syswvopl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxsvepy.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2otnwflpp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvdtnyq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2csjmzaus.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ychgkdgu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrclcjf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tepecafu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmwsnnf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmbomdk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jpleteuz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2inzhlqfm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lyveyplo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaywjwm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bygjhmex.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lemgjbhr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoibawj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqpnpgx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzlojuj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlgtgmr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmxpkqr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2npdfbxgd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwpsziz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuoxfuh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnwniwr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2thcdwetn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zydgasnr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjmgyeh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrofzts.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2glhzkyid.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaunwss.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ndshczlh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwovree.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxnrcfs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2znlqhqvs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdkkkxi.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiqpkvr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwocycnr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jazajdvx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2icrorqwm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xarrptuf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjchzjm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yftybsps.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtubhdb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhfyylq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgbpfip.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnihhnp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2txzxfald.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ucktvpcr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxrfpgf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2usngisyn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2edcaubor.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjxbtwe.html


<!-- 参考信息 -->