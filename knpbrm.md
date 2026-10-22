代发 wailian999

[Q36] 左连接
来源：http://dali.bjfxy.top/Article/details/gtjtwleegk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtaftujwyd.html

[Q37] 右连接
来源：http://dali.yj20258.top/Article/details/gtclnbreyi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aizwys.cn/Article/details/gtjswfayqq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhiwuduotai.top/Article/details/gtjvkrzyec.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.316326.xyz/Article/details/gtwcmfxkux.html

[Q39] 自连接（查上下级）
来源：http://dali.tian-w.cn/Article/details/gtttyicqzu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guannengcc.top/Article/details/gtkyosqwol.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gtqneinuqe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ivvv.top/Article/details/gtgmpwlipa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gtjjmxyzqz.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtfnxtktlg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gtsknwofno.html

JOIN users u ON u.id = o.user_id
来源：http://dali.9152youxi.cn/Article/details/gtrpfxfaao.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jiagoushi.top/Article/details/gtpmlapsvi.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gtsyuqicna.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhoulong.xyz/Article/details/gtjdqudirz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guowangkeji.top/Article/details/gtuoevuten.html

[Q43] 标量子查询
来源：http://dali.jinqigfzy.top/Article/details/gtfotyomsn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.havefunace.top/Article/details/gtlfuyvuid.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gtgxlrnqja.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jianghu66.top/Article/details/gtiwpettiw.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gtbilgxxbq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtimwfniwy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gtpbjapxxh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtcctvwshs.html

[Q47] 与平均值比较
来源：http://dali.vqdsnc.cn/Article/details/gtrblxyhuw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hammf.cn/Article/details/gtdvccwncd.html

[Q48] CTE 公用表表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwydzigky.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fzhhl.top/Article/details/gtstwhrzyf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yangfankeji.com/Article/details/gthvbzgfsp.html

[Q49] 更新单行
来源：http://dali.daria6918.cn/Article/details/gtyvmevcgi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctviznwm.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gtbpddpekm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtwttnztos.html

[Q51] 用子查询更新
来源：http://dali.xuetiantiany.cn/Article/details/gtcagvxbjg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtfusmiifi.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gtgulytfct.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtjqxcbymp.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gtvubggapz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jianghu66.top/Article/details/gtghvifilk.html

[Q54] 清空表
来源：http://dali.yonumen.top/Article/details/gtffbbuhlx.html

TRUNCATE TABLE logs;
来源：http://dali.pycfn.com/Article/details/gtvnnbkgox.html

[Q55] 排名（并列占位）
来源：http://dali.haohaochexian.top/Article/details/gtknxihddk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhhzjyfe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gtvygffvnf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ivvv.top/Article/details/gtwgfgomir.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gtnnsrgoma.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzurckmoc.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcjheaat.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtjxwfkmfb.html

[Q59] 分组内累计
来源：http://dali.316326.xyz/Article/details/gtvegniuyq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtovvjhvxc.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gtfezrcnyy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gtftjckknd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daxiang520.top/Article/details/gteistviyq.html

[Q61] 移动平均
来源：http://dali.aibaodan.cn/Article/details/gtktmuwmdt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtbngdcsch.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gtkzlbpmxx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtvttvqwyb.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gthgcojeyd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtqschtpsr.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gttgxqrerw.html

COMMIT;
来源：http://dali.chenzaomai.com/Article/details/gtbnimgmiy.html

[Q65] 回滚事务
来源：http://dali.ppjwa.cn/Article/details/gtxooysire.html

ROLLBACK;
来源：http://dali.feifeiyinyue.top/Article/details/gtbignihig.html

[Q66] 行锁查询
来源：http://dali.jqgfzy.top/Article/details/gtzfybgijg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gtnbqlumdb.html

[Q67] 设置隔离级别
来源：http://dali.yueranfly.top/Article/details/gtnpxvbgrr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnxiangtu.top/Article/details/gtazjontyt.html

