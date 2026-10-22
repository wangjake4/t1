代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtkbrefoim.html

[Q30] 分组统计
来源：http://dali.xinyue.icu/Article/details/gtljyheujm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtdssrfuyq.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gtnlcuseqw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenzaomai.com/Article/details/gtwukwtjyg.html

[Q32] 分组拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtlbumougp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtvmoxlqcm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gtjiuoifpo.html

[Q33] 多列分组
来源：http://dali.jiagoushi.top/Article/details/gtqjswxamv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gtgvhoawfz.html

[Q34] 每组取第一条
来源：http://dali.hywenlv.cn/Article/details/gtrffdzjbj.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtayojdbzh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhaomingkeji.xyz/Article/details/gthygdhcvc.html

) t WHERE rn = 1;
来源：http://dali.yonumen.top/Article/details/gtdkvbpldr.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gthdbrutdc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtjchptbuh.html

[Q36] 左连接
来源：http://dali.zycfv.cn/Article/details/gtyncgnavj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gthnxnbecc.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gtlnrmvyku.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cucudq.cn/Article/details/gtxdpvjgbv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gthqyydkvk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gtvgqdxqzm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfosmuhsu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gtzfvozyzq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.meibo888.top/Article/details/gtxzbzjzhm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxghzuzv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yueranfly.top/Article/details/gtalbdcqfe.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gthfhefqud.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gtxwbelxns.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gtlbvpeuax.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtjiywmhgh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gtmynftavo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gtzejnncsm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuanzx.com/Article/details/gtbqkxhewx.html

[Q43] 标量子查询
来源：http://dali.cheryme.top/Article/details/gtxspqyiap.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnqzz.top/Article/details/gtpxyncdht.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtsvtvwazq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gtbvagcgxp.html

[Q45] EXISTS 判断存在
来源：http://dali.sxryk.cn/Article/details/gthhhqxobi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtsemaapaj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gtlhkypdha.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdpwcstc.html

[Q47] 与平均值比较
来源：http://dali.hnqzz.top/Article/details/gtefnvpopu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gtyjmkcqxe.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtonbmorsd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturjvowkv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gtagzvtrib.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gtgsjghzyk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gttcyvsaly.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gtukwqqday.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtxovvvpns.html

[Q51] 用子查询更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvsmldwy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslehfrei.html

[Q52] 删除指定行
来源：http://dali.yongpay.top/Article/details/gtxdguuxwm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gtubrciwek.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gtldgxaahi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtyrzasyjh.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtvsaeprio.html

TRUNCATE TABLE logs;
来源：http://dali.redwolf501.top/Article/details/gtcqbrjoem.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gtqukwwwru.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtrifibigm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.andypj.xyz/Article/details/gtyecsddwu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtvremtstt.html

[Q57] 行号
来源：http://dali.0kj1m.cn/Article/details/gtwwcnzpki.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtnsbsxfyw.html

[Q58] 累计求和
来源：http://dali.zdqjudy.top/Article/details/gtwocacmev.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtixzvipsi.html

[Q59] 分组内累计
来源：http://dali.jinqigfzy.top/Article/details/gtfavtssbn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtpvgpnvag.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtderslolb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gtuqqimvvh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtqpwjckbj.html

[Q61] 移动平均
来源：http://dali.zhongyouzk.top/Article/details/gtgwfgqjtt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gttjjhtxkd.html

[Q62] 分组占比
来源：http://dali.iojbl.cn/Article/details/gtlucskcge.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtlmlnopsv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gtejvhcgxg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gtwlpufrer.html

[Q64] 提交事务
来源：http://dali.xuetiantiany.cn/Article/details/gtsgxxefii.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gtuvdlwrnx.html

[Q65] 回滚事务
来源：http://dali.chenjidiqi.icu/Article/details/gtsarayrhg.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gtgurgykfq.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtkizgplvs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.0kj1m.cn/Article/details/gtdeyxxlso.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gtnfxhgqqn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkhsymak.html

[Q68] 保存点
来源：http://dali.daxiang520.top/Article/details/gtglawxuay.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtbdpfmbqc.html

ROLLBACK TO sp1;
来源：http://dali.meibo888.top/Article/details/gtemswdand.html

[Q69] 查看执行计划
来源：http://dali.jiagoushi.top/Article/details/gtvcwbhccc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gtbphgnykh.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gtxjmjgvoz.html

ANALYZE TABLE users;
来源：http://dali.shuidangran.top/Article/details/gtdneqjahs.html

[Q71] 查看建表语句
来源：http://dali.jinghuilouyu.cn/Article/details/gttrzlsrlt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cheryme.top/Article/details/gtxvnsekob.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gtxfyfbtsp.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkypwswsw.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gtrkpxtmwc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtgytwawwa.html

[Q74] 强制使用索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffgiujtw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkryattdx.html

[Q75] 日期格式化
来源：http://dali.cashguo.top/Article/details/gtfazysnxo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gttczabvsq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jyoumei.cn/Article/details/gtmjeyuvfp.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gtnprloeaw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gtzqxvkxzm.html

