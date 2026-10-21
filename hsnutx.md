代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hongshengwenyu.top/Article/details/gttfcsbuoo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtijfgsnba.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllxwiqzf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xinyue.icu/Article/details/gtdwlhkzxu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugooqkej.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.andypj.xyz/Article/details/gtpjnqucll.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigfzy.top/Article/details/gtanmfyyka.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gtrzukptzg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gtdldtfmcm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gtrfoohdgf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gtdqviugzo.html

[Q42] 连接条件附加过滤
来源：http://dali.bjfxy.top/Article/details/gtsliddvfz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jiagoushi.top/Article/details/gtomvaulec.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.havefunace.top/Article/details/gtmkcgshxy.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gtxuawgdfm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.mhx1999.top/Article/details/gtcbgpsaci.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtpcbqntvt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aibaodan.cn/Article/details/gtxvgscyst.html

[Q45] EXISTS 判断存在
来源：http://dali.chenjidiqi.icu/Article/details/gtgckvoxqo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtbgkagfqm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gtdhwyfqtk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtcflnibwf.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gtcxkrcqgp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gtzhpfcckt.html

[Q48] CTE 公用表表达式
来源：http://dali.snrcjt.cn/Article/details/gtgdoqqnwb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shzxlz.cn/Article/details/gtrdqcfjmj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfcyutee.html

[Q49] 更新单行
来源：http://dali.ehwqpu.com/Article/details/gtjqjbroly.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtlwyqrnzt.html

[Q50] 批量更新
来源：http://dali.cucudq.cn/Article/details/gthuqatdfz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gtblhpcvva.html

[Q51] 用子查询更新
来源：http://dali.xziqi.cn/Article/details/gtsqhezruo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtaspcmetx.html

[Q52] 删除指定行
来源：http://dali.iojbl.cn/Article/details/gtgxwjyawu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gtabuidhcl.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gthtxkjaix.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtnnhhvkoa.html

[Q54] 清空表
来源：http://dali.pengpengdd.cyou/Article/details/gtbtubvlkr.html

TRUNCATE TABLE logs;
来源：http://dali.0kj1m.cn/Article/details/gtsrlbfmvw.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gtxfssufkj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtxtmpfror.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenzaomai.com/Article/details/gtimsamucg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpanscnz.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gthhxcrajf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.iojbl.cn/Article/details/gtfqqkpwoo.html

[Q58] 累计求和
来源：http://dali.hysaishi.cn/Article/details/gttrdpcrmh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gtpebkqfdc.html

[Q59] 分组内累计
来源：http://dali.zhoulong.xyz/Article/details/gtdkeoywyo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtrtbuddeh.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxuanxn.top/Article/details/gtnmnklciu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gtplvoclmg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtheewqgsa.html

[Q61] 移动平均
来源：http://dali.cqqwz.cn/Article/details/gtjjatzrem.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtijedcvrr.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gtrrthzfjs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtpzjqietf.html

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gtwdqqungr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.svipenyu.cn/Article/details/gtrgkosupv.html

[Q64] 提交事务
来源：http://dali.pycfn.com/Article/details/gtndpefygk.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gtuulfqved.html

[Q65] 回滚事务
来源：http://dali.0kj1m.cn/Article/details/gtmvnhvjlf.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gtjsmevjii.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gtsejyzkvg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aibaodan.cn/Article/details/gtzcopxkrd.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gtqcsgjfhd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ppjwa.cn/Article/details/gtpagvpynz.html

[Q68] 保存点
来源：http://dali.yangfankeji.com/Article/details/gtgrwrfchv.html

SAVEPOINT sp1;
来源：http://dali.hammf.cn/Article/details/gtcamsxvsd.html

ROLLBACK TO sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gtjxiajyoi.html

[Q69] 查看执行计划
来源：http://dali.mhx1999.top/Article/details/gtgbkihakl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.9152youxi.cn/Article/details/gtbvezghdt.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmamdoko.html

ANALYZE TABLE users;
来源：http://dali.mhx1999.top/Article/details/gtxhouzmji.html

