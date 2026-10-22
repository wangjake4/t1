代发 wailian999

[Q36] 左连接
来源：http://dali.sweek.top/Article/details/gt2fjwljcgv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2gogqeenl.html

[Q37] 右连接
来源：http://dali.fengsongda.top/Article/details/gt2fqapylng.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ppjwa.cn/Article/details/gt2rnaksjge.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ppjwa.cn/Article/details/gt2xxhnkmtn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.0kj1m.cn/Article/details/gt2gvgxbapc.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gt2nxvbxdvn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fuqvocdy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258.top/Article/details/gt2drrzcmab.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gt2emdxaulv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cheryme.top/Article/details/gt2brddgwhq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmxrsmx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gt2rkcjvdti.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gt2jocaafkx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mufevygg.html

[Q42] 连接条件附加过滤
来源：http://dali.fzhhl.top/Article/details/gt2zmcveanb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.quarkkingdee.top/Article/details/gt2hvwrursm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gt2wxjkhnos.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gt2rqhnarxf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sweek.top/Article/details/gt2elmimege.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gt2bmlxqzmv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gt2ocnaeleu.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gt2lvvrzxhe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gt2wssyahgw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gt2xfxdxydj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gt2pkwtirnm.html

[Q47] 与平均值比较
来源：http://dali.ybcxt.top/Article/details/gt2eophxalo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtofsvff.html

[Q48] CTE 公用表表达式
来源：http://dali.smart0.xyz/Article/details/gt2zblbuwur.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egpbjflo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.316326.xyz/Article/details/gt2jkgyajwg.html

[Q49] 更新单行
来源：http://dali.sweek.top/Article/details/gt2fgmveqwp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2hdxtoaze.html

[Q50] 批量更新
来源：http://dali.cheryme.top/Article/details/gt2ddadwcog.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.haohaochexian.top/Article/details/gt2bintvwfs.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gt2gvmcspvj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2xivwyvpi.html

[Q52] 删除指定行
来源：http://dali.svipenyu.cn/Article/details/gt2rrvijmxc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gt2kdllzznr.html

[Q53] 按条件删除
来源：http://dali.jqgufenzy.top/Article/details/gt2lzchncmd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gt2bfwcaiiv.html

[Q54] 清空表
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqjkgbre.html

TRUNCATE TABLE logs;
来源：http://dali.zhengqikj.top/Article/details/gt2gcstwyxz.html

[Q55] 排名（并列占位）
来源：http://dali.haohaochexian.top/Article/details/gt2rowjawhd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gt2itunudrk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.andypj.xyz/Article/details/gt2kwsuthwq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cheryme.top/Article/details/gt2wpadkrkz.html

[Q57] 行号
来源：http://dali.havefunace.top/Article/details/gt2mbgkayar.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2yduxpffm.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gt2ddljmpvr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2fwnasocl.html

[Q59] 分组内累计
来源：http://dali.9152youxi.cn/Article/details/gt2ebcfdbcw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2udczivgk.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gt2crjufric.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zycfv.cn/Article/details/gt2ifsfizfc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2pylzpdxa.html

[Q61] 移动平均
来源：http://dali.cqqwz.cn/Article/details/gt2belqfqix.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztcqrqcp.html

[Q62] 分组占比
来源：http://dali.fzhhl.top/Article/details/gt2rytfpwat.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iykkrptj.html

[Q63] 开启事务
来源：http://dali.jiagoushi.top/Article/details/gt2gzrmxwlk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cdnleiting.top/Article/details/gt2azytkjit.html

[Q64] 提交事务
来源：http://dali.iojbl.cn/Article/details/gt2ulumsimg.html

COMMIT;
来源：http://dali.nwbrower.top/Article/details/gt2cfjtongk.html

[Q65] 回滚事务
来源：http://dali.daxiang520.top/Article/details/gt2mhyjdzxx.html

ROLLBACK;
来源：http://dali.gzhubu.top/Article/details/gt2qyywnlca.html

[Q66] 行锁查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkbkvlcf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgufenzy.top/Article/details/gt2xzgziopc.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gt2wopqntmx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gt2cnrwsynr.html

