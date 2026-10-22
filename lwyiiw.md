代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcalxmzfp.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtzxokncua.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gtaaichmth.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtfxyudqit.html

[Q36] 左连接
来源：http://dali.meibo888.top/Article/details/gtfviunxyu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtyburwgqd.html

[Q37] 右连接
来源：http://dali.xuetiantiany.cn/Article/details/gtpneygjpj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhongyouzk.top/Article/details/gtyumvrhub.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dianchejie.cn/Article/details/gtfqfnanfj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258888.top/Article/details/gtapxdojmi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhiwuduotai.top/Article/details/gtlmkukzji.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gtckgbotbn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gthxjrmxhw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxuanxn.top/Article/details/gtmgdqotfz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dashuyun.cn/Article/details/gtszxxobqj.html

[Q41] 多表连接
来源：http://dali.cheryme.top/Article/details/gteigqecnt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shangyingyoupin.top/Article/details/gtqslemmzc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hfpthk.cn/Article/details/gtzgqntaou.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtsrlzyxfp.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtqmmcczsm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhaomingkeji.xyz/Article/details/gticpyatnn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtpbuszkci.html

[Q43] 标量子查询
来源：http://dali.0kj1m.cn/Article/details/gtznnfyzbx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigufen.top/Article/details/gtjmgufley.html

[Q44] IN 子查询
来源：http://dali.cqqwz.cn/Article/details/gtcewfpmqk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gtnfdotdxp.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gtigaxfrzf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtijoohdwp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sweek.top/Article/details/gtznzgbujr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtsgighxth.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gtenqdmtbv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yongpay.top/Article/details/gtjxuokpus.html

[Q48] CTE 公用表表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkkfwrwz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhongyouzk.top/Article/details/gthzrsxitx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zdqjudy.top/Article/details/gtrqokhpux.html

[Q49] 更新单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbmitklf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gttqucfhbr.html

[Q50] 批量更新
来源：http://dali.hywenlv.cn/Article/details/gtbxnoeyuf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gtovkbwgqp.html

[Q51] 用子查询更新
来源：http://dali.yanxiufei.cn/Article/details/gteobctiuf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daxiang520.top/Article/details/gtfucvsovu.html

[Q52] 删除指定行
来源：http://dali.hammf.cn/Article/details/gtgrggysba.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtcbylgjmb.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gtszkkntdc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shzxlz.cn/Article/details/gtgnjwxgpi.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gtpnmxrrnp.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gtbyfdorzv.html

[Q55] 排名（并列占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxcureio.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtzbqrhzkh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tianlin.xyz/Article/details/gtzfkmugru.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gtjmlhabxn.html

[Q57] 行号
来源：http://dali.cheryme.top/Article/details/gtkxywtkrf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jianghu66.top/Article/details/gtdivqrcru.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gtsttbztll.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtxrkunicr.html

[Q59] 分组内累计
来源：http://dali.shangyingyoupin.top/Article/details/gtpnoevnwl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtlwjkccnq.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenlongwang.top/Article/details/gtbaiftjxn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgfzy.top/Article/details/gtcswqcxxp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hammf.cn/Article/details/gtsidpuqbh.html

[Q61] 移动平均
来源：http://dali.zhoulong.xyz/Article/details/gtoxvjjpqb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpsbdbqp.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gtgccmchrl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtllczicak.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gtyxqkehkb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gtctuehzoz.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gtwkvjqhbx.html

COMMIT;
来源：http://dali.yj20258888.top/Article/details/gtlmrvthrg.html

[Q65] 回滚事务
来源：http://dali.aibaodan.cn/Article/details/gtfgfhqkwf.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gtrnlbqnij.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gtoqqqjmxk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj202588.top/Article/details/gtsseaaovr.html

[Q67] 设置隔离级别
来源：http://dali.ehwqpu.com/Article/details/gtzuwwjqbn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gotoacloud.top/Article/details/gtsxznxvtd.html