[Q71] 查看建表语句
来源：http://dali.pengpengdd.cyou/Article/details/gtgcgypzwb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hammf.cn/Article/details/gtjqrnqeyu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gtahvbhfqv.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtiltvjqto.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gtbujitdfg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dashuyun.cn/Article/details/gtyicdvmpf.html

[Q74] 强制使用索引
来源：http://dali.zycfv.cn/Article/details/gtherbuoro.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gtpznrooty.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gtikhvmbrs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258.top/Article/details/gtdevlnumu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258.top/Article/details/gtlaidwkhq.html

[Q76] 按天统计
来源：http://dali.andypj.xyz/Article/details/gtsdkoehdu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.svipenyu.cn/Article/details/gtyituyjva.html

[Q77] 时间加减
来源：http://dali.zhongyouzk.top/Article/details/gtmertrbfq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gtkwwgnrpr.html

[Q78] 当前时间
来源：http://dali.yj20258888.top/Article/details/gttdmldako.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gtmjtsyvey.html

[Q79] 字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtlwbhfpeg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dianchejie.cn/Article/details/gtaigiiynb.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gtnrdghhkh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cheryme.top/Article/details/gtiwnpwsrd.html

[Q81] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcxuyqdr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guannengcc.top/Article/details/gtnuivoril.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gtetacqewu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtxayxohyy.html

[Q83] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtkpdzgsci.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtvfjehzws.html

[Q84] 去除首尾空格
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxmpqhrn.html

SELECT TRIM(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtzjdjzzgf.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gtnzglelrj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gtaemjrrui.html

[Q86] 读取 JSON 字段
来源：http://dali.svipenyu.cn/Article/details/gtabaztbfb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiffzhxal.html

[Q87] JSON 字段做条件
来源：http://dali.guowangkeji.top/Article/details/gtmknpedak.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pengpengdd.cyou/Article/details/gtgdbybtwj.html

[Q88] 行转列（条件聚合）
来源：http://dali.cashguo.top/Article/details/gtzmcblfdd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cdnleiting.top/Article/details/gtihnaifln.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tian-w.cn/Article/details/gtxglafrrl.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gtkvwmfdrf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnljsdqb.html

[Q90] 生成序号列
来源：http://dali.havefunace.top/Article/details/gtjadowipr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gthbygmlwc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmtqklehn.html

R. Bash 专题
来源：http://dali.hnxiangtu.top/Article/details/gtjhszwxov.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmgoijqnb.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtrjusfwlj.html

#!/usr/bin/env bash
来源：http://dali.mhx1999.top/Article/details/gtspdznkzg.html

set -euo pipefail
来源：http://dali.316326.xyz/Article/details/gtcfoqqzra.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gtsjrejwte.html

name="Tom"; echo "$name"
来源：http://dali.jinqigfzy.top/Article/details/gtbvvpkhrw.html

[R03] 只读变量
来源：http://dali.zhongyouzk.top/Article/details/gthwqvwmwa.html

readonly PI=3.14
来源：http://dali.sysykeji.top/Article/details/gtcffmpklo.html

[R04] 位置参数
来源：http://dali.jinqigfzy.top/Article/details/gtxqbpndid.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangshuangyany.cn/Article/details/gtvdltmfeq.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gtppqhqmqn.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gtzpefsfmb.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gtbxfkjrfo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtmtvhyhur.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gtnxrxiswp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gttjniamzz.html

[R08] 数值比较
来源：http://dali.haohaochexian.top/Article/details/gthzudfzyp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gtxkthknmq.html

[R09] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gtnlyowbui.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnqzz.top/Article/details/gtascydgms.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gtbvivuwcm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtayaqsnmt.html

[R11] case 多分支
来源：http://dali.yuxming.cn/Article/details/gttyntjxju.html

case "$1" in
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmetocyyt.html

start) echo "启动" ;;
来源：http://dali.yj202588.top/Article/details/gtrmigcsky.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gturfvtqej.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gtlhjtvbxx.html

esac
来源：http://dali.xylfe.cn/Article/details/gtvcsognuu.html

[R12] for 遍历文件
来源：http://dali.wangshuangyany.cn/Article/details/gtxctnkurz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xinyue.icu/Article/details/gtajzyrjfm.html

[R13] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtpnppudst.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtnlmtxeke.html

