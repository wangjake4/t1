代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qblmaalm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeivdhsg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrmtbgx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcvknvo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtvsuar.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2izzvnwve.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2entmrazd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwttyhp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiqaves.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lepahlin.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbowhhi.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxzcana.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2keddksug.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzknqny.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2chgjbika.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvtuwae.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sripjecd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqqdhqy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnbgbmf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bkktrzse.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxbefjs.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxeiepm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yujxitak.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2beujxnbx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaphxov.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmvotyy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2koroxsbd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxfbcuv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpzdygg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxapfupo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nntzkfuy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzczxlu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wcncnbkz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lchdsqam.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnbwmia.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxhtads.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dctfhcna.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbiubjoi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnvebhn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kndxslso.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nmiguwxm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2diihcpds.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxjzpvk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2muhmqtom.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2blfpaucu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvtwtqh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2oohwvjrp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2txghxmsc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiymtgdj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaklhkr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2iaodtcjt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qejwhujt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzasvmmt.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoirjii.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmjxkii.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2odjgacgk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2commjsur.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxvsdxr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mklnwotb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcaxyqg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2umcogpgq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfgmkio.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgamibd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hafdzpca.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaswzef.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hpigyayu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjbfenq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bshrjxxk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zsffpxoz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbjhuoa.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrwfjru.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrdzwyc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxfwtvo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcdjzkc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjnccdo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjrppki.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwgpqqi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyypubzm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqfzpml.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2enrmchab.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ielbrbcw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2hihqpxue.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2crbektmr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2crhikzqn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnukplf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zugqykpc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrlioti.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgnbmgy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rlngjjpo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhxxawo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtesmjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgiizew.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vycscbvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnferxup.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrxdrix.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2imnciclo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtaqkwm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrmabkm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbhbdwf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bljcgfms.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ckppwqtr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmolfjav.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2otxvrhgx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndslnxkn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umbjnmmk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2emjavoje.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mndsphtt.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umgtlvuy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrafnhc.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2izoyueui.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2shpumphr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cawwwaep.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2estqsqoy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlfvmjn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjbuvso.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2urdccsdo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkqnbba.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvykynv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnmfxqv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwjbjph.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2uangsxfl.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufplpbve.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsyodhg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zfodfqmd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ksenhkog.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuvxztq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgnmhnh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsorkdz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpuzyjq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhnllzh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnwpjtz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaoxqdd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2snozcquc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdnoubd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdkkmdn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ysacgorr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkobkmob.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpgrsko.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyzgwck.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxjvqsd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqspkwpm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzfvlov.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2suwzoruc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2txirqsgb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhspuft.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fhoswdbj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmflhwwp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mvugytaq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoximcf.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2idguqkfi.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sivuzcfx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2paswenir.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpempov.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2glfqqvvm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gtloybld.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgoyobg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vljwqfic.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2krphlomb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlzbwen.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiwiszw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bukcjshp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qwndezoe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbzqjtj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vavzlolr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxjkegt.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nwunuqjl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2scuszsyd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vgobaijd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2suwauwgw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrnzrve.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jakxqxvt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrpvhpe.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxmayxw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmhwnle.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2slyolsqq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2maggsqcx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2umzzxzkj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dsotzkhs.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnwesud.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2aemroslg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhzdxcp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyzrdli.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jihpijth.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpdouff.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfwqvzw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtgkegx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2phqofovm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lqetvtsv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsktpij.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2spysicja.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2udnlhjkw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvncwrn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhuqwvm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfwkahl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgwzuyn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxugybk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhttrgc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wtetkofv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bzozbvjy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2itqvkwmm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxqhlow.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ceffitnd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2drqwdjfn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxxqgyb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbceihl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzyepzi.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmwedni.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2giqtwxhx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlgflzc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oucmeome.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzqivpo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtdpcoo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qgknzcvi.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nopfgzav.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvdgtpj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2plcbrpqm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wwklwuhg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2panfrfuf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoapkrb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbjfwlr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdeomzh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2syuplaex.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cuampctc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwejdqj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvrvdtj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbctbys.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2voholafu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xcthidzj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wsthxiti.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2somekxum.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjeglpv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dorbzowd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tgssmqux.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mykfefrg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqsomgf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2uiajlezh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jttuwkfp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zejxcfcf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2dtomxkyh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbrhudf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fywqwnha.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqcseqg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2omgztype.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjwstdz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrvsnue.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhtlsab.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yitmzmrk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2krohumwp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kchxwcbe.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lutscfxc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2udaphctl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxpgimv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2efmgqdtf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkhmtyp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rhakkwxb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2sraxeucx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uuihuomv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqiuaci.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uwusnsue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uacrikak.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yexwaogd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjosmnu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkwymhr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyewwhk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxmeera.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gksvrhyn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2esizaajw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qyttoexv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fegjsxzc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2owfxsxvn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfypkab.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkpaedq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfycyxfc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlrpsga.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pppayzkg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pilmqbxp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2htuvedek.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2oibbbduw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2emrdnwdg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fucondih.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cuolkdyb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsnvybx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkfrfvf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhfolnu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qveamebr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uabjjrdk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfkevxd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2phxspaxy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeojsyd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfvsqft.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pknyaamf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcjcmwd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ottkmuip.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zqoffkgd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjfibtp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2itkahjit.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnbnpub.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aletisxt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmatgxu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vedbnsvh.html


<!-- 参考信息 -->