代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guannengcc.top/Article/details/gticfpjeqk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gtxklrtdub.html

[Q39] 自连接（查上下级）
来源：http://dali.tianlin.xyz/Article/details/gtwpqecrsd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.havefunace.top/Article/details/gtplvsyxbf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gtklhnwrms.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.316326.xyz/Article/details/gtagdkgyqe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnpshxkg.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gtpcndtlso.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hywenlv.cn/Article/details/gtgtpxqzkw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gtuewclrcn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cashguo.top/Article/details/gtpafrwfhr.html

[Q42] 连接条件附加过滤
来源：http://dali.snrcjt.cn/Article/details/gtdyqjgggc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yangfankeji.com/Article/details/gtlsbuswrx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jiagoushi.top/Article/details/gtqhtglneb.html

[Q43] 标量子查询
来源：http://dali.zhengqikj.top/Article/details/gtaassezfn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gthfqtvdfx.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gtlmzzpuoi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gzhubu.top/Article/details/gtxfrogzou.html

[Q45] EXISTS 判断存在
来源：http://dali.yueranfly.top/Article/details/gtkgycvamk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtkjujsixt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gzhubu.top/Article/details/gtrkijamql.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtwgefkusq.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gthsudylnq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hammf.cn/Article/details/gttrakxvzu.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gthdmgpmgb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shuidangran.top/Article/details/gtpuzmarjw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhongyouzk.top/Article/details/gtdjvjujjg.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gtvswiwulm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtbahywhso.html

[Q50] 批量更新
来源：http://dali.hnxiangtu.top/Article/details/gtspogvdiq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cheryme.top/Article/details/gttmqsrbgd.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gtpijcrfey.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xylfe.cn/Article/details/gtunqidvtj.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gtnxgfdyfm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gttudickiu.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gtabattebd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gtpsquxmew.html

[Q54] 清空表
来源：http://dali.sweek.top/Article/details/gtijlxcsdk.html

TRUNCATE TABLE logs;
来源：http://dali.nanxinkj.top/Article/details/gtapetvvvn.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gtzunkmtje.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjvedxux.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhixingplan.top/Article/details/gtokpzigoy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmroeiyx.html

[Q57] 行号
来源：http://dali.yj20258888.top/Article/details/gtsrnulceb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sxryk.cn/Article/details/gtzkxwzxnj.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfrxxanx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtkdoffcnl.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtpoxbwsgo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gteqzoegtb.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gtoaqjaedk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gtusxhcbgl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gtxhntzgpw.html

[Q61] 移动平均
来源：http://dali.havefunace.top/Article/details/gtfqzpvnyl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtgkzstxkn.html

[Q62] 分组占比
来源：http://dali.pycfn.com/Article/details/gtvmqyhfip.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gttvflcvof.html

[Q63] 开启事务
来源：http://dali.sweek.top/Article/details/gtebgzubro.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gtmxinnfzs.html

[Q64] 提交事务
来源：http://dali.chenzaomai.com/Article/details/gtgxyqwcmi.html

COMMIT;
来源：http://dali.chenzaomai.com/Article/details/gtxiodlwsy.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gtnfmzboau.html

ROLLBACK;
来源：http://dali.ehwqpu.com/Article/details/gtuvypfriq.html

[Q66] 行锁查询
来源：http://dali.yuanzhike.top/Article/details/gtqrfggwcr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yongpay.top/Article/details/gtujggcbjs.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gtbjownqrx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gtxvgwsith.html

[Q68] 保存点
来源：http://dali.jianghu66.top/Article/details/gtmixsxdqp.html

SAVEPOINT sp1;
来源：http://dali.yueranfly.top/Article/details/gtrdwcggai.html

ROLLBACK TO sp1;
来源：http://dali.yueranfly.top/Article/details/gtjmgrhqxj.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gtruadanyi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gtfikfvrgn.html

[Q70] 更新统计信息
来源：http://dali.gzhubu.top/Article/details/gtxvpodurp.html

ANALYZE TABLE users;
来源：http://dali.shzxlz.cn/Article/details/gtxngakyju.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gtghfewkcx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gtphbwnylt.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gtwkqtzdtx.html

SHOW INDEX FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtiwwlwwwg.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gtahnzymdm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nwbrower.top/Article/details/gtbsmrzohm.html

[Q74] 强制使用索引
来源：http://dali.jinqigfzy.top/Article/details/gtlciyeqpj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgufenzy.top/Article/details/gtmknyqcvg.html

[Q75] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtzsdnfjtg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gttjlouepj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenlongwang.top/Article/details/gtxkxijaus.html

[Q76] 按天统计
来源：http://dali.chenlongwang.top/Article/details/gtgnspqqib.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gtdxpilclr.html

[Q77] 时间加减
来源：http://dali.cdnleiting.top/Article/details/gtrwqghyfh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gtbffniybu.html

[Q78] 当前时间
来源：http://dali.tian-w.cn/Article/details/gtiypplswy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gtyvsvzvnz.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gtmeifqbys.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gtnmxohkwr.html

[Q80] 字符串截取
来源：http://dali.jiagoushi.top/Article/details/gtakxebbve.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtyvqwsbkz.html