[R14] C 风格 for
来源：http://dali.ivvv.top/Article/details/gtahqsursr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gtvjsuoupx.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gttdbjjnnz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxuanxn.top/Article/details/gtofiqwrel.html

[R16] until 等待条件
来源：http://dali.nanxuanxn.top/Article/details/gtvjgrgnpk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtnubkjfbu.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gtyvtxhpad.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwswgkta.html

[R18] 遍历数组
来源：http://dali.yvedp.cn/Article/details/gtlwrerhzu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.meibo888.top/Article/details/gttbevsbjj.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtwuqxpd.html

echo "${#arr[@]}"
来源：http://dali.birdmap.top/Article/details/gtalxpaxvh.html

[R20] 关联数组（字典）
来源：http://dali.jiagoushi.top/Article/details/gttthyqlrj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aizwys.cn/Article/details/gtkajrhpbg.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gtqgcujsfj.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gtxnlvzibv.html

[R22] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gtpsmsmavr.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gtneqlcshd.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtsipiwnjn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gtnvuzampo.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtagtnwlsa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zycfv.cn/Article/details/gtlpacztvx.html

[R25] 去后缀 / 去前缀
来源：http://dali.yueranfly.top/Article/details/gtkzlbkuhb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gtayphtonl.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gtlsvxnivj.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gtttorjpjc.html

[R27] 算术展开
来源：http://dali.smart0.xyz/Article/details/gtjpvhwxcv.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gtnusisyyi.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gtsrjmxkvu.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwnxuaej.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gtxglcxupz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gtbzplsduz.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gtwsywhikh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhoulong.xyz/Article/details/gtmrnizmyi.html

[R31] 局部变量
来源：http://dali.mhx1999.top/Article/details/gtsevzourq.html

f() { local x=1; echo "$x"; }
来源：http://dali.xinyue.icu/Article/details/gtkjdoskrj.html

[R32] 参数个数校验
来源：http://dali.cucudq.cn/Article/details/gttiuzjzmd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gtlorihpip.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtffkkalux.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gtgoqdwpti.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gtigetedzm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtmsxnttfg.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gtzmouhyae.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.redwolf501.top/Article/details/gtaauopbgf.html

[R36] 并发执行多个任务
来源：http://dali.hongshengwenyu.top/Article/details/gtykrzodku.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gtdcyjnvio.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gtqbwkdssu.html

files=$(ls -1)
来源：http://dali.gaohongyu789.top/Article/details/gtshuuntqe.html

[R38] 管道串联
来源：http://dali.chenzaomai.com/Article/details/gtbemtxawz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nwbrower.top/Article/details/gtsvxslmdp.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gtenstjmys.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtssrdbksr.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gtmjandsqx.html

echo "log" >> out.log
来源：http://dali.wangdashe.top/Article/details/gtatvmyphj.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gtelgbxown.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtrrdgmkec.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxudetuy.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gtpmhmuwdk.html

[R43] 按名字查找文件
来源：http://dali.zhongyouzk.top/Article/details/gtowtsksme.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gtygedhzfj.html

[R44] 按修改时间查找
来源：http://dali.iojbl.cn/Article/details/gtsrazotln.html

find . -mtime -7 -type f
来源：http://dali.pycfn.com/Article/details/gtewzyjtyp.html

[R45] 批量删除
来源：http://dali.svipenyu.cn/Article/details/gtotmwjtec.html

find . -name "*.tmp" -delete
来源：http://dali.xziqi.cn/Article/details/gtrvpzwkcc.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gtdxggqzfj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gturaoktne.html

[R47] sed 单行替换
来源：http://dali.yuxming.cn/Article/details/gtixrhfips.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gtffhlfluq.html

[R48] awk 取指定列
来源：http://dali.gotoacloud.top/Article/details/gtvvgtrfjf.html

awk '{print $1, $3}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtgmkowlil.html

[R49] awk 带条件
来源：http://dali.zdqjudy.top/Article/details/gtupiepqzg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gtpivalkto.html

[R50] awk 求和
来源：http://dali.shanyushiyangtech.top/Article/details/gttdeskuqb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gthewfepgi.html