[Q77] 时间加减
来源：http://dali.wangshuangyany.cn/Article/details/gtkpigdrgc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gtuyueuign.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gttzhknxso.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gtiqmnlhjg.html

[Q79] 字符串拼接
来源：http://dali.cashguo.top/Article/details/gtphzldtdp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhiwuduotai.top/Article/details/gtcwifutaa.html

[Q80] 字符串截取
来源：http://dali.jlsjyb.cn/Article/details/gtpcicogtr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtkfbzxksz.html

[Q81] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtvdilpzaq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtogvpzjlg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gtwviqopcl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtlujpaoqr.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gthvgcqags.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtbzioneig.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gteonsfxkx.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtflbcsmze.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gtbwkiotmc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigufen.top/Article/details/gtxuvhioxc.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gtdpwictrs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gteaqjmfxe.html

[Q87] JSON 字段做条件
来源：http://dali.vqdsnc.cn/Article/details/gtvnvcvrcp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guannengcc.top/Article/details/gtcgxfkwqi.html

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gtetsdnvga.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gthhhkmium.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtdjczpcjz.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjazydmv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sysykeji.top/Article/details/gtlhryvgie.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gtbptkrock.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gtyydwfcip.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtpnobprxv.html

R. Bash 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtgasqzfht.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtuvmifbmi.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtvcvxhvrd.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gtuwahiwnw.html

set -euo pipefail
来源：http://dali.jlsjyb.cn/Article/details/gthwvwzqbb.html

[R02] 变量赋值与使用
来源：http://dali.zhixingplan.top/Article/details/gtigioyruc.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gtopsfcbvp.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gtjbuahtzs.html

readonly PI=3.14
来源：http://dali.jinqigufen.top/Article/details/gtkucfckpn.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gtvmycxppc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gtdxsuowox.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gtbpvpaoxs.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gtdofeuxgk.html

[R06] 判断命令是否存在
来源：http://dali.jqgfzy.top/Article/details/gtsaryghtu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gthqfterjv.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmysvqdck.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gtkrbxpbhn.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gtbcaasgfx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuusfmbx.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtwffvhxan.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.snrcjt.cn/Article/details/gtuwjlzrpj.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gtwtlqcvjd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gtroifsucs.html

[R11] case 多分支
来源：http://dali.jyoumei.cn/Article/details/gtccrsakbi.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gtehpxlcne.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtvwahtssi.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gtphskiwbq.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gtpqasriiv.html

esac
来源：http://dali.zhiwuduotai.top/Article/details/gtebewmixn.html

[R12] for 遍历文件
来源：http://dali.snrcjt.cn/Article/details/gtmgaykyjm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnxiangtu.top/Article/details/gtrhjjtjie.html

[R13] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gtegjwusuq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtxaszzboz.html

[R14] C 风格 for
来源：http://dali.svipenyu.cn/Article/details/gtugcndwye.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtgoaiegrs.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtsmjranpq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gtkldrabzq.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gtqtxummbv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtmxjtryub.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gtuqzbpijg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gtoxuxwzzp.html

[R18] 遍历数组
来源：http://dali.hongshengwenyu.top/Article/details/gttwloswsk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuanzx.com/Article/details/gtjsyoqxlg.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtdevdffxe.html

echo "${#arr[@]}"
来源：http://dali.xinyue.icu/Article/details/gtxgvxryup.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gtafiffbmo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gtoknedlce.html

[R21] 字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkdesqvw.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhzsbjnb.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtesolcqwk.html

echo "${s:0:5}"
来源：http://dali.xziqi.cn/Article/details/gtgrmyetqu.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtbqovrbmg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tianlin.xyz/Article/details/gtteldvkeh.html

[R24] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtypkccodd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtswbwaxft.html

[R25] 去后缀 / 去前缀
来源：http://dali.birdmap.top/Article/details/gttpukzcom.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlxiggsc.html

[R26] 命令替换
来源：http://dali.ehwqpu.com/Article/details/gtknewucav.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gtkvuzhkdg.html

[R27] 算术展开
来源：http://dali.vqdsnc.cn/Article/details/gtkjotlwbh.html

echo $((1 + 2 * 3))
来源：http://dali.yuanzhike.top/Article/details/gtoekoiwqq.html

[R28] 浮点运算
来源：http://dali.andypj.xyz/Article/details/gtyogageax.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gtnwvlwcmg.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtfplqeqjx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndzbamsm.html

[R30] 函数返回状态码
来源：http://dali.ppjwa.cn/Article/details/gtzhvknkfu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlyokkiog.html

[R31] 局部变量
来源：http://dali.jiagoushi.top/Article/details/gtytveezgp.html

