代发 wailian999

[Q33] 多列分组
来源：http://dali.jqgufenzy.top/Article/details/gt2nogezehb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhiwuduotai.top/Article/details/gt2opokmnam.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gt2eoazhahl.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gt2btwwcpqk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pengpengdd.cyou/Article/details/gt2akarkite.html

) t WHERE rn = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mianbdqc.html

[Q35] 内连接
来源：http://dali.yongpay.top/Article/details/gt2lcejxjsi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gt2uyepkzsc.html

[Q36] 左连接
来源：http://dali.yongpay.top/Article/details/gt2gemfheip.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gt2jkwmebyk.html

[Q37] 右连接
来源：http://dali.yj20258888.top/Article/details/gt2hvnrzhwm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.haohaochexian.top/Article/details/gt2gkonxood.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.meibo888.top/Article/details/gt2rxbsjphj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmtwugre.html

[Q39] 自连接（查上下级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhqdriro.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gt2xljgbsmx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gt2htmmfcci.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxuanxn.top/Article/details/gt2cqfzfoog.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yanxiufei.cn/Article/details/gt2ltshuziu.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gt2xewtcyja.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.smart0.xyz/Article/details/gt2plshqqcd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gt2jjkcrxmh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxinkj.top/Article/details/gt2gxqjcrac.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2sjajkygo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gt2jxwzmznb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gt2jiwpubfq.html

[Q43] 标量子查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2avkasndi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yvedp.cn/Article/details/gt2rqedvxps.html

[Q44] IN 子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmgbgdzu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ehwqpu.com/Article/details/gt2alkrllpc.html

[Q45] EXISTS 判断存在
来源：http://dali.ybcxt.top/Article/details/gt2lqiaicca.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gt2enamtklz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shuidangran.top/Article/details/gt2qdpslsjh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gt2slbajxym.html

[Q47] 与平均值比较
来源：http://dali.yuxming.cn/Article/details/gt2wvdxbubx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhpqquel.html

[Q48] CTE 公用表表达式
来源：http://dali.aibaodan.cn/Article/details/gt2awwujekd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.redwolf501.top/Article/details/gt2uydjgexq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cashguo.top/Article/details/gt2gfuecutj.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gt2bvohogcv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gt2esjwcmmk.html

[Q50] 批量更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2femdpsvc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gt2wlfudwdn.html

[Q51] 用子查询更新
来源：http://dali.yueranfly.top/Article/details/gt2nysyspnn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gt2ydrxitxh.html

[Q52] 删除指定行
来源：http://dali.yonumen.top/Article/details/gt2ihvojhzi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gt2tbwshysf.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gt2aaeendzq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tianlin.xyz/Article/details/gt2gifwfwer.html

[Q54] 清空表
来源：http://dali.zhoulong.xyz/Article/details/gt2coilrobg.html

TRUNCATE TABLE logs;
来源：http://dali.jiagoushi.top/Article/details/gt2veebctrc.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gt2hpqswzlb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sxryk.cn/Article/details/gt2uujhejor.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gt2unbxpkvg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gt2rxatuowl.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gt2ojzuflfk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2pmfsbuwp.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gt2ggbtmhxj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2vbkjffle.html

[Q59] 分组内累计
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtckqpph.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2redolkah.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gt2rthztfrh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gt2wjawlwke.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2cqfqehhh.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gt2hyctlscg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2itmskhdf.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gt2lxxfeytc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofkkopbz.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gt2ckspjafv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hfpthk.cn/Article/details/gt2azrridfx.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gt2ehctimlo.html

COMMIT;
来源：http://dali.yj20258.top/Article/details/gt2ysypzvfw.html

[Q65] 回滚事务
来源：http://dali.guowangkeji.top/Article/details/gt2fgtnumso.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gt2vjlbxjii.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gt2nqecvxmj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gt2vbljqbhy.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uryzgcvm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuetiantiany.cn/Article/details/gt2lyfrcxza.html

