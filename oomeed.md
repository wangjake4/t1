代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnpuvqy.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2giuydetu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzcurdr.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfmbyfg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjufnubk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrlxzxl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyjsbcc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlexcaf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjodwof.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjkkyse.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rokirdkg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekekydtt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfznohf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfawcwej.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqthdxqo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2snjcghbj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epinlbvn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtofxwb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmchscak.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxnxhvm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sehgdjxy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2thuxnrbp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwyrxfz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeikonx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kjguccfw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iykmhwro.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkequtd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpqsqld.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzdswqh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kndobvyi.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyyafms.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzryucjm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmpdayz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyehrlr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rschngmr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2engfffgl.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hknaknpe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtdsajy.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaxtlxc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqecpqeh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpznmxno.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwgmnjt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfeddxm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvftuwt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtavrmor.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuoyrgs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfmjnhh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2otpihqqm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyipzilz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrwewly.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jdurcisw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrkpffe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzzkwey.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dupjknzg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2opinpdlg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xogyzvjm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvwqgpy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwowxmne.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pxifxiie.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuxpekb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmznyci.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2sqenlkfb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeotzeg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjhovor.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2flqlnkde.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkitdxn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyeemmj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmarzgr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkknbqx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpteggkt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qcndrwgi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkainxei.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2icduaszq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuefkqm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2phxgvwkb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuuefsd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwibyoo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xnackiga.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmoqbzwy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpshyyqj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aekjwxbg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnjosia.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkwgjgw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vsomylfz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmjvsml.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwqrsrz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsysqvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dficeztw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhdycjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgocdbi.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwcqkcd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pynmvgnp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxzodeq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlqtcsr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyqqbmg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdzefsd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tchhgnpr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2scuyoxab.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tswnlztk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgkvpft.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwbafxm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ouipjwbz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbwqaoj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqhsegs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiueqpq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2engvpsmo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzraiap.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kaguelij.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xbahnprj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhcjkeu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeelwld.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwcglll.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2isxbnjlv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqbenfu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlwlajz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqlglsa.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqsyuyt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cixkmtzk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2knjisxij.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxskkfe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cokqazee.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mviyfafi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2njhucgab.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mliibagd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdtrxxf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cahmnrlb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wbodwhai.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsrzbkr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2puculfks.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfuktvn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wadpflrx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fappvawk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsygiqe.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2oehbufgg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhptkepl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwabveo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcduzrd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2czgwdelf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2owidoweq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfpergj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2niktzfql.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xaautksy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuhidxv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsaihaa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eubpjewn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zasetnlu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwhmmjn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlmjskp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwzyyjh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zwodzzvt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pishtxmy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgasmbdv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jckzsrpe.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oezpzail.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlbznzg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fijyfabd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaefbtfm.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xkadsekh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ainyekde.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mptxyxzm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2knxazchq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrbbfyy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkgkrhi.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mclljhwb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcqbtdc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aruvfsek.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ounspqkq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuapids.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkovvojb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2etwclfrl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tnybyliy.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wumyjffu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxtdgmd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuvqdst.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xnblrrtw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgjlnov.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fofecqri.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gkspjcdk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsokpux.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdwvzoh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2shmtlozv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfumuaw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zajesscu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vepruzjb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxfujja.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrbzomv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfaikyk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfgxjgd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtkehgj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qavjbmfj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2movnqwll.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2myxubery.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoadlqf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrmipwg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfldxgf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdpyyrx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2olppsupu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxduayq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlfjcmj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zlalceot.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2okrzqngv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmmdfad.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzaxbey.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnldflw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2usuhbdpt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zzswzrix.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhcisyz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyagjje.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2poxsczuh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmzissv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ubckekhc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbqaufo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuccsji.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2raodawmp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrtrjci.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2avncezlb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zreqfene.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oldqrtna.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2damtkeii.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmkpbki.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wumqbdyf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fxexzkfn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtnutaw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2burdmmmr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2eafmyuqh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvmxkfn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wcseftag.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lajiduoe.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wemdrzke.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqmohyx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkyutkz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmgqkbd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjwqhne.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yegrxjbt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2doxmnbca.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qywmjasj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2omiftwoo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zywboqdw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aaquifrv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2foaokhgh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qedertce.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrxhcnh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2beayskln.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hphdhhmj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2blostnxf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dziqsjyy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mygwhlcl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeumjct.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2acuyxidy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xprwwigz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2stfnkybh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ojssuhtc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwptdgk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcfgmlx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nkswqkmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqomceje.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qukzxleb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdeanpp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eiswmfpk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2icmyspuk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfllifjv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2okjlvoub.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2izgvnyze.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqbufnd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlocwmr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxgwqtn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiahhug.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhezavf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsjnxkg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mqggfuxr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjrafxb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjgwtjr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gryqmpnm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xwourpme.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2udujberf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2otegnkjm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnxiadu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqxlypp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2prqnxpax.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvtzfif.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtziwaiz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvbcvgs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtghuqo.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbtegna.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoesdly.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvpeezr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrbrpjf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyeqyuf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbvapxa.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqtrohn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vlspotue.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfjcgqe.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xppnwasr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpvnjdk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwjzojo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2blkegopu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2blwnvabn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvfasar.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bprynxqu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhwxvro.html


<!-- 参考信息 -->