[R51] 排序去重取前几
来源：http://dali.ivvv.top/Article/details/gtfjbljoav.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gtmkoqykbm.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gtzmqkiduu.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gtpytblrvt.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gtegbtijmp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gtmxusamwq.html

[R54] 比较两个文件
来源：http://dali.mhx1999.top/Article/details/gtezkrljkj.html

diff a.txt b.txt
来源：http://dali.jianghu66.top/Article/details/gtvumvfhxk.html

[R55] 压缩与解压
来源：http://dali.hysaishi.cn/Article/details/gtgyofrcmc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gtfgegvtfv.html

[R56] 远程拷贝
来源：http://dali.9152youxi.cn/Article/details/gtcgqnnegv.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gthvadhyqx.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gtspfrvqhr.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gtdyvldbal.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gtjlsszavn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.vqdsnc.cn/Article/details/gtsqztrppe.html

[R59] 发 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gthcasprcr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gogol.net.cn/Article/details/gtxamrwinz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtfrhmswjf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gtwvlnekei.html

[R61] 磁盘占用
来源：http://dali.dianchejie.cn/Article/details/gtyxtdfzrl.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclymrams.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gtgwgsvcrq.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gtdgercalt.html

[R63] 内存与进程
来源：http://dali.yj20258.top/Article/details/gtihynymyi.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gtmtjnqksi.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gtbigwetke.html

kill -9 $(pgrep -f app.py)
来源：http://dali.andypj.xyz/Article/details/gtrmjudfor.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gtjtctlsoa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aibaodan.cn/Article/details/gtyqnjoxqb.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gtimlavoms.html

crontab -e;  crontab -l
来源：http://dali.sweek.top/Article/details/gttztbqulb.html

[R67] 生成随机十六进制串
来源：http://dali.cdnleiting.top/Article/details/gtfekwxxsi.html

openssl rand -hex 16
来源：http://dali.nanxinkj.top/Article/details/gtudxchzgs.html

[R68] 计算文件校验值
来源：http://dali.zhoulong.xyz/Article/details/gtspkksvza.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gtasnbpwgk.html

[R69] 生成随机密码
来源：http://dali.jianghu66.top/Article/details/gttlqnfwak.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gtvflglcbs.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gtkulsokmo.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gtbuarlamx.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtowbqpctn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigufen.top/Article/details/gtcufpykjx.html

[R72] 等待端口就绪
来源：http://dali.cdnleiting.top/Article/details/gtidrkoppq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtyotpiwjp.html

[R73] 分割大日志
来源：http://dali.xziqi.cn/Article/details/gtogvzferi.html

split -l 1000 big.log part_
来源：http://dali.cqqwz.cn/Article/details/gtmsnmgwke.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gtpxogmssw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hfpthk.cn/Article/details/gtcsjzbcuu.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtviyzfvnp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuxming.cn/Article/details/gtzlrvocnq.html

[R76] 使用临时文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkscodms.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtfxktruvy.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gtgnzcsvha.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gtykjnoziu.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gttgwxngyd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gtbxdlnvnu.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gtpchelzgr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gtnotgzzwu.html

[R80] 查看脚本执行耗时
来源：http://dali.jyoumei.cn/Article/details/gtokswzwoc.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gtrmmjnozh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvpakmoom.html

S. C / C++ 专题
来源：http://dali.iojbl.cn/Article/details/gtqowlmedv.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfypxkkia.html

[S01] C：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtajswlbpf.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gtuuelxqeq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daxiang520.top/Article/details/gtwzlyteoj.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gtbkolfljp.html

int a = 10; printf("%d\n", a);
来源：http://dali.hysaishi.cn/Article/details/gtyvhhpsmr.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gtzkydeydk.html

int x; scanf("%d", &x);
来源：http://dali.daria6918.cn/Article/details/gtzlytxich.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gttjxcnitn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtdjkfvqsu.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtgizyscuo.html

strlen(s)
来源：http://dali.hysaishi.cn/Article/details/gtareomyfg.html

[S06] C：字符串比较
来源：http://dali.316326.xyz/Article/details/gtofgbetdw.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gtpooilcno.html

[S07] C：数组遍历求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtovtvkzdq.html


<!-- 参考信息 -->