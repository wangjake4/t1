代发 wailian999

[Q33] 多列分组
来源：http://dali.yj20258.top/Article/details/gtkrcpraow.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gthbmiocqe.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gtwdaqzsfq.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gtrhmftcbu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jianghu66.top/Article/details/gtkacyaqmv.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gtasgehxnz.html

[Q35] 内连接
来源：http://dali.yanxiufei.cn/Article/details/gtkhtgeldf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gtirhcwygm.html

[Q36] 左连接
来源：http://dali.shzxlz.cn/Article/details/gtrpizrsem.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtcolliogd.html

[Q37] 右连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcewlsayy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gterfmzghc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fengsongda.top/Article/details/gtlekzpozb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nwbrower.top/Article/details/gtqbekjmxa.html

[Q39] 自连接（查上下级）
来源：http://dali.yj20258888.top/Article/details/gtowuqhagu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.bjfxy.top/Article/details/gtxevmrsny.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jyoumei.cn/Article/details/gtprpslthi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gteravjxmb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ehwqpu.com/Article/details/gtroiaskpb.html

[Q41] 多表连接
来源：http://dali.hnqzz.top/Article/details/gtyknwytxm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fengsongda.top/Article/details/gtfyuyeznl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.feifeiyinyue.top/Article/details/gtmdjppqcu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yanxiufei.cn/Article/details/gtjublocaf.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtgxndddfh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guannengcc.top/Article/details/gttkvyuadl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fzhhl.top/Article/details/gtkymgrhzy.html

[Q43] 标量子查询
来源：http://dali.dianchejie.cn/Article/details/gtpumxvmro.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shzxlz.cn/Article/details/gtlbixccda.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gteskamszh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuxming.cn/Article/details/gtrojkmpyv.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gtgyeizxbv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtajynqetz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hfpthk.cn/Article/details/gtqcwcgfro.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gtssfqlqjo.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gtftlfsnuo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gtotpnwbpd.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gtvardfglq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gtdndwtbnd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtqkfyhlrc.html

[Q49] 更新单行
来源：http://dali.andypj.xyz/Article/details/gtrzexooly.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtecquwsqc.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gtprtihhuu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.redwolf501.top/Article/details/gtvrbwqftv.html

[Q51] 用子查询更新
来源：http://dali.cqqwz.cn/Article/details/gtuwlhzjlj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtdkjjcrzw.html

[Q52] 删除指定行
来源：http://dali.havefunace.top/Article/details/gtgaqadwqw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtwrpbmowy.html

[Q53] 按条件删除
来源：http://dali.kuanghao11.cn/Article/details/gtcqvcwsbr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cucudq.cn/Article/details/gtbbsjaior.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gtbrmuaytu.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdibtgbcs.html

[Q55] 排名（并列占位）
来源：http://dali.sufxvd.cn/Article/details/gtfyzmuzkl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gtzwknbvrw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xylfe.cn/Article/details/gtiaesfvrt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtdshydhcl.html

[Q57] 行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhsaxoyx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtauwwxiqs.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gtkvtjfxau.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hammf.cn/Article/details/gtmmhwnawl.html

[Q59] 分组内累计
来源：http://dali.gotoacloud.top/Article/details/gtkxqhuewv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtjhufedln.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gtdotgjhan.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gtbrrkkwoz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtvvymnnor.html

[Q61] 移动平均
来源：http://dali.guannengcc.top/Article/details/gtpqbmdqcw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtuxjvufpp.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gthugpkenw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtdxubcxtg.html

[Q63] 开启事务
来源：http://dali.zhoulong.xyz/Article/details/gtufrnxglg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gtszvgxnbb.html

[Q64] 提交事务
来源：http://dali.aibaodan.cn/Article/details/gtehliucql.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gtheehyqnj.html

[Q65] 回滚事务
来源：http://dali.fengsongda.top/Article/details/gtjahdmwmx.html

ROLLBACK;
来源：http://dali.tian-w.cn/Article/details/gtqoovutbf.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gtifsuzmvu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gtjlkcczdc.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gtrkueagxc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tianlin.xyz/Article/details/gtwlqfczad.html

[Q68] 保存点
来源：http://dali.guowangkeji.top/Article/details/gtwnoryjcj.html

SAVEPOINT sp1;
来源：http://dali.jianghu66.top/Article/details/gtacedjehe.html

ROLLBACK TO sp1;
来源：http://dali.yj20258.top/Article/details/gtpsulduxz.html

[Q69] 查看执行计划
来源：http://dali.svipenyu.cn/Article/details/gtnsxccrnc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaobukgza.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtorwuapsk.html

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gtnwuaolnu.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gtwxcsoshr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tian-w.cn/Article/details/gtwsaycibp.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gtjjhxggpc.html

SHOW INDEX FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gthqjztmii.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gthwudnoms.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xinyue.icu/Article/details/gtbvpqxidk.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gtpjicicnl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gtbrnxpdxs.html