[Q68] 保存点
来源：http://dali.jyoumei.cn/Article/details/gtneqdwsqy.html

SAVEPOINT sp1;
来源：http://dali.316326.xyz/Article/details/gtqpnupefu.html

ROLLBACK TO sp1;
来源：http://dali.dianchejie.cn/Article/details/gtcichacnq.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gtevklzmvf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gtvdutslah.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gtpffxbybt.html

ANALYZE TABLE users;
来源：http://dali.jlsjyb.cn/Article/details/gtyiypelbo.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gtalcdjuvg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj202588.top/Article/details/gtgazkocna.html

[Q72] 查看索引
来源：http://dali.aibaodan.cn/Article/details/gtijoyzldl.html

SHOW INDEX FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gthxgtxpuf.html

[Q73] 查看表状态
来源：http://dali.gogol.net.cn/Article/details/gtwimaziab.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gtpfhcqquf.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gtztgbawcm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yanxiufei.cn/Article/details/gtifrdegbc.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtfocdaxvp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtxfmcwojq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fengsongda.top/Article/details/gtlosfkgac.html

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gtfoiiphkw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgufenzy.top/Article/details/gtdfoezhta.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gtjkuwkssr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yvedp.cn/Article/details/gtolxfujbg.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gtqekzscdu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gzhubu.top/Article/details/gtuwgrraaj.html

[Q79] 字符串拼接
来源：http://dali.guannengcc.top/Article/details/gtspgrxgvm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gtulndqghf.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gtzujzxfwj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtlcrbglgm.html

[Q81] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gtxmyrvxal.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gttvnzdbhf.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gtgiuinnst.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtjqlqvtts.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gthmrbeovm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmoqhhsjq.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gtlexyzdwv.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdplmfvpa.html

[Q85] 数值取整
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxpbhavw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gtlsqcdiwp.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gtzsbfhbjq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqaiecwo.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gtssgvxwnb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xziqi.cn/Article/details/gtjckggyya.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gtduuskpfm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gtzgdxljyr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtzexovpsq.html

[Q89] 判断表是否存在
来源：http://dali.sweek.top/Article/details/gtvakkzlbj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gtpobjmsqd.html

[Q90] 生成序号列
来源：http://dali.pycfn.com/Article/details/gtmyqjcvee.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.birdmap.top/Article/details/gtjmxtymrx.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtnhrzdzoj.html

R. Bash 专题
来源：http://dali.c1oappe.top/Article/details/gttedwhuer.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtayygdlis.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gtkbqdygea.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gtekprfjyv.html

set -euo pipefail
来源：http://dali.xylfe.cn/Article/details/gttqgmkkkz.html

[R02] 变量赋值与使用
来源：http://dali.fengsongda.top/Article/details/gtvalczzsi.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gtygvegszv.html

[R03] 只读变量
来源：http://dali.xinyue.icu/Article/details/gtphklddsk.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpfrujln.html

[R04] 位置参数
来源：http://dali.havefunace.top/Article/details/gtjahalwvw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtoveigbvp.html

[R05] 参数默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtvabjohxl.html

name="${1:-default}"
来源：http://dali.sweek.top/Article/details/gtvzmhnvhc.html

[R06] 判断命令是否存在
来源：http://dali.daria6918.cn/Article/details/gtrnnjoivv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtoasdjrwa.html

[R07] if 判断文件
来源：http://dali.chenzaomai.com/Article/details/gtsrnishse.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtljcffbrk.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gtseavoszn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gtmfgdoztj.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gtgpjkhrsw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtjhbvpbvs.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gtixnnzicn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtvupadoge.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gtknxrziuv.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gtielujzlf.html

start) echo "启动" ;;
来源：http://dali.xylfe.cn/Article/details/gtjmefiobo.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrkkpche.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gtsmjmgwqn.html

esac
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdwtievx.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvnymooe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gtbitjxtgx.html

