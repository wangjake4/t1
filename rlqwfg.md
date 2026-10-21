代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuetiantiany.cn/Article/details/gtvialhqgz.html

) t WHERE rn = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtwmxdiwng.html

[Q35] 内连接
来源：http://dali.gzhubu.top/Article/details/gtmrxgyjpt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gtsvvqqjhf.html

[Q36] 左连接
来源：http://dali.zhiwuduotai.top/Article/details/gtbhxbprlb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtvkfdptau.html

[Q37] 右连接
来源：http://dali.cdnleiting.top/Article/details/gtqeazqucd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gtrmhgterp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gtcsgzbovz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gtshdboxoc.html

[Q39] 自连接（查上下级）
来源：http://dali.gotoacloud.top/Article/details/gtlxzvaomy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.0kj1m.cn/Article/details/gthfmhsfur.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtjatqbjmj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjhwbkwh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gtqvotzljh.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gtbpawxcys.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yanxiufei.cn/Article/details/gtzuwxdfpx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gtmuobnefi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.c1oappe.top/Article/details/gtpozttbvp.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gthdbgnuib.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtnabbpk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hammf.cn/Article/details/gtnxyauvdb.html

[Q43] 标量子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtttncixis.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gtlcpfnsqi.html

[Q44] IN 子查询
来源：http://dali.hnxiangtu.top/Article/details/gtknufubnv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhixingplan.top/Article/details/gtupxwnhqd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtpkvnpomf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gthxwazmlx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gtbotzyjae.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtqenyenag.html

[Q47] 与平均值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtyechtfzo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guowangkeji.top/Article/details/gtpqryzmvm.html

[Q48] CTE 公用表表达式
来源：http://dali.quarkkingdee.top/Article/details/gtqaidompv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aizwys.cn/Article/details/gtmgeuztho.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangdashe.top/Article/details/gtlhthazco.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gtkpnbzuio.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtennmkxoj.html

[Q50] 批量更新
来源：http://dali.jinqigfzy.top/Article/details/gtxnkyoqgt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtsyynbske.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gtjrqhzmli.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dianchejie.cn/Article/details/gtwakkimsa.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gtsoakjbap.html

DELETE FROM users WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gttbdvrqmg.html

[Q53] 按条件删除
来源：http://dali.ehwqpu.com/Article/details/gtptynpyyg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtpdxvtovl.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gtksjjysud.html

TRUNCATE TABLE logs;
来源：http://dali.gogol.net.cn/Article/details/gtqxgthqof.html

[Q55] 排名（并列占位）
来源：http://dali.shangyingyoupin.top/Article/details/gtkvkvnrpn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtwvyoemcy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.quarkkingdee.top/Article/details/gtjtimhpdt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtqiqtmtzg.html

[Q57] 行号
来源：http://dali.sufxvd.cn/Article/details/gtqfjmdhik.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gtxwnypyzl.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevtwyfzr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtipwqknbn.html

[Q59] 分组内累计
来源：http://dali.hywenlv.cn/Article/details/gthuyaahhr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtzsskqvam.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gtgadtpknt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.316326.xyz/Article/details/gtoprukpij.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtrdcabugb.html

[Q61] 移动平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzqzdnap.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkrsprwi.html

[Q62] 分组占比
来源：http://dali.ehwqpu.com/Article/details/gtnipkptpz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtxwmdvslj.html

[Q63] 开启事务
来源：http://dali.aizwys.cn/Article/details/gtnajvwtct.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gtidlnifdu.html

[Q64] 提交事务
来源：http://dali.zhengqikj.top/Article/details/gtxnavwxzz.html

COMMIT;
来源：http://dali.yueranfly.top/Article/details/gtxxgkwmes.html

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahgadvdu.html

ROLLBACK;
来源：http://dali.gogol.net.cn/Article/details/gtqfzgkbvh.html

[Q66] 行锁查询
来源：http://dali.yonumen.top/Article/details/gtkomztzli.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gtesncujyt.html

[Q67] 设置隔离级别
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyeqykxnd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gtgrraaawp.html

[Q68] 保存点
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjhzbpwd.html

SAVEPOINT sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtipgvhqkz.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtajeiwbph.html

[Q69] 查看执行计划
来源：http://dali.cdnleiting.top/Article/details/gtwilmiipb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gtzauxecij.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gtvbadnash.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtbwczcldy.html

[Q71] 查看建表语句
来源：http://dali.tian-w.cn/Article/details/gtmypbupsx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gtqvpoaobz.html

[Q72] 查看索引
来源：http://dali.xziqi.cn/Article/details/gtwqqrmszo.html

SHOW INDEX FROM users;
来源：http://dali.sysykeji.top/Article/details/gtximzcyrd.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gtpoupeppz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gtpnkgfcwg.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtbruhtkdm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shzxlz.cn/Article/details/gtggctuiwg.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtbyxbkkvi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtpilvzvfj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gtlnwrasss.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gtecagsvqo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.havefunace.top/Article/details/gtrnfwzpio.html

