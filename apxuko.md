代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtkouefqbk.html

[Q30] 分组统计
来源：http://dali.birdmap.top/Article/details/gtqbthjkjt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtkncddaro.html

[Q31] 分组后过滤
来源：http://dali.yonumen.top/Article/details/gthayumppe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gtwsjdwcqa.html

[Q32] 分组拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtewoaytzp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtxvkgogfu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gtpmhlkcvq.html

[Q33] 多列分组
来源：http://dali.pengpengdd.cyou/Article/details/gttebsasno.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhoulong.xyz/Article/details/gtnkfketit.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gtsxuazzsc.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gttprflrtz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yvedp.cn/Article/details/gtvaveytlq.html

) t WHERE rn = 1;
来源：http://dali.shuidangran.top/Article/details/gtumuimetr.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gtpgrtrgpc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtcoljdfej.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gtpjipmyqo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtpjvxftgd.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gtqhbqokpb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.mhx1999.top/Article/details/gtmebkifqk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gtigmpstpn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guowangkeji.top/Article/details/gthwbcmkyo.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigufen.top/Article/details/gtlakvjrjy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.redwolf501.top/Article/details/gtxdferoef.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwddufipt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.c1oappe.top/Article/details/gtusbpvkcu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gtpgwofakd.html

[Q41] 多表连接
来源：http://dali.yj20258888.top/Article/details/gtnrtsrzer.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cqqwz.cn/Article/details/gtwwzyrlnd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuxming.cn/Article/details/gtjykwpweu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.meibo888.top/Article/details/gttgqfldzm.html

[Q42] 连接条件附加过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtutevmjtb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nwbrower.top/Article/details/gtwnsfqnjs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtgdkedhnt.html

[Q43] 标量子查询
来源：http://dali.yj20258.top/Article/details/gtwqmptyuv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zycfv.cn/Article/details/gtktctkehu.html

[Q44] IN 子查询
来源：http://dali.xinyue.icu/Article/details/gtkksyqddd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.birdmap.top/Article/details/gtcxkdwsbt.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgufenzy.top/Article/details/gtjtwuteud.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtuxgrjkhr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxuanxn.top/Article/details/gtgvjocefh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtadpqaxyf.html

[Q47] 与平均值比较
来源：http://dali.hnqzz.top/Article/details/gtrruaetbj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gtnaitvwfq.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gtzirzhapu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jyoumei.cn/Article/details/gtbccprxxz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvzqqunh.html

[Q49] 更新单行
来源：http://dali.xinyue.icu/Article/details/gtkuspggop.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtetxvwegx.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gtxusdaahh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtxayjwtmv.html

[Q51] 用子查询更新
来源：http://dali.yanxiufei.cn/Article/details/gtdurjadtl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj202588.top/Article/details/gtmtiseegw.html

[Q52] 删除指定行
来源：http://dali.hammf.cn/Article/details/gtzzsrckvo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtsbdeczuw.html

[Q53] 按条件删除
来源：http://dali.wangdashe.top/Article/details/gtndhodosw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gtxrmnxoas.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gtenahhdnj.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gtgjlwnuqd.html

[Q55] 排名（并列占位）
来源：http://dali.cashguo.top/Article/details/gtjsiygmdt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtisvsevzr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gthhombzkx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtpfdalzdo.html

[Q57] 行号
来源：http://dali.iojbl.cn/Article/details/gtnvjwwebc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gtxguscupz.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gtlfyzkglr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.meibo888.top/Article/details/gtocmdlxbq.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gtbwbkpprk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtxohvenhk.html

[Q60] 取上一行 / 下一行
来源：http://dali.ivvv.top/Article/details/gtvsgdpbmy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hongshengwenyu.top/Article/details/gtbeslezub.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtsrrwiznv.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gtedphaedq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtgnxlypem.html

[Q62] 分组占比
来源：http://dali.9152youxi.cn/Article/details/gtqskgvafe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtpbjgtapo.html