[Q68] 保存点
来源：http://dali.xziqi.cn/Article/details/gt2ojjhaxlm.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gt2lrwjuvkg.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gt2jsbbdhyx.html

[Q69] 查看执行计划
来源：http://dali.guannengcc.top/Article/details/gt2zjxxutcv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlabxasz.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gt2dwpyaflh.html

ANALYZE TABLE users;
来源：http://dali.cdnleiting.top/Article/details/gt2sxdcnxll.html

[Q71] 查看建表语句
来源：http://dali.meibo888.top/Article/details/gt2jdldubbu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guowangkeji.top/Article/details/gt2rbpqlvak.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gt2jyexsfzi.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2mifzhszv.html

[Q73] 查看表状态
来源：http://dali.hywenlv.cn/Article/details/gt2dynnviwz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.meibo888.top/Article/details/gt2dmnvlabm.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gt2sbuobqiz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guannengcc.top/Article/details/gt2ddzsqkuu.html

[Q75] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gt2reeljcyq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2napqjtaz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gt2zwqqgrjk.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gt2gpfkwmma.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gt2mvrbzidp.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gt2qhsrbglr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gt2zzwyprdz.html

[Q78] 当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2njtwuiyi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gt2oxigiqee.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gt2knsxotww.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gt2yesdyygr.html

[Q80] 字符串截取
来源：http://dali.snrcjt.cn/Article/details/gt2lcimxqci.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2rbywmddz.html

[Q81] 字符串替换
来源：http://dali.hammf.cn/Article/details/gt2fzmpdriq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2ykfjuswc.html

[Q82] 字符长度与字节长度
来源：http://dali.aizwys.cn/Article/details/gt2bfixzkwf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2wphzrxvl.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gt2zknuugtj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2iknkxwxm.html

[Q84] 去除首尾空格
来源：http://dali.guowangkeji.top/Article/details/gt2ddnxwdde.html

SELECT TRIM(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2tbeymefv.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gt2zybdelhh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.c1oappe.top/Article/details/gt2jilrgecl.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gt2mvmhtsya.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cashguo.top/Article/details/gt2rhsmagry.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hkfiglvk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gt2xnioqqhm.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gt2ainwkmvi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sweek.top/Article/details/gt2grzoaoyu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2esazxemy.html

[Q89] 判断表是否存在
来源：http://dali.tian-w.cn/Article/details/gt2vfjfzvjp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj202588.top/Article/details/gt2ticjjcfq.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gt2svmcyjzs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gt2kjnyygqm.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2kqzcnqqa.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gt2ddzkarwv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2mfkubplm.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gt2tsvwtkdj.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gt2upsztkcc.html

set -euo pipefail
来源：http://dali.jinqigufen.top/Article/details/gt2cwscakjt.html

[R02] 变量赋值与使用
来源：http://dali.wangdashe.top/Article/details/gt2oilmalny.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gt2hfrzahjo.html

[R03] 只读变量
来源：http://dali.ivvv.top/Article/details/gt2shfzybhr.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gt2dmkbxrqn.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gt2cbquattn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dcxhgbvr.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gt2tqulauvn.html

name="${1:-default}"
来源：http://dali.jinqigfzy.top/Article/details/gt2mdlaqane.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gt2nhbbnzej.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gt2paqkgikw.html

[R07] if 判断文件
来源：http://dali.chenlongwang.top/Article/details/gt2ztczejjq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2emqunnfw.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gt2jlipnqcz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mngfqqqj.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gt2zszsfqiz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2xgryxexe.html

[R10] 正则匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2ofebtmpe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yanxiufei.cn/Article/details/gt2dagvflde.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gt2reeasukn.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gt2rfobrfuf.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2pkzwnttq.html

stop)  echo "停止" ;;
来源：http://dali.xuanzx.com/Article/details/gt2wzuxdveu.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2rzaxzhfa.html

esac
来源：http://dali.aibaodan.cn/Article/details/gt2hchhrjaz.html