[Q77] 时间加减
来源：http://dali.pengpengdd.cyou/Article/details/gtnywhcdtn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gttclnaobh.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gtpveinjkl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtwafnrcbf.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtafvlmdks.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jyoumei.cn/Article/details/gtwiyzjgfz.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gtxlsqaqwy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtfydhjgkj.html

[Q81] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gtiypfueib.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtknrpfoab.html

[Q82] 字符长度与字节长度
来源：http://dali.aibaodan.cn/Article/details/gttgbfxiaw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtuibjgzvu.html

[Q83] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtristgvbi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtztvzohgr.html

[Q84] 去除首尾空格
来源：http://dali.nwbrower.top/Article/details/gtxbspceck.html

SELECT TRIM(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtsowsdnwb.html

[Q85] 数值取整
来源：http://dali.hnxiangtu.top/Article/details/gtogkogxei.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.havefunace.top/Article/details/gtqatxnwap.html

[Q86] 读取 JSON 字段
来源：http://dali.sweek.top/Article/details/gtokgwhqor.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gtvvebpeeg.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gtnulychtz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuanzx.com/Article/details/gtxhsqohvw.html

[Q88] 行转列（条件聚合）
来源：http://dali.sweek.top/Article/details/gtmyofecyj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gtpdsgrgtu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gtlibhtmpa.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gtmtuhsskf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gtoahdjsfh.html

[Q90] 生成序号列
来源：http://dali.gotoacloud.top/Article/details/gtwefxtubx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gtqeflkhad.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwohxjzvo.html

R. Bash 专题
来源：http://dali.316326.xyz/Article/details/gteeuxurdd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtuetoajgv.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gthggdrfsy.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gttnmlwocw.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gtfuunlsiv.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gtyrpjpjni.html

name="Tom"; echo "$name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotrldtwr.html

[R03] 只读变量
来源：http://dali.aibaodan.cn/Article/details/gtgyvamjpd.html

readonly PI=3.14
来源：http://dali.kuanghao11.cn/Article/details/gtmbzaleep.html

[R04] 位置参数
来源：http://dali.yonumen.top/Article/details/gtsrukijch.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gtmwetcqvt.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gtcdrigocu.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gtfjeykfox.html

[R06] 判断命令是否存在
来源：http://dali.daxiang520.top/Article/details/gtjzsptzee.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtfyfdnvjf.html

[R07] if 判断文件
来源：http://dali.gogol.net.cn/Article/details/gthymvazcw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gthzxusxqb.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gtiichbmvv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gtzgzasbil.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gtwxukvikn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtsxqjeljg.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gtmdvtgfus.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvknoehbo.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhyfqgyd.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gtlqqcdqgd.html

start) echo "启动" ;;
来源：http://dali.gzhubu.top/Article/details/gtbbwyjjnk.html

stop)  echo "停止" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugjnbcqn.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gtsgbqtyzh.html

esac
来源：http://dali.hnxiangtu.top/Article/details/gtbxfiecry.html

[R12] for 遍历文件
来源：http://dali.cucudq.cn/Article/details/gtgvkxeekr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gtbkonxfsq.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gtlsokbbnk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtmjlfgvuu.html

[R14] C 风格 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdomjbftt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtvldpyxao.html

[R15] while 逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtizcbljqs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gtwxxazcgc.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gtlrwxnyik.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtauobaguv.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gtcumocpuu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xziqi.cn/Article/details/gtalyoktwc.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gtnrirpajz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gtqdwybxrb.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtjrilgvwj.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gthgvkxhpf.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxoeeyfq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guowangkeji.top/Article/details/gteqiknduv.html

[R21] 字符串长度
来源：http://dali.yueranfly.top/Article/details/gtfclakieq.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gtmbhtezcn.html

[R22] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtzgejobws.html

echo "${s:0:5}"
来源：http://dali.ehwqpu.com/Article/details/gtjlllzhsb.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtyigteghb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenlongwang.top/Article/details/gtbydcvvhx.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtzhvhjfdn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gzhubu.top/Article/details/gtvbelzzyw.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gtqpkggslq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gtdgpvmxlv.html

[R26] 命令替换
来源：http://dali.ivvv.top/Article/details/gteijobnpn.html

now=$(date +%F); echo "$now"
来源：http://dali.tian-w.cn/Article/details/gtawerpfiw.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gtxtbpfozk.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gtjhcndyqh.html

[R28] 浮点运算
来源：http://dali.andypj.xyz/Article/details/gttyigvffv.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gtoajjfzdr.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtpoooqvnq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gttidlpwwo.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxdgvfkv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gtdahpkqcy.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gtunbxokar.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gtlvapyfbs.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gtwldqntxv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gttmtmagik.html

[R33] 捕获错误并提示行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjziabel.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtsylyzfdf.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gtjumimnlo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtyqeybtrq.html