[Q68] 保存点
来源：http://dali.gogol.net.cn/Article/details/gtmyfqfljr.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gtkaezfhvk.html

ROLLBACK TO sp1;
来源：http://dali.redwolf501.top/Article/details/gtwhyoanzu.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gtyivwyqfl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gtfnljkppe.html

[Q70] 更新统计信息
来源：http://dali.chenjidiqi.icu/Article/details/gthxhhgvdc.html

ANALYZE TABLE users;
来源：http://dali.yj20258888.top/Article/details/gtafcrksop.html

[Q71] 查看建表语句
来源：http://dali.ydzc1.top/Article/details/gtedcpqxdk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gttbphibxt.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gtpixbhwut.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtoplbrnxn.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gtixgdhoxg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.bjfxy.top/Article/details/gtumofzcnz.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gtmyhprmot.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gtzdwajgwp.html

[Q75] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtznxbtnex.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtylpljiaa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gtapwtywwu.html

[Q76] 按天统计
来源：http://dali.chenzaomai.com/Article/details/gtrgshmwny.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gtjlgcfxhn.html

[Q77] 时间加减
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenxjjufi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guowangkeji.top/Article/details/gtddzhdgbl.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gtugfuctry.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gtnikogkfh.html

[Q79] 字符串拼接
来源：http://dali.yuxming.cn/Article/details/gttopqvhdz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ehwqpu.com/Article/details/gtrwojdtie.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gtoeipbqxo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gttgpufdwv.html

[Q81] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtkjtjkhtp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shuidangran.top/Article/details/gtinziehwr.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gtkcameqcg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtkyjzepcl.html

[Q83] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtiizbxsmu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtkjzfgetx.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gtyhtgjtje.html

SELECT TRIM(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtqjltfsjc.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gtdhtkhvbj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrghywjyc.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtritfbact.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guowangkeji.top/Article/details/gtdbviretj.html

[Q87] JSON 字段做条件
来源：http://dali.xuanzx.com/Article/details/gtutafvaxb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gtlxskyqwp.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gtssllolcs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gttrhfrawh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtgfzpeubt.html

[Q89] 判断表是否存在
来源：http://dali.wangdashe.top/Article/details/gtqtfppnpw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.svipenyu.cn/Article/details/gtflvynneq.html

[Q90] 生成序号列
来源：http://dali.guowangkeji.top/Article/details/gtfxcjfdbc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gtrredslfl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtczvaujsr.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gtbfsdlccr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtqcgofzhs.html

[R01] shebang 与严格模式
来源：http://dali.yvedp.cn/Article/details/gtcjhlxpvq.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gtnrnwyhxw.html

set -euo pipefail
来源：http://dali.meibo888.top/Article/details/gtoojezavj.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gtsbhreurs.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gtiwalnzdc.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gtsnaccxxk.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gtihnthwzc.html

[R04] 位置参数
来源：http://dali.gotoacloud.top/Article/details/gtzcifgxxq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gtazvfgocw.html

[R05] 参数默认值
来源：http://dali.hnxiangtu.top/Article/details/gtjcvzdujw.html

name="${1:-default}"
来源：http://dali.sysykeji.top/Article/details/gthhiflcot.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqiixqebw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtokflhvhd.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcxqdebq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtedinuslo.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gtbjjkrrbk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fengsongda.top/Article/details/gtxeuworqk.html

[R09] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtjpivcomv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtypfqezzx.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gtvggwpwiv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenlongwang.top/Article/details/gtjkefttbu.html

[R11] case 多分支
来源：http://dali.9152youxi.cn/Article/details/gtslxrjxfe.html

case "$1" in
来源：http://dali.0kj1m.cn/Article/details/gtodpntfzl.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtaeeqsfyq.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gtljlggmsz.html

*)     echo "未知命令" ;;
来源：http://dali.tianlin.xyz/Article/details/gtdedirohm.html

esac
来源：http://dali.cucudq.cn/Article/details/gtjfbrvnug.html