[Q75] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtumkvylsz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtdnehoeqj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigufen.top/Article/details/gtdehoavxx.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtqjkoqavj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gtvtldaabx.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gtpfacgatr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnxiangtu.top/Article/details/gtstlmxgfy.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtylnvef.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenlongwang.top/Article/details/gtbgnlucwo.html

[Q79] 字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtfykidtku.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gtnklacori.html

[Q80] 字符串截取
来源：http://dali.pengpengdd.cyou/Article/details/gtrebnrzrk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlynmnuk.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtrhcgnrxi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtkuvcqzzf.html

[Q82] 字符长度与字节长度
来源：http://dali.jianghu66.top/Article/details/gtkhmfgyic.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtragxaevw.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtnljayrre.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtodmpmgpt.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gtuzlzszoo.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtfxdecrqr.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gtagbgugrn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ehwqpu.com/Article/details/gtghefymak.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gtkbdftdqa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gtekdenicx.html

[Q87] JSON 字段做条件
来源：http://dali.iojbl.cn/Article/details/gtgfummurb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gtokvjipbg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gtvmchjetl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.snrcjt.cn/Article/details/gtbmogqhdr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtlxjirvnp.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gtejrmtbbn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtpxkcfrdu.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gtxmwzxvqy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gtzmjtmeab.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqgppxyml.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gtndblbaxf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtoiiybgfa.html

[R01] shebang 与严格模式
来源：http://dali.zdqjudy.top/Article/details/gtlqbltyrl.html

#!/usr/bin/env bash
来源：http://dali.tianlin.xyz/Article/details/gtkkvzeoqv.html

set -euo pipefail
来源：http://dali.yongpay.top/Article/details/gtzoknzfix.html

[R02] 变量赋值与使用
来源：http://dali.snrcjt.cn/Article/details/gteskygkvf.html

name="Tom"; echo "$name"
来源：http://dali.chenjidiqi.icu/Article/details/gtgstnwkow.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gtybscexck.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gtueesxtbo.html

[R04] 位置参数
来源：http://dali.pycfn.com/Article/details/gtqvyeusaj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sweek.top/Article/details/gtcleydjyu.html

[R05] 参数默认值
来源：http://dali.yvedp.cn/Article/details/gtuqemeekb.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gtvvqysxko.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtjbqrlrkk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtmkjldnyo.html

[R07] if 判断文件
来源：http://dali.shzxlz.cn/Article/details/gtmugmoyzd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aizwys.cn/Article/details/gtqxttxryf.html

[R08] 数值比较
来源：http://dali.daxiang520.top/Article/details/gtvhrzhxrx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtezukaluw.html

[R09] 字符串比较
来源：http://dali.jianghu66.top/Article/details/gtdlfkfsdz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gtbvyadqtg.html

[R10] 正则匹配
来源：http://dali.mhx1999.top/Article/details/gtbuqwksxv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gtxawwslja.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gtjiheejmo.html

case "$1" in
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjiaaqneh.html

start) echo "启动" ;;
来源：http://dali.hnqzz.top/Article/details/gtcwghaprf.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gtfavefikg.html

*)     echo "未知命令" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtsxsbbjgg.html

esac
来源：http://dali.cheryme.top/Article/details/gtbqkzoxhi.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gtclssowxs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gtjxnkwyvm.html

[R13] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gtsejfiuqe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gtdvubpbxg.html

[R14] C 风格 for
来源：http://dali.feifeiyinyue.top/Article/details/gtksyuqpil.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtwdxxbwdb.html

[R15] while 逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gteuatbhqk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jianghu66.top/Article/details/gtzhbbephl.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtbrqwlyxu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gtbioszrrt.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gtvnoohrmn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtrjkwlebl.html

[R18] 遍历数组
来源：http://dali.smart0.xyz/Article/details/gtalnhawps.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xinyue.icu/Article/details/gtbyihhhgk.html

[R19] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtvvgpeqrz.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gtvlwwpzcv.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gtrmvcpwbj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbymtoirh.html

[R21] 字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtsbycnrxi.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gtoavpsvlw.html

[R22] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gtdvcxmpnl.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gtlrivkjvy.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgfehayf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258.top/Article/details/gtdkvfsslf.html

[R24] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtsdaaburw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jlsjyb.cn/Article/details/gtyfcgakts.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigufen.top/Article/details/gthledgptl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gtjjvdfujx.html

[R26] 命令替换
来源：http://dali.yonumen.top/Article/details/gtapcsbytx.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gtrqwnjuqd.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gtadbkfzsj.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gtxaltyows.html

[R28] 浮点运算
来源：http://dali.tian-w.cn/Article/details/gtvnannxxa.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gtlmwmhmpa.html

[R29] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gtsabchxhd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gtkneivdtu.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtdjoolgzb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnqzz.top/Article/details/gtjrsuazoa.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gtrfaatlok.html

f() { local x=1; echo "$x"; }
来源：http://dali.quarkkingdee.top/Article/details/gtettsjgdo.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gtcmdiuqvu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtompkapve.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtwlamiwie.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangkeji.top/Article/details/gttopanixl.html