[Q63] 开启事务
来源：http://dali.ehwqpu.com/Article/details/gtabewbxpe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gtjqmhuvtf.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gtrvlorhte.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gtvushwzut.html

[Q65] 回滚事务
来源：http://dali.dianchejie.cn/Article/details/gtkgirzdtd.html

ROLLBACK;
来源：http://dali.316326.xyz/Article/details/gtlamfnfxa.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gtczrkuutk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuetiantiany.cn/Article/details/gtnifcajcn.html

[Q67] 设置隔离级别
来源：http://dali.wangshuangyany.cn/Article/details/gtgqqruvdo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxuanxn.top/Article/details/gtokapklqv.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gtdjfcvdyz.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gtfewieijc.html

ROLLBACK TO sp1;
来源：http://dali.nwbrower.top/Article/details/gtjczebebp.html

[Q69] 查看执行计划
来源：http://dali.guannengcc.top/Article/details/gtwyfktodw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gthlyntwtm.html

[Q70] 更新统计信息
来源：http://dali.hfpthk.cn/Article/details/gtkrnqczki.html

ANALYZE TABLE users;
来源：http://dali.cucudq.cn/Article/details/gtpqklnqay.html

[Q71] 查看建表语句
来源：http://dali.jlsjyb.cn/Article/details/gtwkghkjvy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuanzx.com/Article/details/gtgokxmnlg.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gtopwsytfd.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtvyabafgn.html

[Q73] 查看表状态
来源：http://dali.cucudq.cn/Article/details/gtkxpyxlpe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtwhhaiemw.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gtblwwwfje.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guannengcc.top/Article/details/gtsfcmnjai.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtedavcxtr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtlxxslewn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gtsrinhrjl.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gtpemfweyl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gtddewzndp.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gtydmfhkof.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxydzflo.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtppylpzfa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gtflvxtaxs.html

[Q79] 字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gtyviyhweu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gtcehfkfmc.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gtyctwjxfp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtqwyroqqi.html

[Q81] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gteknwcpgl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjmagzml.html

[Q82] 字符长度与字节长度
来源：http://dali.gogol.net.cn/Article/details/gtydytqygy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtsojcuykv.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtzmsquxft.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtbbcksrey.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gtmgfassos.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtsgebjhdf.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhqdrpdn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gtaiqxrimj.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gtumcjhwfz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ybcxt.top/Article/details/gtjivtgbtr.html

[Q87] JSON 字段做条件
来源：http://dali.dianchejie.cn/Article/details/gtdfhaghdh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gtluxeucph.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gtcbstqoap.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gtwhvrylme.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndjghevk.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gtvqxdzssr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtlorvfmfd.html

[Q90] 生成序号列
来源：http://dali.yuanzhike.top/Article/details/gtwwypjbbc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ivvv.top/Article/details/gtersnaikt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gttginbdtk.html

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gtaxovswjc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtvaixopos.html

[R01] shebang 与严格模式
来源：http://dali.zycfv.cn/Article/details/gtzyoxnxhz.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gtsusiypim.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gtreqyvkjx.html

[R02] 变量赋值与使用
来源：http://dali.sufxvd.cn/Article/details/gtzjozfwou.html

name="Tom"; echo "$name"
来源：http://dali.jinqigufen.top/Article/details/gtrbukiovn.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gtemjdkbmq.html

readonly PI=3.14
来源：http://dali.yuanzhike.top/Article/details/gtzjjzyzpp.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gtoqfzvces.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gtsrnyrijx.html

[R05] 参数默认值
来源：http://dali.aizwys.cn/Article/details/gtwxyoglvl.html

name="${1:-default}"
来源：http://dali.jinqigfzy.top/Article/details/gtdwjtnrwq.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gtzbxhplgf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtmxstjwax.html