f() { local x=1; echo "$x"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirajmjmx.html

[R32] 参数个数校验
来源：http://dali.yonumen.top/Article/details/gtjeftdook.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtslhfzins.html

[R33] 捕获错误并提示行号
来源：http://dali.yuanzhike.top/Article/details/gtfgbtqhvp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pycfn.com/Article/details/gtgkttlhzv.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gtaoevarue.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtyzdgwjtw.html

[R35] 后台执行并等待
来源：http://dali.cqqwz.cn/Article/details/gtmyelzxes.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gtejzprpfb.html

[R36] 并发执行多个任务
来源：http://dali.yj20258.top/Article/details/gtywwohden.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtljyvbddl.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtzegsvdzm.html

files=$(ls -1)
来源：http://dali.jianghu66.top/Article/details/gtxeedtljy.html

[R38] 管道串联
来源：http://dali.sweek.top/Article/details/gtrpifhmjw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gtvlxyenve.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gtwoqhgqcg.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtiynehoqg.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gtojztsexa.html

echo "log" >> out.log
来源：http://dali.vqdsnc.cn/Article/details/gthpsfvtik.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gtsivsfwvh.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gtqyyerwhp.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gtiriztjhu.html

wc -l < a.txt
来源：http://dali.316326.xyz/Article/details/gtxkvcvpfk.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gtrdbhpujy.html

find . -name "*.log" -type f
来源：http://dali.daxiang520.top/Article/details/gturtnnhei.html

[R44] 按修改时间查找
来源：http://dali.hfpthk.cn/Article/details/gtuisrrlue.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gtjvgeqzbd.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gtieqnprzp.html

find . -name "*.tmp" -delete
来源：http://dali.pengpengdd.cyou/Article/details/gtxjqfgtef.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gtiymwnuoh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gtersigowz.html

[R47] sed 单行替换
来源：http://dali.feifeiyinyue.top/Article/details/gtsbzfmqct.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtvbrwecsk.html

[R48] awk 取指定列
来源：http://dali.yongpay.top/Article/details/gtjpcvssgm.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtcuaaehxz.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gtcfbbkkpf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gtjrpbysgz.html

[R50] awk 求和
来源：http://dali.kuanghao11.cn/Article/details/gtmmawughz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gthznvqqdt.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gtdjlwcfuv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gtilkqyixm.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gtbnyvmvij.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtxljpsmqb.html

[R53] 查看文件头与实时尾
来源：http://dali.feifeiyinyue.top/Article/details/gtdgslpbid.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gterfcpqcp.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gtczodehqj.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtdreezprr.html

[R55] 压缩与解压
来源：http://dali.316326.xyz/Article/details/gtzegcutei.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gterrhngok.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gtzruteiot.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gtofsktnlw.html

[R57] 远程执行命令
来源：http://dali.nwbrower.top/Article/details/gtrpokxjqg.html

ssh user@host 'uptime'
来源：http://dali.wangdashe.top/Article/details/gtktrpmvsp.html

[R58] 下载文件
来源：http://dali.jinqigufen.top/Article/details/gtogtxfvjl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gttsfbteus.html

[R59] 发 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gtllhjdiic.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258888.top/Article/details/gtrhcfydti.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtkncmcjqx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnqzz.top/Article/details/gtlxlhinnu.html

[R61] 磁盘占用
来源：http://dali.cqqwz.cn/Article/details/gtezfjuufw.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gtkotpegte.html

[R62] 找最占空间的文件
来源：http://dali.xuetiantiany.cn/Article/details/gterfzbjgx.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gtxtedjxuk.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gtztozoqbx.html

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gtwrybcsih.html

[R64] 结束进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpgiglkq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gtbgyavnsz.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gtiuycrviq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gtskecrxtl.html

[R66] 定时任务
来源：http://dali.havefunace.top/Article/details/gtoccvhtqh.html

crontab -e;  crontab -l
来源：http://dali.jiagoushi.top/Article/details/gtxrxexguu.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gtjnxnljlr.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gtujtetdjh.html

[R68] 计算文件校验值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfluvdjue.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gtwjkzdjcj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gtztgkwafo.html

head -c 16 /dev/urandom | base64
来源：http://dali.c1oappe.top/Article/details/gtzjuhfezl.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gtagudzdwd.html

date +%s;  date -d @1700000000
来源：http://dali.yuanzhike.top/Article/details/gtvslxfgjn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtqdfkttxu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cucudq.cn/Article/details/gtdrxjnaum.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gtgxsbpusb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtzytenjil.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtbpasypjw.html

split -l 1000 big.log part_
来源：http://dali.zhongyouzk.top/Article/details/gtabpjfjku.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtsqlikwvc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gtrcitpiva.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gtejiuzqvs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gtrqpqjdql.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtameqgday.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbeowkpc.html

[R77] 读取用户输入
来源：http://dali.sweek.top/Article/details/gtxmcvicgt.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gtueckvabk.html

[R78] 交互式菜单
来源：http://dali.daxiang520.top/Article/details/gthycilhyd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gtvzvtekex.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gtavhmosuf.html


<!-- 参考信息 -->