[Q81] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtsivfedye.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fzhhl.top/Article/details/gtdbflphkm.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gtlncesytq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtbxmnojfz.html

[Q83] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtvgkjwpht.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtqmawhwmk.html

[Q84] 去除首尾空格
来源：http://dali.hfpthk.cn/Article/details/gtjbazxgde.html

SELECT TRIM(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gttphqbxvk.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gtnnnixrgn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gtsdhtlwjz.html

[Q86] 读取 JSON 字段
来源：http://dali.yonumen.top/Article/details/gtdvdesebp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gzhubu.top/Article/details/gtenhqliob.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gtsjhdphvb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtnhuonsqf.html

[Q88] 行转列（条件聚合）
来源：http://dali.sysykeji.top/Article/details/gtgfciuwkp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.quarkkingdee.top/Article/details/gtfbfiwuxp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gtnbwmnfhp.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gtnbdvupes.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gtjpyvyhvd.html

[Q90] 生成序号列
来源：http://dali.gaohongyu789.top/Article/details/gtughtcjto.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gtdwnnujen.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtbovowwez.html

R. Bash 专题
来源：http://dali.jinqigfzy.top/Article/details/gtunwxivdl.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdczyiwqe.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gtwvkdynej.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gtmrzovtcn.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gtpewmspgm.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gthhmopppm.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gtboalqjsu.html

[R03] 只读变量
来源：http://dali.yuxming.cn/Article/details/gtgmyjlkac.html

readonly PI=3.14
来源：http://dali.zhixingplan.top/Article/details/gtlfdwgtmq.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjipwesj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gtrtlmlnct.html

[R05] 参数默认值
来源：http://dali.zhoulong.xyz/Article/details/gtfhqnglvp.html

name="${1:-default}"
来源：http://dali.gzhubu.top/Article/details/gtditbkklo.html

[R06] 判断命令是否存在
来源：http://dali.aizwys.cn/Article/details/gtnqtrywwz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmlzrlwl.html

[R07] if 判断文件
来源：http://dali.shuidangran.top/Article/details/gtfjfomutb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrhjopgm.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gtysxsgmli.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gttwrvvfdn.html

[R09] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtubzectqi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnqzz.top/Article/details/gtqkdrfcmt.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gtkldlmsrj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gturtoyvup.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gthzzlacgj.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gtzcbrgyaz.html

start) echo "启动" ;;
来源：http://dali.ivvv.top/Article/details/gtzlovhfyb.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtvjmoysue.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtbdmnvzmc.html

esac
来源：http://dali.dashuyun.cn/Article/details/gtmqmsekhy.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gtxjaewqrs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtfstptxmt.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtyinnffbj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtpiayjaow.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gtizcoelmq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtqfmmyqkt.html

[R15] while 逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtzwqsjvbm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gtvjcucpmd.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gttevutbby.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtvhajunnm.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gtlxxkzpbj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtujvywpvi.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gtpgvlplvb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtbojywqep.html

[R19] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gtmdpesdev.html

echo "${#arr[@]}"
来源：http://dali.sweek.top/Article/details/gthogtqgfp.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtgobxawtx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtyhdhquis.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gtejcsodyg.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gtkiggcazb.html

[R22] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtydasfwrr.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gtgfzqhtbn.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gteuksgxix.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gtlenkyymm.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtvzxwxznh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258888.top/Article/details/gtkkyczgfw.html

[R25] 去后缀 / 去前缀
来源：http://dali.pengpengdd.cyou/Article/details/gtkjbfwunr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gteijlxdsu.html

[R26] 命令替换
来源：http://dali.hysaishi.cn/Article/details/gtpbsnmuaq.html

now=$(date +%F); echo "$now"
来源：http://dali.jiagoushi.top/Article/details/gtywhjokyc.html

[R27] 算术展开
来源：http://dali.fzhhl.top/Article/details/gtsmcpkyds.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gtszngoyhc.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gtixsfeeqg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gtvxsddhrs.html

[R29] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gtpkxekloe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gtbsqwkwzo.html

[R30] 函数返回状态码
来源：http://dali.pycfn.com/Article/details/gthguqdypo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gtxitptegc.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gthhtehnsa.html

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gtfhbabbrd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gtwabixfwb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gthcldatbk.html

[R33] 捕获错误并提示行号
来源：http://dali.shzxlz.cn/Article/details/gtatwfrpcc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangdashe.top/Article/details/gtzmjbcxfv.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtrbmqjvhg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtoksjxyqk.html

[R35] 后台执行并等待
来源：http://dali.yueranfly.top/Article/details/gtzndrfshr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gtqmxlccwn.html

[R36] 并发执行多个任务
来源：http://dali.gzhubu.top/Article/details/gtxjxlaubb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hywenlv.cn/Article/details/gtryotsanz.html

[R37] 把输出赋给变量
来源：http://dali.wangdashe.top/Article/details/gtmmsmwlwg.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gtxsyolqsk.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gtzmceyozi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gtbbfwszev.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gtxyssnsjo.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gtwxehltmx.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gtztjslapa.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhlodsma.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkzlksdq.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gtjvzeeakv.html

