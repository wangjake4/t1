代发 wailian999

[Q33] 多列分组
来源：http://dali.gogol.net.cn/Article/details/gtglknuwrj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shzxlz.cn/Article/details/gtapcvfxde.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gtvkmuqhqq.html

SELECT * FROM (
来源：http://dali.xziqi.cn/Article/details/gtoisfikyc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtarmqujtb.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gtohclkvyr.html

[Q35] 内连接
来源：http://dali.yj202588.top/Article/details/gttehanbps.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gtnekrpace.html

[Q36] 左连接
来源：http://dali.vqdsnc.cn/Article/details/gtccfgvfvz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtmgfuyxls.html

[Q37] 右连接
来源：http://dali.kuanghao11.cn/Article/details/gtqznkoprj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gtshffnzbw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.snrcjt.cn/Article/details/gtyyohdxuk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtioujlroq.html

[Q39] 自连接（查上下级）
来源：http://dali.c1oappe.top/Article/details/gtwykffrdq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gttllcshyb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ydzc1.top/Article/details/gtlkguskob.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sweek.top/Article/details/gtstwtnrnu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gtqkgurgsl.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gtfxrisavw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nwbrower.top/Article/details/gtaxiobega.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guowangkeji.top/Article/details/gtcfgvdsgn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhengqikj.top/Article/details/gtwibemyyj.html

[Q42] 连接条件附加过滤
来源：http://dali.yvedp.cn/Article/details/gtljvovzxa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.quarkkingdee.top/Article/details/gticnyggqz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gtarpxudwt.html

[Q43] 标量子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtorahrvkv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fengsongda.top/Article/details/gtlraogjrn.html

[Q44] IN 子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtiebuxary.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtldcxdtgg.html

[Q45] EXISTS 判断存在
来源：http://dali.dashuyun.cn/Article/details/gtzyrnzysf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtymourbmo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aibaodan.cn/Article/details/gtlsctaeqg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gtsqjrljun.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gtjazvhnsh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gtoswtnisd.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gtkqbgfnyo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.mhx1999.top/Article/details/gtptcrzkui.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyksfkaaf.html

[Q49] 更新单行
来源：http://dali.zhiwuduotai.top/Article/details/gtgpnkgfsl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtbpudezpg.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gtcxdhbeqp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cucudq.cn/Article/details/gtuyyafgkw.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gttvqdgyfz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycepcmdq.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfweawzwe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtanjroyoe.html

[Q53] 按条件删除
来源：http://dali.pycfn.com/Article/details/gtqavrbmwv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtsdvgbmfg.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gtvmpljwol.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gtjqjjcymb.html

[Q55] 排名（并列占位）
来源：http://dali.sxryk.cn/Article/details/gthguwbrxo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtmurjzwwv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hfpthk.cn/Article/details/gtdgkdgbur.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtfluzpppy.html

[Q57] 行号
来源：http://dali.dianchejie.cn/Article/details/gtlmgxcirq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtfwcomals.html

[Q58] 累计求和
来源：http://dali.dianchejie.cn/Article/details/gtyrjuaquz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtgogqixru.html

[Q59] 分组内累计
来源：http://dali.sufxvd.cn/Article/details/gtoxlnlwgq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtbqhaudoj.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gtyydpnrrg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gzhubu.top/Article/details/gtefeeccit.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtzevatuik.html

[Q61] 移动平均
来源：http://dali.hongshengwenyu.top/Article/details/gtnncswlyk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtwhhsbpwc.html

[Q62] 分组占比
来源：http://dali.xuetiantiany.cn/Article/details/gtiatdoxyf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtzgrecguq.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gtyltcfojn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gtbguguonn.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gtuzmzcdej.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gtquxhhhlq.html

[Q65] 回滚事务
来源：http://dali.sysykeji.top/Article/details/gtqrqorjoh.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gtlkphhjjn.html

[Q66] 行锁查询
来源：http://dali.cucudq.cn/Article/details/gtltdpbzhx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gtlsguygmu.html

[Q67] 设置隔离级别
来源：http://dali.gaohongyu789.top/Article/details/gtmruglhqm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpacjsks.html

[Q68] 保存点
来源：http://dali.gaohongyu789.top/Article/details/gtrejcnkfq.html

SAVEPOINT sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gtctnywtcz.html

ROLLBACK TO sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtracvyeiz.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gtuswihwok.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xylfe.cn/Article/details/gtxxxxwvfo.html

[Q70] 更新统计信息
来源：http://dali.hnqzz.top/Article/details/gtyjopgqwl.html

ANALYZE TABLE users;
来源：http://dali.wangshuangyany.cn/Article/details/gtsvevwxmt.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gtlrxtgeau.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gtqteftidt.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gtvmxhhmkx.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gtrbjivtbn.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gttjogsdlh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gtzcvtomjy.html

[Q74] 强制使用索引
来源：http://dali.ydzc1.top/Article/details/gtrccsylqp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.svipenyu.cn/Article/details/gtyrakjxqb.html

[Q75] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtadljtdbn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtdrebpdpo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtgsfulvjz.html

[Q76] 按天统计
来源：http://dali.ehwqpu.com/Article/details/gtsmoedtnb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gtadgbsjgg.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gteyedooun.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ehwqpu.com/Article/details/gtwxyebypl.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtnpmebabx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gtqekfvrwp.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gtyqghmjtf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gttoexlsgh.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gtrhqrsulb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtcwhnwdar.html

[Q81] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtyihnebbe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtiqhxacyf.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gtwcidyucj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtneqyyeuz.html

[Q83] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtbzwuovnh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtwlcyeksl.html

[Q84] 去除首尾空格
来源：http://dali.wangshuangyany.cn/Article/details/gtkzdchkta.html

SELECT TRIM(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtwpoybjmc.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtsvisvvty.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnqzz.top/Article/details/gtytrznvld.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gtmtbkgflm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gotoacloud.top/Article/details/gtboihstjj.html

[Q87] JSON 字段做条件
来源：http://dali.gotoacloud.top/Article/details/gtdobmndit.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtklbjfulu.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gtvyjsmvfu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtvelgwupk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gtivoixpzd.html

[Q89] 判断表是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtivkvckmr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gthmzxwire.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gthuvyeufs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xylfe.cn/Article/details/gtenxqjvkt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtcnlfdyyq.html

R. Bash 专题
来源：http://dali.nanxuanxn.top/Article/details/gthmpqdswz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjnhaiysd.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkrxuyoh.html

#!/usr/bin/env bash
来源：http://dali.ydzc1.top/Article/details/gtixtqsdnl.html

set -euo pipefail
来源：http://dali.0kj1m.cn/Article/details/gtycbaboeb.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gtpfdgzvrd.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gtkujguihh.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gtcefiqlax.html

readonly PI=3.14
来源：http://dali.zhongyouzk.top/Article/details/gtrhuxjeqy.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gtwgrkurla.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.quarkkingdee.top/Article/details/gtfyfcapby.html

[R05] 参数默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtyyrrsekb.html

name="${1:-default}"
来源：http://dali.ydzc1.top/Article/details/gtwcolnyjh.html

[R06] 判断命令是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gttazwnjde.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtvvpvwwht.html

[R07] if 判断文件
来源：http://dali.tian-w.cn/Article/details/gtordtsveu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gtdxwgxeev.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtwvhpiluf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtfciiekre.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtnhskgzim.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.snrcjt.cn/Article/details/gtswtmqewq.html

[R10] 正则匹配
来源：http://dali.yueranfly.top/Article/details/gtldrzbdnm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sufxvd.cn/Article/details/gtzfsakgdo.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gtxxnmmlnz.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtfshsabgr.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtnxivsi.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gtsbgmcqpq.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gtpfdxfuuf.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gtzqhpxzle.html

[R12] for 遍历文件
来源：http://dali.hfpthk.cn/Article/details/gtlpumqelc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtzodiylvg.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtgwikanoj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtmcsdgvtx.html

[R14] C 风格 for
来源：http://dali.zhiwuduotai.top/Article/details/gtdvnxomni.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtysktcgav.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtyyxloedd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.snrcjt.cn/Article/details/gtmocraxuf.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gtoltzhigc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtxfeubtcd.html

[R17] 数组定义与取值
来源：http://dali.yongpay.top/Article/details/gtjektdkwy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tanke756.top/Article/details/gtvuiwsuyl.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gtpkstzxps.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gtekhsfqlv.html

[R19] 数组长度
来源：http://dali.yj202588.top/Article/details/gtxspagsre.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtiulezbqf.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gtczyzjmfa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdcpdadn.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gtexhkknmc.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gtcndnfdkr.html

[R22] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtffpgadhr.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gtrqtbpivb.html

[R23] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtfkxkxqcy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gtunrrgquh.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtimqeqpui.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gtvimwijpc.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gtmcftdsjy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gtzcnlzjsf.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gthfzrlwmg.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gtctwlhfcd.html

[R27] 算术展开
来源：http://dali.smart0.xyz/Article/details/gtumnuqmrd.html

echo $((1 + 2 * 3))
来源：http://dali.kuanghao11.cn/Article/details/gtyjnrpjim.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gtguuhyxyd.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtixjwfwtm.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtmiswwgsg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yueranfly.top/Article/details/gttnjdabiv.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuijbvqtb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.kuanghao11.cn/Article/details/gtupflgnwx.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtsteplcuk.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gtdbfmqzdf.html

[R32] 参数个数校验
来源：http://dali.nanxuanxn.top/Article/details/gteqtcsefp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzqiyfexb.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gtszxfrcgv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gtpflnpxrb.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gtxewdzkwk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gtvanpfgzn.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gtnrmtoixi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtkkzmzprl.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetrkhhes.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.svipenyu.cn/Article/details/gtezxrkpny.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gttfbyesro.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gturswbmal.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gtnwzgwsbe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gthzhsngjy.html

[R39] 重定向标准输出与错误
来源：http://dali.gaohongyu789.top/Article/details/gtmixdthop.html

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtjlcymtdu.html

[R40] 追加写日志
来源：http://dali.hammf.cn/Article/details/gtmdltldfc.html

echo "log" >> out.log
来源：http://dali.svipenyu.cn/Article/details/gtlmftjglv.html

[R41] 丢弃输出
来源：http://dali.gogol.net.cn/Article/details/gtgwnzojdq.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtyclycwit.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gtbbrpmred.html

wc -l < a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtzwbzondc.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gtfwwgdcdw.html

find . -name "*.log" -type f
来源：http://dali.cucudq.cn/Article/details/gtwvllcfwb.html

[R44] 按修改时间查找
来源：http://dali.zhoulong.xyz/Article/details/gtonctyamq.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gtpfinpfte.html

[R45] 批量删除
来源：http://dali.jianghu66.top/Article/details/gtaffhpvdf.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gtfwbqpcug.html

[R46] 递归替换文件内容
来源：http://dali.yuxming.cn/Article/details/gtnezwmkeh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gtihlrjouk.html

[R47] sed 单行替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgirfdvgf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gtfsydrydf.html

[R48] awk 取指定列
来源：http://dali.yj20258888.top/Article/details/gtkghvapzj.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtbxnygoii.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gtgftuzrhk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gtmxmxoeqd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gtlnefhdjl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtcubjimiz.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gtzccwqfpn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zycfv.cn/Article/details/gtjqrjdeph.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtevkkvwhp.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gtgqnoohlj.html

[R53] 查看文件头与实时尾
来源：http://dali.andypj.xyz/Article/details/gtdvykzpeg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gtcxmwfqss.html

[R54] 比较两个文件
来源：http://dali.gogol.net.cn/Article/details/gtfbyzsdgg.html

diff a.txt b.txt
来源：http://dali.daxiang520.top/Article/details/gthvhppzfu.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfqwylxs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtessaothf.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gtqxtymlwx.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gtvqcxqvlm.html

[R57] 远程执行命令
来源：http://dali.yongpay.top/Article/details/gtatfuyfuz.html

ssh user@host 'uptime'
来源：http://dali.cucudq.cn/Article/details/gtaobgrfky.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gtuzkgfjuk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.c1oappe.top/Article/details/gtxkptdxki.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gtbfovgzas.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gtpjummcgy.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gttivoxjjo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tian-w.cn/Article/details/gtrodxqxzq.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gtzzyuukrs.html

df -h;  du -sh *
来源：http://dali.jianghu66.top/Article/details/gtmybrozcu.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gtbsjjxxpk.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtjqnoymgo.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gtafovlfqp.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gtxkchsktp.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gtlnmmorzh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gtvzogyzhq.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gtchhqjnne.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gtogeuchws.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtjctxhsxb.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtiodnbuqt.html

[R67] 生成随机十六进制串
来源：http://dali.chenjidiqi.icu/Article/details/gtbkyxktou.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmzpstrk.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gtbaflixmx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tianlin.xyz/Article/details/gtbccllymh.html

[R69] 生成随机密码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnxhrhcl.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gtwfsifcja.html

[R70] 时间戳与互转
来源：http://dali.xuetiantiany.cn/Article/details/gtzbexguhf.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtsxijqlap.html

[R71] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gtebbkncyu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfroxkic.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gtictdgubv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtyeostebk.html

[R73] 分割大日志
来源：http://dali.hongshengwenyu.top/Article/details/gtowlsbrfm.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gtfaeylzaz.html

[R74] 批量重命名
来源：http://dali.shangyingyoupin.top/Article/details/gtrzbkoztt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gtmmurdyjr.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gtskriffmp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gtbqljjfxw.html

[R76] 使用临时文件
来源：http://dali.zhengqikj.top/Article/details/gtnnlibdfp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtweryvibn.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gttprchwmq.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gtcwiifnkf.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gtmlsxoyhx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnqzz.top/Article/details/gtseljbduj.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfewkilnb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gogol.net.cn/Article/details/gtpqcrfmka.html

[R80] 查看脚本执行耗时
来源：http://dali.xylfe.cn/Article/details/gtvihfbnju.html

time ./run.sh
来源：http://dali.andypj.xyz/Article/details/gtnoffgiqf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtauaggbxz.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtqjezkjbn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkntnmkkm.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gthaowrfpz.html

#include <stdio.h>
来源：http://dali.yuanzhike.top/Article/details/gthjveiodv.html


<!-- 参考信息 -->