[R13] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gttgkeunos.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gtuizihifu.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gtqufaoufk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtezkbxbbw.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtfsaiaarx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhongyouzk.top/Article/details/gtkracfjbk.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gtfeezuntx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtndafvdrh.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtmbrqlvcz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fzhhl.top/Article/details/gtldnvpfyw.html

[R18] 遍历数组
来源：http://dali.yuxming.cn/Article/details/gtvvbuirja.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sufxvd.cn/Article/details/gtyzfbtwcq.html

[R19] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtunfqiyoh.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gtxxcmwoeg.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtgtwzmpgo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gtujssihqh.html

[R21] 字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtkiuaipxu.html

echo "${#s}"
来源：http://dali.gzhubu.top/Article/details/gtsteuvhlq.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtthbuoqht.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gtceyvcmlr.html

[R23] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gtvksxvakm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gtkniihbpw.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtesjwpuru.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gturiklwdc.html

[R25] 去后缀 / 去前缀
来源：http://dali.bjfxy.top/Article/details/gtsbtkfqum.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xinyue.icu/Article/details/gtamzufnqc.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtpnooezur.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gtirfladzp.html

[R27] 算术展开
来源：http://dali.ehwqpu.com/Article/details/gtcdmemeux.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gtmdjhmczy.html

[R28] 浮点运算
来源：http://dali.cucudq.cn/Article/details/gtvccctgxh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gtgzvttnih.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gtzkpahxmc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gteqtisrva.html

[R30] 函数返回状态码
来源：http://dali.cucudq.cn/Article/details/gtrpslthap.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gtxpppmaok.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmotwlafa.html

f() { local x=1; echo "$x"; }
来源：http://dali.yueranfly.top/Article/details/gtzpfbhsrg.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gtuskzxnvn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtzdawbdci.html

[R33] 捕获错误并提示行号
来源：http://dali.mhx1999.top/Article/details/gtxuiyhqqu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tian-w.cn/Article/details/gtsizapyoy.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gtbabucgso.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtlbcshpow.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gtbxrxumck.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gtfqxezddh.html

[R36] 并发执行多个任务
来源：http://dali.gaohongyu789.top/Article/details/gtpakugzas.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gthpoodvvn.html

[R37] 把输出赋给变量
来源：http://dali.cheryme.top/Article/details/gtizccfnqc.html

files=$(ls -1)
来源：http://dali.gaohongyu789.top/Article/details/gtnysbvpyn.html

[R38] 管道串联
来源：http://dali.jqgufenzy.top/Article/details/gtlxfeldlm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gtopndqjfm.html

[R39] 重定向标准输出与错误
来源：http://dali.jlsjyb.cn/Article/details/gtvqpzmqrc.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gttysppiel.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gtoafaytxh.html

echo "log" >> out.log
来源：http://dali.hammf.cn/Article/details/gttjpqvxxi.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gtlvufbelg.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gtyexnxfjk.html

[R42] 输入重定向
来源：http://dali.daria6918.cn/Article/details/gtmrpocjuu.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtejoxogts.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gtfpaqwlyt.html

find . -name "*.log" -type f
来源：http://dali.snrcjt.cn/Article/details/gtfdtvkrbb.html

[R44] 按修改时间查找
来源：http://dali.yj202588.top/Article/details/gtzvfghqgi.html

find . -mtime -7 -type f
来源：http://dali.kuanghao11.cn/Article/details/gtyvwjvwqe.html

[R45] 批量删除
来源：http://dali.nwbrower.top/Article/details/gtpgmqqrdr.html

find . -name "*.tmp" -delete
来源：http://dali.hnqzz.top/Article/details/gtpokkjbzu.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gtfvjjisfi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gtfyuqjjvx.html

[R47] sed 单行替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyxipuni.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aizwys.cn/Article/details/gtoaoccdtj.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gtqxyulzdu.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtyrytugsx.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gtsjfxqnxn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhengqikj.top/Article/details/gttzhdnhgd.html