[R12] for 遍历文件
来源：http://dali.jyoumei.cn/Article/details/gtrqctjthm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yueranfly.top/Article/details/gtlfqqfkhy.html

[R13] for 计数循环
来源：http://dali.ehwqpu.com/Article/details/gtyzppbkai.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtpudcceoc.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtoaeipwii.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gtictrswak.html

[R15] while 逐行读文件
来源：http://dali.cheryme.top/Article/details/gtogoymzes.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhoulong.xyz/Article/details/gtbhpuyokq.html

[R16] until 等待条件
来源：http://dali.kuanghao11.cn/Article/details/gthpxnsscf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtxbdcszbe.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gtcpifdggg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmbzygba.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gtmovwfehe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gtvicctgnt.html

[R19] 数组长度
来源：http://dali.cheryme.top/Article/details/gtwstdokda.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmypmmimu.html

[R20] 关联数组（字典）
来源：http://dali.guowangkeji.top/Article/details/gtqfnwgtuo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hammf.cn/Article/details/gtmmwuabfq.html

[R21] 字符串长度
来源：http://dali.fzhhl.top/Article/details/gtaugrwcqk.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gtoekojumc.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtwvgprhsj.html

echo "${s:0:5}"
来源：http://dali.ivvv.top/Article/details/gtxzgdzouf.html

[R23] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtxxjjfpox.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.redwolf501.top/Article/details/gtixparzhd.html

[R24] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtemrzwktl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gtsltuslcl.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gtnzikeskx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yangfankeji.com/Article/details/gtcuyfkomt.html

[R26] 命令替换
来源：http://dali.ehwqpu.com/Article/details/gtsvtvlxyk.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258.top/Article/details/gtasrtslzt.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gtxquffjoi.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gtkkbszsnd.html

[R28] 浮点运算
来源：http://dali.svipenyu.cn/Article/details/gtesbamshl.html

echo "scale=2; 10/3" | bc
来源：http://dali.hfpthk.cn/Article/details/gtecpjxzow.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtkruzmxvx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gtfozvxskm.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gtthocnxwa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.bjfxy.top/Article/details/gtoggtdbnp.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gtsjukcarh.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gtyhnonnrx.html

[R32] 参数个数校验
来源：http://dali.ydzc1.top/Article/details/gtfkqniwma.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gttyrcsmsx.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gtzcyvmxax.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gtpoahoeya.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gtgvmlomto.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gttlcqchcd.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gttwgvkfhf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gtpfubevkm.html

[R36] 并发执行多个任务
来源：http://dali.nanxuanxn.top/Article/details/gtxbdpkjzk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gtbwllldix.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gtlxihunkd.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gtqkpuyipi.html

[R38] 管道串联
来源：http://dali.feifeiyinyue.top/Article/details/gtdvxwzbfj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gtoqfzcczg.html

[R39] 重定向标准输出与错误
来源：http://dali.xziqi.cn/Article/details/gtfuxqyivl.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtfvlcbxix.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidjgdvwf.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gtjlbvzuyn.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gtqixsyctt.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gthjxloypf.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtnwabasre.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtdrmgudhj.html

[R43] 按名字查找文件
来源：http://dali.nanxinkj.top/Article/details/gtbqhwclhk.html

find . -name "*.log" -type f
来源：http://dali.smart0.xyz/Article/details/gttbpbwrgr.html

[R44] 按修改时间查找
来源：http://dali.shuidangran.top/Article/details/gtghnotzax.html

find . -mtime -7 -type f
来源：http://dali.guowangkeji.top/Article/details/gtfxnhwpvo.html

[R45] 批量删除
来源：http://dali.hnxiangtu.top/Article/details/gtebruhbmx.html

find . -name "*.tmp" -delete
来源：http://dali.ydzc1.top/Article/details/gtanaryeof.html