[R07] if 判断文件
来源：http://dali.gzhubu.top/Article/details/gtvohrrfyp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gtmttndofh.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gttizskhsj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.meibo888.top/Article/details/gtxzilssxv.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gtvpnihcft.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gtxlkewfqd.html

[R10] 正则匹配
来源：http://dali.birdmap.top/Article/details/gtkogsdjkw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gtrkhhvolu.html

[R11] case 多分支
来源：http://dali.hammf.cn/Article/details/gtbybfxkeh.html

case "$1" in
来源：http://dali.gaohongyu789.top/Article/details/gtzvfyhada.html

start) echo "启动" ;;
来源：http://dali.yongpay.top/Article/details/gtlzzsolsm.html

stop)  echo "停止" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtcfggwpew.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbymjtbqc.html

esac
来源：http://dali.zycfv.cn/Article/details/gtqjqztorq.html

[R12] for 遍历文件
来源：http://dali.yanxiufei.cn/Article/details/gtzyanzjwu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtvbirbqhn.html

[R13] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gtlxughqgn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtrqgyfyny.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gtpddacwju.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gthysxnpei.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtcokypudk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gtsotdemcj.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gtusursfml.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtmerqtdwk.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gtumlfwfbn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gtbrwkhhzd.html

[R18] 遍历数组
来源：http://dali.hammf.cn/Article/details/gtolvkadmk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gtevmfubyn.html

[R19] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtnendsczu.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzbcdqnv.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gtzfshctkw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gtypreoglu.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gtnlkibryi.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gtehleeyyy.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtgokcdilv.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gtgsiywxjy.html

[R23] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtkzewybrb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cqqwz.cn/Article/details/gtscvmufxh.html

[R24] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gtamajnwul.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnxiangtu.top/Article/details/gtwnyyfkoz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtkwgarqiq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gtmixijmhi.html

[R26] 命令替换
来源：http://dali.guannengcc.top/Article/details/gtelydnqbz.html

now=$(date +%F); echo "$now"
来源：http://dali.chenjidiqi.icu/Article/details/gtlwxvtmip.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gtisymtjsl.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gthtujmjbu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gtqyiwklcn.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gtsebgyxil.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gtvsscycgv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtbfqysnwh.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtkbqjigvq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.birdmap.top/Article/details/gtciovicbj.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtraaoawwr.html

f() { local x=1; echo "$x"; }
来源：http://dali.vqdsnc.cn/Article/details/gtekuwqsmi.html

[R32] 参数个数校验
来源：http://dali.vqdsnc.cn/Article/details/gtgkwcjvul.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtqmhsdqpn.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gtyoxydajj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.svipenyu.cn/Article/details/gtqpctvsyn.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gtpyxctlvc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gttrjzqnyv.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gttffowdfy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gtnmucavuq.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gtephnbtgd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgfzy.top/Article/details/gtlgjhhpbk.html

[R37] 把输出赋给变量
来源：http://dali.dashuyun.cn/Article/details/gtwrrffixx.html

files=$(ls -1)
来源：http://dali.svipenyu.cn/Article/details/gtczyzljgt.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gtvgpxtwgm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gtodwycazk.html

[R39] 重定向标准输出与错误
来源：http://dali.aibaodan.cn/Article/details/gtsynxpxtb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gtlznqjktw.html

[R40] 追加写日志
来源：http://dali.guowangkeji.top/Article/details/gthzibfwib.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gtfjekyrhj.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gtivxwpvag.html

cmd >/dev/null 2>&1
来源：http://dali.yj202588.top/Article/details/gtdcvbekaw.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gtnwqybnwx.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gteifnqqnm.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gtqlmcjfuz.html

find . -name "*.log" -type f
来源：http://dali.316326.xyz/Article/details/gtriraldcb.html

[R44] 按修改时间查找
来源：http://dali.xinyue.icu/Article/details/gtedqprauf.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gtkupquvjm.html

[R45] 批量删除
来源：http://dali.guowangkeji.top/Article/details/gtcwdkxyaq.html