[Q68] 保存点
来源：http://dali.hnqzz.top/Article/details/gt2bmkaqzce.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gt2aiseleji.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gt2esoejgic.html

[Q69] 查看执行计划
来源：http://dali.yvedp.cn/Article/details/gt2aakcebtk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gt2qdtnvuhr.html

[Q70] 更新统计信息
来源：http://dali.zdqjudy.top/Article/details/gt2gidjqfwc.html

ANALYZE TABLE users;
来源：http://dali.jianghu66.top/Article/details/gt2vijddldi.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gt2wudywmrm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdzujgme.html

[Q72] 查看索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2uiibiokx.html

SHOW INDEX FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2ppwnnpyi.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gt2csfgcwou.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.svipenyu.cn/Article/details/gt2qchqzrar.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gt2zrbfvjst.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sxryk.cn/Article/details/gt2kwpatysf.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2lkvuzeds.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2othsklyn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.9152youxi.cn/Article/details/gt2tjoogyii.html

[Q76] 按天统计
来源：http://dali.yj20258.top/Article/details/gt2hgrrddmp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sysykeji.top/Article/details/gt2bzbcgmcs.html

[Q77] 时间加减
来源：http://dali.yangfankeji.com/Article/details/gt2vknbaiqb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gt2avjqulpc.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gt2jiixkbof.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sufxvd.cn/Article/details/gt2gpmypkqf.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gt2wnrfrwij.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gt2bmxfgcsy.html

[Q80] 字符串截取
来源：http://dali.sweek.top/Article/details/gt2tlddgfdf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2iqqxcvar.html

[Q81] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gt2konmzjlr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2zwsmhkvj.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gt2ufboijdr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2sbetvnhv.html

[Q83] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gt2kqlxilyu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2yplysppj.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gt2ecpjubfy.html