[R42] 输入重定向
来源：http://dali.tianlin.xyz/Article/details/gtcuwwhazl.html

wc -l < a.txt
来源：http://dali.sxryk.cn/Article/details/gtpebauvjc.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gtigzozwek.html

find . -name "*.log" -type f
来源：http://dali.wangdashe.top/Article/details/gtdnujubdr.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gtzhiriwht.html

find . -mtime -7 -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtdbqicqls.html

[R45] 批量删除
来源：http://dali.pengpengdd.cyou/Article/details/gtoiiuvggz.html

find . -name "*.tmp" -delete
来源：http://dali.zhengqikj.top/Article/details/gtxlxiqusx.html

[R46] 递归替换文件内容
来源：http://dali.ivvv.top/Article/details/gtbichdmpm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cqqwz.cn/Article/details/gtcnyvgfzv.html

[R47] sed 单行替换
来源：http://dali.aizwys.cn/Article/details/gtwbckpvvb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtozemohhi.html

[R48] awk 取指定列
来源：http://dali.chenzaomai.com/Article/details/gtigdsbwpr.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtovbrsfje.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuohpwvvq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gtxwfnjxbh.html

[R50] awk 求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjezaafec.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtzfhgmgkp.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gtonbccmlf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tianlin.xyz/Article/details/gtezzzxfep.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gtfwgxunla.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gtxpkohvuq.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gtvyyoshao.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhiwuduotai.top/Article/details/gtrercmcaq.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gtkymjsrwi.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gtdbqpkuvj.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaybcxiwr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gtgryrsriz.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gtcaqwkdnf.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gtomuyssnm.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gtpnrbijlv.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangtech.top/Article/details/gtzueomcbs.html

[R58] 下载文件
来源：http://dali.jyoumei.cn/Article/details/gtshucqtnd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guannengcc.top/Article/details/gtpazcdiok.html

[R59] 发 POST JSON
来源：http://dali.cashguo.top/Article/details/gtauyubphw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gtgisyqzhc.html

[R60] 只看 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gthaokqhop.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hysaishi.cn/Article/details/gtvcnntzvh.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gtplntuzrh.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gtwfmxvpef.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtjcgslwbs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoubutyqg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gtblivqlnn.html

free -h;  ps aux | grep nginx
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdkcpoev.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtjhhhcvvc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gtlujtndqm.html

[R65] 查看端口占用
来源：http://dali.guannengcc.top/Article/details/gtcctfgqew.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ppjwa.cn/Article/details/gtwybdkgfy.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gtotctucgj.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gtwkdvxihy.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gtsdmdlcmf.html

openssl rand -hex 16
来源：http://dali.9152youxi.cn/Article/details/gtkidmhzqc.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtgwxfimwb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guowangkeji.top/Article/details/gtqgccvvie.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gtoepbiyes.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gtokizmwuz.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gtjszrmqpa.html

date +%s;  date -d @1700000000
来源：http://dali.dianchejie.cn/Article/details/gtqdhqdmyh.html

[R71] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtawwmrnlx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtdpfvdjfi.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gttrrtqofo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gtpiiguwki.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gtgfgrcwzb.html

split -l 1000 big.log part_
来源：http://dali.ybcxt.top/Article/details/gtxbpwnnxl.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gtnrngiftz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gtgqwvidss.html

[R75] 导出环境变量
来源：http://dali.dashuyun.cn/Article/details/gtjjiyadwp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gtslyopodp.html

[R76] 使用临时文件
来源：http://dali.yvedp.cn/Article/details/gtsgynwrpz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gtwuuvdwjn.html

[R77] 读取用户输入
来源：http://dali.hongshengwenyu.top/Article/details/gtqsguzsjx.html

read -rp "请输入: " ans
来源：http://dali.jiagoushi.top/Article/details/gtrwlhfgvv.html

[R78] 交互式菜单
来源：http://dali.tanke756.top/Article/details/gtcoyfwfrj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gtkprdtzxc.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gtdhpkwehj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zycfv.cn/Article/details/gtlmqkwipy.html

[R80] 查看脚本执行耗时
来源：http://dali.chenlongwang.top/Article/details/gtxyfxzlsp.html

time ./run.sh
来源：http://dali.meibo888.top/Article/details/gtehtvrdmg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlefyalxk.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtijqjsokl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtcdyaubih.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gtnuoepehl.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gtzfwltwpm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gtatdvbdaq.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gtsxhwehhs.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtxshzodmq.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gtvagmmeuj.html

int x; scanf("%d", &x);
来源：http://dali.ehwqpu.com/Article/details/gtiobofxkd.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncyrsend.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhengqikj.top/Article/details/gtyneuyuer.html

[S05] C：字符串长度
来源：http://dali.yonumen.top/Article/details/gtdrwiccnw.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gtzdgvjrtf.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtbcbqelzr.html

strcmp(a, b) == 0
来源：http://dali.fzhhl.top/Article/details/gtiykfbaaq.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gtuwezoxzn.html


<!-- 参考信息 -->