[R34] 退出时清理
来源：http://dali.shanyushiyangtech.top/Article/details/gtacstjrzl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtakogjhme.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gtvogxecuj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gtoitolblk.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gtngpkdoal.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprevayki.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gtemvrzjua.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gtwhbworkw.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gtauqvttcx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gtufmjmojr.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtkwwxmzot.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gtuiklhrrp.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gtwsyutgtp.html

echo "log" >> out.log
来源：http://dali.nanxinkj.top/Article/details/gtvotunobw.html

[R41] 丢弃输出
来源：http://dali.ydzc1.top/Article/details/gtihaywdhn.html

cmd >/dev/null 2>&1
来源：http://dali.yj202588.top/Article/details/gtrqvukkyb.html

[R42] 输入重定向
来源：http://dali.yanxiufei.cn/Article/details/gthylahllh.html

wc -l < a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdngotoi.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gtvlwscdve.html

find . -name "*.log" -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdquxwme.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gtjlfqcblq.html

find . -mtime -7 -type f
来源：http://dali.cucudq.cn/Article/details/gtphfipoom.html

[R45] 批量删除
来源：http://dali.yj20258.top/Article/details/gtmyquxgxy.html

find . -name "*.tmp" -delete
来源：http://dali.gogol.net.cn/Article/details/gtqnlfoihs.html

[R46] 递归替换文件内容
来源：http://dali.vqdsnc.cn/Article/details/gtajczpdig.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjdmgtym.html

[R47] sed 单行替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgsexbcg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtztuchrvb.html

[R48] awk 取指定列
来源：http://dali.xuetiantiany.cn/Article/details/gtalbuosdh.html

awk '{print $1, $3}' a.txt
来源：http://dali.xinyue.icu/Article/details/gtkxewlchc.html

[R49] awk 带条件
来源：http://dali.shzxlz.cn/Article/details/gtieonyghl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.iojbl.cn/Article/details/gtgpjjibpz.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtqgmmqfoe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gthystpicn.html

[R51] 排序去重取前几
来源：http://dali.zhixingplan.top/Article/details/gtohihobdp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhengqikj.top/Article/details/gtdonknvwz.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gtunrnkneh.html

wc -l a.txt
来源：http://dali.yongpay.top/Article/details/gtqwlkuavp.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gtxjndlrhx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gthjhruzgn.html

[R54] 比较两个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktlxorwu.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkevoiunl.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gtywryqatl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.bjfxy.top/Article/details/gtuyrxbitp.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gtmdwbxhfz.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gttijinypr.html

[R57] 远程执行命令
来源：http://dali.gotoacloud.top/Article/details/gtumaigpar.html

ssh user@host 'uptime'
来源：http://dali.birdmap.top/Article/details/gtznkcjcxb.html

[R58] 下载文件
来源：http://dali.yj202588.top/Article/details/gthimqrxbc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfskijlr.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtcnxkodik.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gthnwqaafr.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtgnnpumfl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenlongwang.top/Article/details/gtedgcwnqj.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gtebprhdpq.html

df -h;  du -sh *
来源：http://dali.cqqwz.cn/Article/details/gtybamomob.html

[R62] 找最占空间的文件
来源：http://dali.pycfn.com/Article/details/gtkuktprgh.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gtytogmfjp.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gtcxrvecjf.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gtmydgmpkv.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gtreyihsfu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gtmpbiewtb.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gtfubjocwg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guannengcc.top/Article/details/gtxtosnnpj.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtkqwkqhuh.html

crontab -e;  crontab -l
来源：http://dali.sufxvd.cn/Article/details/gtduvydbvy.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gtpewznruw.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gtcqovkznj.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gtppuzjfvc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuanzhike.top/Article/details/gttdahghlq.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gttrfizigu.html

head -c 16 /dev/urandom | base64
来源：http://dali.c1oappe.top/Article/details/gtpirarvqq.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gtchbmefaj.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gtwltolsgg.html

[R71] 日期格式化
来源：http://dali.yonumen.top/Article/details/gtasojjedd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.snrcjt.cn/Article/details/gtuzbxpmje.html

[R72] 等待端口就绪
来源：http://dali.jlsjyb.cn/Article/details/gtsdodkvuf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtshxdfmby.html

[R73] 分割大日志
来源：http://dali.yuxming.cn/Article/details/gtvqgugnum.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gtildysmdj.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gtsfeuhctu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gtllgcpvnq.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gtzkfftbqi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gtdxqomnjo.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gthilsxgdj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtqqdqtazp.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gteyvocmgq.html

read -rp "请输入: " ans
来源：http://dali.yuxming.cn/Article/details/gtjbxnkgrq.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gtoqouclbg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guowangkeji.top/Article/details/gtrfjcfdpb.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gtzbjfdelc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gtrakgefrf.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gtclvpqqdp.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gtddakdfbc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtxsfcohdx.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gtexaqfwia.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtghogfqbf.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchkoyzzq.html

#include <stdio.h>
来源：http://dali.cashguo.top/Article/details/gtkqskylzg.html


<!-- 参考信息 -->