[R12] for 遍历文件
来源：http://dali.yanxiufei.cn/Article/details/gt2eiezharv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xziqi.cn/Article/details/gt2lsxbdzgk.html

[R13] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gt2msmavmqf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gt2bvxiiknd.html

[R14] C 风格 for
来源：http://dali.svipenyu.cn/Article/details/gt2wgwsgotr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gt2skuyyuqx.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2psqqhjoj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.redwolf501.top/Article/details/gt2urwwqppe.html

[R16] until 等待条件
来源：http://dali.jqgufenzy.top/Article/details/gt2exskzspd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gt2ukaujscu.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gt2gtmknknm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gt2wxpjfzeo.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gt2xddxhqpb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gt2cwpiosrx.html

[R19] 数组长度
来源：http://dali.yj20258888.top/Article/details/gt2ggbpkkxy.html

echo "${#arr[@]}"
来源：http://dali.ydzc1.top/Article/details/gt2ldkfwrhu.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixsixhkb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gt2suksqytx.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gt2pckhelte.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gt2bcmizlsn.html

[R22] 截取子串
来源：http://dali.sweek.top/Article/details/gt2hrhlbxxo.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gt2rshpiwwz.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gt2fmoyudzn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gt2sbpqvfti.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gt2ugrsymyy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ppjwa.cn/Article/details/gt2nwznvckz.html

[R25] 去后缀 / 去前缀
来源：http://dali.fengsongda.top/Article/details/gt2wnntqikh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.meibo888.top/Article/details/gt2rhvbvtor.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gt2mgcmbbni.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gt2jwguwjso.html

[R27] 算术展开
来源：http://dali.fzhhl.top/Article/details/gt2dyzqxiaz.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gt2kazedqhs.html

[R28] 浮点运算
来源：http://dali.chenlongwang.top/Article/details/gt2crzigzxo.html

echo "scale=2; 10/3" | bc
来源：http://dali.iojbl.cn/Article/details/gt2wsilthpu.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uoecbyzv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigufen.top/Article/details/gt2asxacdrp.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gt2bdrvmbde.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangshuangyany.cn/Article/details/gt2etlamjot.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqfgzyqc.html

