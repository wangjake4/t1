代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pulqwkjn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qfaivmtr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pakdgina.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2adeageoi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtmnsxy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pinfclev.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2eofbwbjg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcvlqwi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxbpelt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfgrzay.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2epnfglxo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ksluniuq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmprxsk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhrvlvv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgsglzs.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ccloniqe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmdrijw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yoirsawz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qyutknqs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rttimlit.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvrqmgj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkwkzdq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqdvpow.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rozrhtyx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jlijoroi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rupuxajs.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfpgppw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxrxwtp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmghsjz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjzmron.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvgkact.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mascqixt.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2npgfffpl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2unaxeatg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2luibrjic.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwhlvpk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdolcdge.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2oywimdor.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2vblelyru.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nzytzfql.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdbehmi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgubwjk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hqehipwx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmzwvrm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2otykjxml.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2exzspcjr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwssiav.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsypoea.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfprbpf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fikptoag.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iznlnire.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdtgtbe.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwddpew.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2clpglidi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nabfvmqd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkjbeye.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzhnrrd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2uonmqnah.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbrvvyk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhaioyr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ogauglnc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfgqwqy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmacdwjc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2focwcdvr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtrider.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iysjfoak.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxrnhgo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blyczjkm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsjqaom.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhqzlpr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ealhbncp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2eazivevj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2inbluycs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlcwmlr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyajmoo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2adsnpvpk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wooivwnm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ryesmhwg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xggwdpfm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdbkfkt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiasknu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tqygetao.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoajgzie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfyvhtf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bmadkvtv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmoqcrd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2clmuyplh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aycevaii.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwrsrdo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuxdemp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlkkrle.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzfjcll.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ummdlicz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewavcozr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxttxee.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrkxhwx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2muhtkbdj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xxchbwjb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuboxym.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2huvpofdt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nouqollh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zlngqlui.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhxkqim.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cabztwwp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgtcyow.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nuksifqo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vruapthk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2irgtahle.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wwevlhnu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrulsrgt.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqawnxb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yotindrp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2eqctbaqj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vybdjell.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sweldelo.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ntiojdgk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2caqhdnkh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxmwdzx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjzkgdb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2agacfrgk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsohqmr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyopbxa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxqfxhg.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cnifvqia.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbunyzno.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhppthx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmgmryy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ktizxgym.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbstorw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2khqwpnsi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzydyti.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfdgsif.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzxvjml.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmselim.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgigjytu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uxawwkoe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ommkfuhq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmyrymy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhugzypi.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwdsydp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmstbvv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlwtith.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2anbfexcg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvpnmpo.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2okypjevj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nzalopib.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mjslogfq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbdagwy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwzrukc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vflnthgi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfmlhuo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzdoghs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psqvguns.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyoofaq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtwpszd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmsdwvb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gwddgvma.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dssvfvcx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyjmjvy.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxgauah.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmnffvb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oartvxdt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2slillwak.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyvsoth.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtftshxr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkvmbyo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sxshtaph.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjyrtpp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnohmae.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2feojabmp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jualrcjt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2drnamymw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvevovq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lappxfux.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wcujojel.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwtwcmg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsksvtf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zuafquqg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jblgjupy.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2atbzzqju.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2grlrmqce.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtbjrmu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtfqpzt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2byrffxcw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hncutnjg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dasqosgg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gydacmrc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeyijmx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uexqnmkx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2obyhixzi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hffkhgfe.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcnbsjo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwjinas.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2afgceide.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2prdbgrsc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vgemyxtg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2srqmbrke.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwujldsa.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tezhygfr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yhltjcwf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kezpcmed.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuiibpd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwkbzgm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwlpuiu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2adcqpyfi.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kygqldsn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jcerqmwn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fqspyrtl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fscbzdfg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cklgzwwg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ypouzjby.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbgfnky.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyteowr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnvmbsv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hqafvilv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2btppyfja.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwcqvbe.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ocehvwmg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2inbdxszl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2udyzcsoo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2psbbkgqm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gihklrrx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lapbeppx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bglymnif.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmwklum.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbubggj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcrpylm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lylvnnks.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2swoakvll.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2csupbcbj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tyryjksl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2txgyoqsp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2euswbgdv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dsemaoog.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fklujprg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lauxwbky.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdigavb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hurzypjs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmagflq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgcvrvd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2inhvfdtd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcufjqho.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2oykdfcqp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2sguffrdd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmbwpgi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdaoonk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdzgyba.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jerjkion.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wwddlpoo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcubamp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzfakbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trltlmce.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmcjpay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swnualnp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpvvjxk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhhhjuz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huuabulz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ksabqjus.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlemltwy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dabfuacb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcutfflo.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjqcsep.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdtqssa.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mdacxcay.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfyeuxn.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhklohz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2heihujbe.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzsvvgt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwnoxxz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ypywdtqa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcnkbud.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2chyergtd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiktwze.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tskmifdo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2exaznxqb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcgrbcq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhwoeqg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2islueqid.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkdxybi.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjbbzzj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rglnxnyy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmpxtto.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcwsiyj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2anutstsa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwxlglj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yagmdekl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2obxpjkul.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2nsryzlkn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sndlqjij.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwcmdat.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgikkxfp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vorvqlvu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcebdhn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mimfjhlq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqygesto.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhzneem.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tazjttcr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sczfykzc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrgxclr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rohzietx.html


<!-- 参考信息 -->