find . -name "*.tmp" -delete
来源：http://dali.kuanghao11.cn/Article/details/gtxxcmaanw.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gtjndroeql.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gtuxfltrlc.html

[R47] sed 单行替换
来源：http://dali.yvedp.cn/Article/details/gtnvedwiak.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daxiang520.top/Article/details/gtnrshupqx.html

[R48] awk 取指定列
来源：http://dali.ivvv.top/Article/details/gtexrkznyr.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpshhybw.html

[R49] awk 带条件
来源：http://dali.yvedp.cn/Article/details/gtybwfuxal.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zdqjudy.top/Article/details/gtzzhmavzb.html

[R50] awk 求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosmtchzs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtmhubnzsx.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gtlmnshjpx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xziqi.cn/Article/details/gtpbvtknxk.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gthfkpogpm.html

wc -l a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtxgbxttgq.html

[R53] 查看文件头与实时尾
来源：http://dali.guannengcc.top/Article/details/gtmhvijlpq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gzhubu.top/Article/details/gtgsgzuhps.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gtujpttyob.html

diff a.txt b.txt
来源：http://dali.cdnleiting.top/Article/details/gtbfxurxni.html

[R55] 压缩与解压
来源：http://dali.cheryme.top/Article/details/gtdltusdmd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gtrvmsdodo.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtvxkqlyme.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gtojvjrmod.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gtvhlabikp.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gtuumuwyif.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gtxxfsbfrl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pycfn.com/Article/details/gtdhrazgpu.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwuzrfky.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nwbrower.top/Article/details/gtafzigcmy.html

[R60] 只看 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gtqutnqbbu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gtksgxoxrd.html

[R61] 磁盘占用
来源：http://dali.cucudq.cn/Article/details/gtsckbiojz.html

df -h;  du -sh *
来源：http://dali.chenlongwang.top/Article/details/gtfskirmdu.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gttjamwyae.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gthchjsgfx.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gtaficksgz.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gtgilinske.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gtzpkqjzpt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gtzpcniekj.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gtcszjfurj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nwbrower.top/Article/details/gtowvstqdq.html

[R66] 定时任务
来源：http://dali.fzhhl.top/Article/details/gtquxesvdz.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gtlwbhctnu.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gtzracprsc.html

openssl rand -hex 16
来源：http://dali.daria6918.cn/Article/details/gtobloqrru.html

[R68] 计算文件校验值
来源：http://dali.wangshuangyany.cn/Article/details/gtvkxdfsvo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ydzc1.top/Article/details/gtdbyqokac.html

[R69] 生成随机密码
来源：http://dali.hfpthk.cn/Article/details/gtvxatnwgd.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gtdqcaviqw.html

[R70] 时间戳与互转
来源：http://dali.cheryme.top/Article/details/gtlnxhwmom.html

date +%s;  date -d @1700000000
来源：http://dali.yueranfly.top/Article/details/gtqlqxzxie.html

[R71] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gthseqmdgt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guowangkeji.top/Article/details/gtxbnxfgyt.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtldynxtnw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtxlxwnegx.html

[R73] 分割大日志
来源：http://dali.gotoacloud.top/Article/details/gtdqjwayss.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gtjiisadlm.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gtvlltgkri.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jianghu66.top/Article/details/gttuoqfzmx.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtanyffunn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gttqfdpckm.html

[R76] 使用临时文件
来源：http://dali.guowangkeji.top/Article/details/gtbofpkdre.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtgwvpqmyp.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkkuffid.html

read -rp "请输入: " ans
来源：http://dali.shangyingyoupin.top/Article/details/gtezreftai.html

[R78] 交互式菜单
来源：http://dali.9152youxi.cn/Article/details/gtlykbysbp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gteqdhjzhs.html

[R79] 解析命令行选项
来源：http://dali.wangshuangyany.cn/Article/details/gtualqqghz.html


<!-- 参考信息 -->