f() { local x=1; echo "$x"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bhuhqyql.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lysfybiz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obgoxkly.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gt2ccbbzqzd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gt2amylmpwf.html

[R34] 退出时清理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnezrtgd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gt2tickeznr.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gt2eybehuku.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxinkj.top/Article/details/gt2wepvdtvr.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gt2nqkwzgim.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gt2nmtzearo.html

[R37] 把输出赋给变量
来源：http://dali.quarkkingdee.top/Article/details/gt2humqlbjb.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gt2vbfzjkli.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmvenwph.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gt2ixbbcpeg.html

[R39] 重定向标准输出与错误
来源：http://dali.xinyue.icu/Article/details/gt2coegeymn.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gt2teayiwyb.html

[R40] 追加写日志
来源：http://dali.zdqjudy.top/Article/details/gt2frcbknxq.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gt2chifasbu.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gt2iqeagggz.html

cmd >/dev/null 2>&1
来源：http://dali.nanxinkj.top/Article/details/gt2ilpaibks.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gt2qcbiqqib.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gt2jtpewfvx.html

[R43] 按名字查找文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nkftvezw.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gt2jkhshuvj.html

[R44] 按修改时间查找
来源：http://dali.jianghu66.top/Article/details/gt2tnjvzmly.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gt2bccrmakq.html

[R45] 批量删除
来源：http://dali.mhx1999.top/Article/details/gt2rrivclrx.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gt2ieohezob.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gt2bdqruqgb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gt2vwbceezi.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wyiptikb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2pofvoebp.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gt2acvqnvdz.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2qeywasdm.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gt2jnqgpecp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gt2npnekaae.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gt2upnwocei.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2chydgxpl.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gt2ilvrhstl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tianlin.xyz/Article/details/gt2fwcfqxol.html

[R52] 统计行数
来源：http://dali.zhongyouzk.top/Article/details/gt2ogkwpubi.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2krhyvuqk.html

[R53] 查看文件头与实时尾
来源：http://dali.ehwqpu.com/Article/details/gt2bgbatkso.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gt2iuccauzd.html

[R54] 比较两个文件
来源：http://dali.zdqjudy.top/Article/details/gt2dalfmlge.html

diff a.txt b.txt
来源：http://dali.chenlongwang.top/Article/details/gt2qznhsrdq.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gt2zigzedgi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gt2xcziqctm.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gt2xigqsuak.html

scp file user@host:/path/
来源：http://dali.vqdsnc.cn/Article/details/gt2kvmgbdlh.html

[R57] 远程执行命令
来源：http://dali.zhengqikj.top/Article/details/gt2xhsusidx.html

ssh user@host 'uptime'
来源：http://dali.aizwys.cn/Article/details/gt2pdtfavsa.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gt2tcqpoymj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcwnhdu.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fptwutox.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vacurgxz.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gt2eetvdvpb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gt2moepjukr.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gt2tqbhfwdh.html

df -h;  du -sh *
来源：http://dali.tianlin.xyz/Article/details/gt2bcrhsvsa.html

[R62] 找最占空间的文件
来源：http://dali.zhoulong.xyz/Article/details/gt2ohlsbbed.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gt2euopuzqu.html

[R63] 内存与进程
来源：http://dali.hnxiangtu.top/Article/details/gt2ogghtzsj.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gt2pyvmbhwy.html

[R64] 结束进程
来源：http://dali.yj20258.top/Article/details/gt2ltcbgxmx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gt2kopzajmq.html

[R65] 查看端口占用
来源：http://dali.zdqjudy.top/Article/details/gt2takoxxto.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aibaodan.cn/Article/details/gt2rcoxsowu.html

[R66] 定时任务
来源：http://dali.yuxming.cn/Article/details/gt2ludwqhki.html

crontab -e;  crontab -l
来源：http://dali.jinqigfzy.top/Article/details/gt2xkuafsne.html

[R67] 生成随机十六进制串
来源：http://dali.ybcxt.top/Article/details/gt2gikppqer.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gt2khvgonub.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gt2ulahhfuj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2ldfubwco.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gt2meprdwxr.html

head -c 16 /dev/urandom | base64
来源：http://dali.kuanghao11.cn/Article/details/gt2xaetcchv.html

[R70] 时间戳与互转
来源：http://dali.sysykeji.top/Article/details/gt2dcunbhys.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gt2gixwbovv.html

[R71] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gt2wkxmbwmn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlsehbog.html

[R72] 等待端口就绪
来源：http://dali.feifeiyinyue.top/Article/details/gt2ywkjfsxi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gt2gcpaygvs.html

[R73] 分割大日志
来源：http://dali.hammf.cn/Article/details/gt2wcribjdq.html

split -l 1000 big.log part_
来源：http://dali.yj20258888.top/Article/details/gt2yiowxgsa.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gt2sjqiknzh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xinyue.icu/Article/details/gt2ofewkmhz.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gt2ipvvfkuf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gt2athfljew.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxaluzwi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gt2szlyuucd.html

[R77] 读取用户输入
来源：http://dali.ydzc1.top/Article/details/gt2gejdqmgh.html

read -rp "请输入: " ans
来源：http://dali.jyoumei.cn/Article/details/gt2gtdjnkkj.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gt2ubosghrf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2koyozldn.html

[R79] 解析命令行选项
来源：http://dali.quarkkingdee.top/Article/details/gt2zmbdwpbc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gt2iwfqfgma.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gt2abonuujf.html

time ./run.sh
来源：http://dali.shangyingyoupin.top/Article/details/gt2lghrbiom.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ibzehrbb.html

S. C / C++ 专题
来源：http://dali.guowangkeji.top/Article/details/gt2rfmhgvkp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2eyqvoptp.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2fdhryjdu.html

#include <stdio.h>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eryugnbm.html


<!-- 参考信息 -->