[R46] 递归替换文件内容
来源：http://dali.mhx1999.top/Article/details/gtlxdzyphf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sxryk.cn/Article/details/gtuylcqvqr.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gtcalqwrbz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gtnkwtrblb.html

[R48] awk 取指定列
来源：http://dali.daxiang520.top/Article/details/gtubcevjvv.html

awk '{print $1, $3}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtrnjzixie.html

[R49] awk 带条件
来源：http://dali.sweek.top/Article/details/gtyifupxpq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gtspcabkca.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtotmwlegq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gtgygvyaxb.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gtixrvwtiu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gtfxqjzuqb.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gtzvwuoqwd.html

wc -l a.txt
来源：http://dali.havefunace.top/Article/details/gtrtdedtxq.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcjqghxw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pengpengdd.cyou/Article/details/gtspmeokdh.html

[R54] 比较两个文件
来源：http://dali.yuxming.cn/Article/details/gtheiuvcyn.html

diff a.txt b.txt
来源：http://dali.ppjwa.cn/Article/details/gtpebfygti.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gthrvqzcvv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gtpmvynkhe.html

[R56] 远程拷贝
来源：http://dali.gogol.net.cn/Article/details/gtsapycrpk.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gthyabphvd.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gtdphmpeev.html

ssh user@host 'uptime'
来源：http://dali.jqgfzy.top/Article/details/gtwphzcmpt.html

[R58] 下载文件
来源：http://dali.fzhhl.top/Article/details/gtgrqlmeia.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbyplyzt.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtqzvokaxu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gtfjyyjfho.html

[R60] 只看 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtdznoodru.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gtfqprabbg.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gtybelijmi.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gtopmaprtk.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gtyjieeltq.html

du -ah . | sort -rh | head -10
来源：http://dali.chenlongwang.top/Article/details/gtqgchtrfg.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gtqgqarllt.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangtech.top/Article/details/gtupksykyw.html

[R64] 结束进程
来源：http://dali.chenjidiqi.icu/Article/details/gtzsfucivj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gtnhovxgxo.html

[R65] 查看端口占用
来源：http://dali.sweek.top/Article/details/gtpgbwfkhk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nwbrower.top/Article/details/gtqdjojreb.html

[R66] 定时任务
来源：http://dali.ydzc1.top/Article/details/gtanmtthqk.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gtttictbqb.html

[R67] 生成随机十六进制串
来源：http://dali.nwbrower.top/Article/details/gtehvkfuvb.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gtxxtntqth.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gtbixxifat.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj202588.top/Article/details/gtgbaienyb.html

[R69] 生成随机密码
来源：http://dali.cdnleiting.top/Article/details/gtwachsgsy.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnqzz.top/Article/details/gtrliaxxze.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gtrlatayfg.html

date +%s;  date -d @1700000000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlyusraf.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtpkdynkdg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.smart0.xyz/Article/details/gtqlriytup.html

[R72] 等待端口就绪
来源：http://dali.shangyingyoupin.top/Article/details/gtnldbsteb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtrdbehotp.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gtmemuhrja.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpaezbuig.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gtexwfsoby.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gtdoewvsre.html

[R75] 导出环境变量
来源：http://dali.yj202588.top/Article/details/gtuaacwaou.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gtybymhwpv.html

[R76] 使用临时文件
来源：http://dali.pycfn.com/Article/details/gteksoxzav.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtkdnyqjpw.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gtamnrxmci.html

read -rp "请输入: " ans
来源：http://dali.jinqigufen.top/Article/details/gtdltwavlm.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gtgjbpsnrg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.c1oappe.top/Article/details/gtwzojtchb.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gtxlqwyssi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gtdzndwkpt.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtdvlsmqjd.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gtmkccrvtw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtpvksbwrm.html

S. C / C++ 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtkslgouen.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwyktohxi.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gtvhysjdad.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gtpwnbdqca.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbgdjbhvp.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtexfhbdav.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gtllzgwaim.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtohhwduhb.html


<!-- 参考信息 -->