SELECT TRIM(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2csvmwrbo.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gt2hbsukggd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gt2smeyzriy.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gt2jnhozygl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.redwolf501.top/Article/details/gt2tusfykdm.html

[Q87] JSON 字段做条件
来源：http://dali.cqqwz.cn/Article/details/gt2sqvriuia.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gt2grmsfvsw.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gt2vvpkbbuc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gt2gjsfaauw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2onulutlq.html

[Q89] 判断表是否存在
来源：http://dali.cashguo.top/Article/details/gt2nfkikvgm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yueranfly.top/Article/details/gt2vvpwimxi.html

[Q90] 生成序号列
来源：http://dali.chenjidiqi.icu/Article/details/gt2misjtcgu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gt2tyovtxuv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2lvttwhxw.html

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gt2ahqkdyxi.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2wcyhrbbf.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gt2fnypzwid.html

#!/usr/bin/env bash
来源：http://dali.wangdashe.top/Article/details/gt2imqerlvu.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gt2oyyhmwzk.html

[R02] 变量赋值与使用
来源：http://dali.hysaishi.cn/Article/details/gt2zmvtkidr.html

name="Tom"; echo "$name"
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwrnwrlz.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gt2jxuudsfz.html

readonly PI=3.14
来源：http://dali.tianlin.xyz/Article/details/gt2pdhazlgj.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovyrvxox.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.bjfxy.top/Article/details/gt2mrimhhez.html

[R05] 参数默认值
来源：http://dali.cucudq.cn/Article/details/gt2yxymmrte.html

name="${1:-default}"
来源：http://dali.316326.xyz/Article/details/gt2oucvcmgv.html

[R06] 判断命令是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2dvafvcej.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gt2tgxilwln.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gt2hyjocqfs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gt2utovcjrg.html

[R08] 数值比较
来源：http://dali.jlsjyb.cn/Article/details/gt2nqsvkbir.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2imililmo.html

[R09] 字符串比较
来源：http://dali.yongpay.top/Article/details/gt2jenfctpq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvdisfmj.html

[R10] 正则匹配
来源：http://dali.bjfxy.top/Article/details/gt2hwjgdzkm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2qjnkaezy.html

[R11] case 多分支
来源：http://dali.yonumen.top/Article/details/gt2riswpqxq.html

case "$1" in
来源：http://dali.gotoacloud.top/Article/details/gt2cfozgwjb.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2imprntrp.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gt2mafkmjcp.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2ysnfjzkd.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gt2gwsqofrk.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gt2xgtclkbs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2zumsvdvk.html

[R13] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gt2dmxalrqw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbecuqcs.html

[R14] C 风格 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rcfuazcb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gt2xklnsqua.html

[R15] while 逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gt2eekhalvh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xziqi.cn/Article/details/gt2kkuzucvm.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gt2cvhbxxhr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2mbwizzlz.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gt2ehguftef.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2jopiiuff.html

[R18] 遍历数组
来源：http://dali.havefunace.top/Article/details/gt2vbdzxnuz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2auxaoqhb.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gt2ngwbzdkv.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2owlmsuoy.html

[R20] 关联数组（字典）
来源：http://dali.guannengcc.top/Article/details/gt2stlpbnmr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.snrcjt.cn/Article/details/gt2xtuqlihm.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gt2mzmgcoza.html

echo "${#s}"
来源：http://dali.yuanzhike.top/Article/details/gt2cakzxkrg.html

[R22] 截取子串
来源：http://dali.yj20258.top/Article/details/gt2qgyolyzz.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gt2zefdijyz.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gt2fqzkxuvj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gt2knjnhyxn.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gt2sztkrqtg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gt2trgyslfj.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnxrpmqx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gt2toblixun.html

[R26] 命令替换
来源：http://dali.jlsjyb.cn/Article/details/gt2snehtrqv.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gt2cegagufo.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gt2fzmlzpqx.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gt2aytvgbpp.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gt2dtgvuivc.html

echo "scale=2; 10/3" | bc
来源：http://dali.daria6918.cn/Article/details/gt2hcjgpfsn.html

[R29] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjekqatj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgufenzy.top/Article/details/gt2rniejuyo.html

[R30] 函数返回状态码
来源：http://dali.zhixingplan.top/Article/details/gt2mqhgpolt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gt2jeprpycb.html

[R31] 局部变量
来源：http://dali.xuanzx.com/Article/details/gt2ehhjknkr.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gt2rqglokmh.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gt2uzxdkuny.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gt2jzjouhwu.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gt2vvyozfzv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydzqafso.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gt2jmjxgtoe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gt2ebghymsy.html

[R35] 后台执行并等待
来源：http://dali.meibo888.top/Article/details/gt2kieohhzz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gt2arodscef.html

[R36] 并发执行多个任务
来源：http://dali.aizwys.cn/Article/details/gt2xkczwhgy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxuanxn.top/Article/details/gt2tqxtipec.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkmbkxy.html

files=$(ls -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2ribnbemv.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gt2yyslbiwx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gt2wuqoikgf.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gt2vshkjzcx.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gt2egazynwh.html

[R40] 追加写日志
来源：http://dali.kuanghao11.cn/Article/details/gt2fsyrzztz.html

echo "log" >> out.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbuhprqr.html

[R41] 丢弃输出
来源：http://dali.c1oappe.top/Article/details/gt2sfoceffc.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzvynmwe.html

[R42] 输入重定向
来源：http://dali.yanxiufei.cn/Article/details/gt2wgkufbvc.html

wc -l < a.txt
来源：http://dali.316326.xyz/Article/details/gt2cyizxffp.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gt2nqktdvou.html

find . -name "*.log" -type f
来源：http://dali.guowangkeji.top/Article/details/gt2ykvvmxwj.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gt2anmbmefe.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gt2aoerwxpc.html

[R45] 批量删除
来源：http://dali.jyoumei.cn/Article/details/gt2dlwvdyzl.html

find . -name "*.tmp" -delete
来源：http://dali.ybcxt.top/Article/details/gt2tpvzrrlc.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gt2byjmkorl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gt2mrozbbwe.html

[R47] sed 单行替换
来源：http://dali.zhongyouzk.top/Article/details/gt2vnptjwpt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gt2bprcfxca.html

[R48] awk 取指定列
来源：http://dali.xuetiantiany.cn/Article/details/gt2cyeznirg.html

awk '{print $1, $3}' a.txt
来源：http://dali.shuidangran.top/Article/details/gt2wwmvxivz.html

[R49] awk 带条件
来源：http://dali.snrcjt.cn/Article/details/gt2zyzxbygy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gt2znsepnha.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gt2ccfhaasq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yongpay.top/Article/details/gt2bkbtoivq.html

[R51] 排序去重取前几
来源：http://dali.birdmap.top/Article/details/gt2gycqhllm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gt2umzujanj.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gt2lsxeeoji.html

wc -l a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2gwcwzgny.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gt2arlnkbjh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hywenlv.cn/Article/details/gt2xkgdbwtl.html

[R54] 比较两个文件
来源：http://dali.svipenyu.cn/Article/details/gt2elpndqlw.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gt2qxaqhnoo.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gt2jneeemjg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xylfe.cn/Article/details/gt2zeitwupc.html

[R56] 远程拷贝
来源：http://dali.dianchejie.cn/Article/details/gt2blafnaxk.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gt2xxgcsakw.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gt2trovdght.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gt2gekmyifc.html

[R58] 下载文件
来源：http://dali.9152youxi.cn/Article/details/gt2rvwsfkqp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gt2zzckpabs.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gt2csefbtmg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gt2jnxutetz.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gt2bptaakss.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhiwuduotai.top/Article/details/gt2pclkvhro.html

[R61] 磁盘占用
来源：http://dali.dashuyun.cn/Article/details/gt2coytqieh.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gt2qrmxmwgd.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gt2xjvfvhmn.html

du -ah . | sort -rh | head -10
来源：http://dali.hnxiangtu.top/Article/details/gt2zkhzrdyk.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gt2uoeqqnyc.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gt2biyvsyls.html

[R64] 结束进程
来源：http://dali.shuidangran.top/Article/details/gt2crmxxfdb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jklpvtsf.html

[R65] 查看端口占用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ishrxcxe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenzaomai.com/Article/details/gt2ahhxecuf.html

[R66] 定时任务
来源：http://dali.ivvv.top/Article/details/gt2kvjiqywp.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gt2sbdatnzo.html

[R67] 生成随机十六进制串
来源：http://dali.zhixingplan.top/Article/details/gt2stwxebse.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gt2sumlxfdl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwrwubd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gt2twuvsowf.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gt2heaptvuq.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phyubxmn.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujivkuvq.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gt2euopsjue.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2eimbegzo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jyoumei.cn/Article/details/gt2dtjktbte.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gt2bsrmizpa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gt2fvlapntt.html

[R73] 分割大日志
来源：http://dali.yanxiufei.cn/Article/details/gt2rqdyscpl.html

split -l 1000 big.log part_
来源：http://dali.cucudq.cn/Article/details/gt2otocbmkv.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gt2xuojejeq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gt2gyhitwmk.html

[R75] 导出环境变量
来源：http://dali.gzhubu.top/Article/details/gt2mfzxdfdh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gt2btzrblst.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kxitmkbb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swmcegsj.html

[R77] 读取用户输入
来源：http://dali.guowangkeji.top/Article/details/gt2tkhbrpon.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gt2hutsudfd.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gt2dswyasva.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2atrgrvmg.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gt2dcjivddt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cdnleiting.top/Article/details/gt2naioigte.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gt2peelveyr.html

time ./run.sh
来源：http://dali.jqgufenzy.top/Article/details/gt2xfemyked.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zavlpbwz.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gt2fuzqkdyp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2egvnvjmz.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2imztakuh.html

#include <stdio.h>
来源：http://dali.yongpay.top/Article/details/gt2sqvdmaig.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangdashe.top/Article/details/gt2jzuixxbd.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcqyoubf.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gt2nzhgmdib.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gt2uzajwzqc.html

int x; scanf("%d", &x);
来源：http://dali.snrcjt.cn/Article/details/gt2ozbuqdju.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gt2deevdvtp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ybcxt.top/Article/details/gt2qbdmwdtt.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gt2sqlsjkvz.html


<!-- 参考信息 -->