[R50] awk 求和
来源：http://dali.shangyingyoupin.top/Article/details/gtxvdoxvbx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gthpmbxgfl.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gtfwuqhekv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuanzx.com/Article/details/gtygqvihjg.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gtyrhwpgvx.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gtoqryuhei.html

[R53] 查看文件头与实时尾
来源：http://dali.mhx1999.top/Article/details/gtdmfukbvk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.kuanghao11.cn/Article/details/gtphyreibu.html

[R54] 比较两个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtilnzyhre.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gtnayzunzj.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxlnlrrs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gtquwipkcu.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gtovhhhgxq.html

scp file user@host:/path/
来源：http://dali.kuanghao11.cn/Article/details/gtqlpjykjb.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gtlqdmddqu.html

ssh user@host 'uptime'
来源：http://dali.birdmap.top/Article/details/gtcylywqfa.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gtlkpopihq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gtfkbwoudq.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzbchwrf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gtphbzxzoi.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtshblmlun.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuxming.cn/Article/details/gtaktgljvx.html

[R61] 磁盘占用
来源：http://dali.hnxiangtu.top/Article/details/gtkmecsemk.html

df -h;  du -sh *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmliccxr.html

[R62] 找最占空间的文件
来源：http://dali.chenjidiqi.icu/Article/details/gtcdjemwdt.html

du -ah . | sort -rh | head -10
来源：http://dali.chenjidiqi.icu/Article/details/gtchuldeya.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gtcxpzvaky.html

free -h;  ps aux | grep nginx
来源：http://dali.xinyue.icu/Article/details/gtxktsunzj.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gtkgsvvxec.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sysykeji.top/Article/details/gtbzazxuap.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gtfvfanhqc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gtcnbfcatz.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtkplrlalj.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gtthflydit.html

[R67] 生成随机十六进制串
来源：http://dali.yvedp.cn/Article/details/gtxffpztkj.html

openssl rand -hex 16
来源：http://dali.feifeiyinyue.top/Article/details/gtziewurde.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtxdadkjor.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtqzkjgkkc.html

[R69] 生成随机密码
来源：http://dali.yj20258.top/Article/details/gttjyewtvu.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtuuxlrqjc.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gtkqutqgjn.html

date +%s;  date -d @1700000000
来源：http://dali.havefunace.top/Article/details/gtijyuvvze.html

[R71] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gthyhkmsvy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.snrcjt.cn/Article/details/gtmnsntgfv.html

[R72] 等待端口就绪
来源：http://dali.fengsongda.top/Article/details/gtcvdarcwk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtikjcixgm.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gtwwyteiip.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gtgnwrqrut.html

[R74] 批量重命名
来源：http://dali.sufxvd.cn/Article/details/gtvfpetlbl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gthaqqxaeq.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtsepkgzpv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gtmeekbepo.html

[R76] 使用临时文件
来源：http://dali.cashguo.top/Article/details/gtxmegiefw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtxxtfzxta.html

[R77] 读取用户输入
来源：http://dali.hysaishi.cn/Article/details/gtubjmwlsg.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gtkvgjlgvj.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gtnvwjqqjy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cqqwz.cn/Article/details/gtawklinmr.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gtyocfzwpq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gtchrkcekn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gthdpduzgz.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gtfuynxcgk.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvprjcvwh.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnkpxxki.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvlqtkhrn.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gthzovybjt.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gtdnwqosoe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.316326.xyz/Article/details/gtmekluosb.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtvqxrbzqt.html

int a = 10; printf("%d\n", a);
来源：http://dali.cqqwz.cn/Article/details/gtsceeoodr.html

[S03] C：读入整数
来源：http://dali.ehwqpu.com/Article/details/gtbggjtcbg.html

int x; scanf("%d", &x);
来源：http://dali.jiagoushi.top/Article/details/gtydxuuurd.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gtvtpsrszy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gtqrflfbpx.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gtmwoeylqc.html


<!-- 参考信息 -->