[R35] 后台执行并等待
来源：http://dali.havefunace.top/Article/details/gtipzuofwg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xziqi.cn/Article/details/gtagnpgvxb.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gtactiexom.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gtjyjqfnhq.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gthibknjkl.html

files=$(ls -1)
来源：http://dali.yj20258888.top/Article/details/gtnkhbzgeb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gtepzqzkyy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtxgkmboiq.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuuymonl.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtihvdnblg.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gtyxlahjuq.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gtfhlbvydd.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gtwfnbawrz.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gtpyeylmpv.html

[R42] 输入重定向
来源：http://dali.yongpay.top/Article/details/gtnhxqbnyu.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gtfkxucenv.html

[R43] 按名字查找文件
来源：http://dali.ehwqpu.com/Article/details/gtkkbdteli.html

find . -name "*.log" -type f
来源：http://dali.316326.xyz/Article/details/gtaobsetnh.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gtacifcwti.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtnntkxbaw.html

[R45] 批量删除
来源：http://dali.xuetiantiany.cn/Article/details/gthzktzmeg.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gtcqcxedqk.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gtejsxemys.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hywenlv.cn/Article/details/gtllxvoigx.html

[R47] sed 单行替换
来源：http://dali.tanke756.top/Article/details/gtpqgeccvn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gttsisaprp.html

[R48] awk 取指定列
来源：http://dali.ybcxt.top/Article/details/gtxdjlfave.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtehtspakr.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gtspqadcsl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhoulong.xyz/Article/details/gtgtunanct.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gtxntnpunh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtvnrbckxh.html

[R51] 排序去重取前几
来源：http://dali.nanxinkj.top/Article/details/gtzjzovtsh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj202588.top/Article/details/gtgpgpqzzf.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gtaowshqfc.html

wc -l a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtikdgcipo.html

[R53] 查看文件头与实时尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmkvsafy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gtkkycaztk.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gtgrwjoafg.html

diff a.txt b.txt
来源：http://dali.tanke756.top/Article/details/gtvoinqkvw.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gtmzkomrua.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenzaomai.com/Article/details/gtspbmhliq.html

[R56] 远程拷贝
来源：http://dali.yangfankeji.com/Article/details/gtwxugprsf.html

scp file user@host:/path/
来源：http://dali.yj202588.top/Article/details/gtsabnepgp.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjfghyim.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gtyzxrtuey.html

[R58] 下载文件
来源：http://dali.aibaodan.cn/Article/details/gtezulbsfc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwryniiz.html

[R59] 发 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtimphabgm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gtbjbhwlpw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtqaqlogki.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gtubluuvzp.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gtobbetkmu.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gthjkqpcfl.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gtkylylhlf.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gtzpdngyez.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnhfhvbj.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gtcxogzzib.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gtfmlgbdov.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gtxveluuol.html

[R65] 查看端口占用
来源：http://dali.gogol.net.cn/Article/details/gtpnxdsxda.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gtvimfaerv.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtgooooahv.html

crontab -e;  crontab -l
来源：http://dali.zdqjudy.top/Article/details/gttzqjgbxq.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gtykpnacnp.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gtotxbdoek.html

[R68] 计算文件校验值
来源：http://dali.yj20258.top/Article/details/gttqqiddur.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dianchejie.cn/Article/details/gtajxgbhvu.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gtrdzhbeeo.html

head -c 16 /dev/urandom | base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjqimuep.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfxgolij.html

date +%s;  date -d @1700000000
来源：http://dali.yuanzhike.top/Article/details/gtdrxsvssl.html

[R71] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtbzwqxibz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gtkjvqktol.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gtnbcqpipr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtsvrswpgg.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gtvsrvuidw.html

split -l 1000 big.log part_
来源：http://dali.dashuyun.cn/Article/details/gtbyhgxaio.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gtlhnymahg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtiejvheca.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gtacyhlkou.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gtxevezbpm.html

[R76] 使用临时文件
来源：http://dali.kuanghao11.cn/Article/details/gtoexpmdzc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtpjhpukgn.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gtxgfljbnh.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gthrifnvge.html

[R78] 交互式菜单
来源：http://dali.dashuyun.cn/Article/details/gtzvmkhixy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gtjguzusti.html

[R79] 解析命令行选项
来源：http://dali.hywenlv.cn/Article/details/gtielsfzkg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gtciufltln.html

[R80] 查看脚本执行耗时
来源：http://dali.tianlin.xyz/Article/details/gtgivczefw.html

time ./run.sh
来源：http://dali.xinyue.icu/Article/details/gtmlupanrm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtknprwbhs.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gtztglrwxr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtawhfgjgb.html

[S01] C：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuxxczzt.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gtcjxzbord.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gtdiaksmjr.html

[S02] C：变量与格式化输出
来源：http://dali.meibo888.top/Article/details/gtnsjdxwhi.html

int a = 10; printf("%d\n", a);
来源：http://dali.shuidangran.top/Article/details/gthsloweab.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrboyvxtj.html


<!-- 参考信息 -->