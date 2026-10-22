代发 wailian999

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gtxncklvda.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtymnswpru.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gtkgygzavu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gtjcwhcghq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gtvikrvhwi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgbxtlcb.html

[Q39] 自连接（查上下级）
来源：http://dali.jianghu66.top/Article/details/gtrxwnbwbk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.redwolf501.top/Article/details/gtngtxagqt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigfzy.top/Article/details/gtkhijtqvy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gtmwhybiym.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gtcjxiutoy.html

[Q41] 多表连接
来源：http://dali.yanxiufei.cn/Article/details/gtwetdffym.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.snrcjt.cn/Article/details/gtvfxvxrop.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gtmyjruuwk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hfpthk.cn/Article/details/gtzgimbhar.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gtpuypzxyd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtfpqiisem.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sufxvd.cn/Article/details/gtcwessmfq.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnglxmor.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhengqikj.top/Article/details/gtgstefels.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gtcfsxotbb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gtsukvmuix.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtganiatgf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtmeigibwb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.c1oappe.top/Article/details/gtduckcoiy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtqocmhtrz.html

[Q47] 与平均值比较
来源：http://dali.fengsongda.top/Article/details/gtqcrunfmk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yonumen.top/Article/details/gtbvwbxebv.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gtguauhyhp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hammf.cn/Article/details/gtsesabclj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guowangkeji.top/Article/details/gtmnvgamoi.html

[Q49] 更新单行
来源：http://dali.iojbl.cn/Article/details/gtxbyxuggc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtnngmywcs.html

[Q50] 批量更新
来源：http://dali.hywenlv.cn/Article/details/gtshdxdwpd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gtfzeoupct.html

[Q51] 用子查询更新
来源：http://dali.xziqi.cn/Article/details/gtdbehgfmd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aibaodan.cn/Article/details/gtwgecogps.html

[Q52] 删除指定行
来源：http://dali.zdqjudy.top/Article/details/gtkksdqqlo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtorhcwowo.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gtyupzxqvj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jianghu66.top/Article/details/gtstimdeqk.html

[Q54] 清空表
来源：http://dali.andypj.xyz/Article/details/gtoqepwblv.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gtqgqhsgxa.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gtwomqsvqr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.redwolf501.top/Article/details/gtxaxrphry.html

[Q56] 密集排名（并列不占位）
来源：http://dali.snrcjt.cn/Article/details/gtozeadchc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtakubekdu.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjkikkex.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtuynuantg.html

[Q58] 累计求和
来源：http://dali.wangshuangyany.cn/Article/details/gterqcieoj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtdeecywpg.html

[Q59] 分组内累计
来源：http://dali.fengsongda.top/Article/details/gtkywipmbn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtxciepwiw.html

[Q60] 取上一行 / 下一行
来源：http://dali.gaohongyu789.top/Article/details/gtarwmmsap.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.316326.xyz/Article/details/gtfyypnldw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupwrfasn.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gttkqenwxr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtjbsvehih.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gtonvpwlxg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtfkeidxxb.html

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gtmafdlsnk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xylfe.cn/Article/details/gtavmbbsnu.html

[Q64] 提交事务
来源：http://dali.fengsongda.top/Article/details/gtfvyywyst.html

COMMIT;
来源：http://dali.nwbrower.top/Article/details/gtiqebqsgt.html

[Q65] 回滚事务
来源：http://dali.0kj1m.cn/Article/details/gtquwlztpp.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gtxmedbhbm.html

[Q66] 行锁查询
来源：http://dali.316326.xyz/Article/details/gtazknqevj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sysykeji.top/Article/details/gtcrwufebh.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gtyoiwszgq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigfzy.top/Article/details/gtvabakvvd.html

[Q68] 保存点
来源：http://dali.zycfv.cn/Article/details/gtfwdpfxal.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gtzpmpizfs.html

ROLLBACK TO sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtpoehqbuu.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gtriqndkbe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tian-w.cn/Article/details/gtdblxcdyy.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gtjbwujirg.html

ANALYZE TABLE users;
来源：http://dali.xuetiantiany.cn/Article/details/gtfeyyqraz.html

[Q71] 查看建表语句
来源：http://dali.sysykeji.top/Article/details/gtlulxzmtj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gtfumqmefa.html

[Q72] 查看索引
来源：http://dali.hnqzz.top/Article/details/gtgnrzrcyt.html

SHOW INDEX FROM users;
来源：http://dali.wangdashe.top/Article/details/gtjapnuayw.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gtbuqlduzc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gtashrgarm.html

[Q74] 强制使用索引
来源：http://dali.fzhhl.top/Article/details/gtbajkuetz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxkussxm.html

[Q75] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtjtilrbqs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtwegxdjmg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gtzseikpgu.html

[Q76] 按天统计
来源：http://dali.316326.xyz/Article/details/gtuobhgrvq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmicpnrh.html

[Q77] 时间加减
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpecbitx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gtxhfhjvxj.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gtzujwuefr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gtvkjrxoub.html

[Q79] 字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gtafsbtytu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gtsfcouqbx.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgssoinv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtptyozugg.html

[Q81] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtflrgegck.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sweek.top/Article/details/gtdsbkihoy.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gttgtxitlp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtmvefqefs.html

[Q83] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtziwgfzng.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gttcyvnahr.html

[Q84] 去除首尾空格
来源：http://dali.jqgfzy.top/Article/details/gttehaqker.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gticmoebed.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gtaeilpgjb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gtyjedquce.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gtznszwtzm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guowangkeji.top/Article/details/gtovpgsjor.html

[Q87] JSON 字段做条件
来源：http://dali.jlsjyb.cn/Article/details/gtkpkezrhl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sweek.top/Article/details/gtjeaqjdwr.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gtzifjcrtu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gogol.net.cn/Article/details/gtaoscsbom.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gtpwasigsj.html

[Q89] 判断表是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtmjkmkeno.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gtkdpgsuwr.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gtfxmrdyzt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guannengcc.top/Article/details/gtyhvjqmsv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtdelcvheb.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gtlttbvuat.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtfvfpzdzt.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtupfhcjvt.html

#!/usr/bin/env bash
来源：http://dali.yj20258.top/Article/details/gttdvgsuqk.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gtkstinius.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gthgtcvlkk.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gtzanxqrte.html

[R03] 只读变量
来源：http://dali.haohaochexian.top/Article/details/gtmgnxxncz.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtcqvbjgbh.html

[R04] 位置参数
来源：http://dali.jinqigufen.top/Article/details/gtuxzcdxnk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gtbmhqzucd.html

[R05] 参数默认值
来源：http://dali.zycfv.cn/Article/details/gtwmcqexnz.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gtbbtokepg.html

[R06] 判断命令是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtiuwwpcmh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtvxmomnsz.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gtrkdncfsd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenzaomai.com/Article/details/gtgwvmtesd.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gtsupxjguq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gtvpmxzygg.html

[R09] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gthakzdysp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtybfgarsz.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtntbvsnyk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.snrcjt.cn/Article/details/gtknxytggk.html

[R11] case 多分支
来源：http://dali.316326.xyz/Article/details/gtwopcurcn.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtjchjdovf.html

start) echo "启动" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbhjdisj.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gtemxzlxcm.html

*)     echo "未知命令" ;;
来源：http://dali.316326.xyz/Article/details/gthfcxyzsj.html

esac
来源：http://dali.sxryk.cn/Article/details/gtnwnnyakb.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gtqstutveb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gtkwupkooj.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtyqsrwbqr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtiiclwqlp.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gtvbvnbmpu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtabmyrcmd.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtdkojdlzl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvsgttwg.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gtkmdortra.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gtxwfnnkdk.html

[R17] 数组定义与取值
来源：http://dali.aibaodan.cn/Article/details/gteehptycs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258888.top/Article/details/gttwttlndw.html

[R18] 遍历数组
来源：http://dali.jqgfzy.top/Article/details/gtpbtbbusy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtawtdafzw.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtdcyqwfpz.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gtiirefnjy.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gtdyodlolp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtrsexznil.html

[R21] 字符串长度
来源：http://dali.jinqigufen.top/Article/details/gtfrelmpun.html

echo "${#s}"
来源：http://dali.xziqi.cn/Article/details/gtugixbhly.html

[R22] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gtfdgqzjuz.html

echo "${s:0:5}"
来源：http://dali.sufxvd.cn/Article/details/gtxctixnxx.html

[R23] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gtqpaykdoc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.andypj.xyz/Article/details/gtgoaibvjs.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtiovdazly.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnxiangtu.top/Article/details/gtyocbuljk.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihlrqnea.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.redwolf501.top/Article/details/gtjzmahulr.html

[R26] 命令替换
来源：http://dali.zhoulong.xyz/Article/details/gtphkvcbfw.html

now=$(date +%F); echo "$now"
来源：http://dali.jlsjyb.cn/Article/details/gtemgbgavr.html

[R27] 算术展开
来源：http://dali.jianghu66.top/Article/details/gtotfpwxya.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gtsliikell.html

[R28] 浮点运算
来源：http://dali.yangfankeji.com/Article/details/gttmennjrx.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuxming.cn/Article/details/gtogpwaluv.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gtswtonigz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hysaishi.cn/Article/details/gtfebxgdag.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gtsavzdpwr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.0kj1m.cn/Article/details/gtzatqoghj.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gtmiafkaea.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimkfrhlq.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gtddcxtvqc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtdaptaysq.html

[R33] 捕获错误并提示行号
来源：http://dali.xziqi.cn/Article/details/gtvghucwhe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.kuanghao11.cn/Article/details/gtyjypnuqb.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gtjjainqln.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtlqusedpa.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gtlpowcngj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gtktpfzvmj.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gtcyemcgii.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gttjtahdwj.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gtkvpzotxd.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtrrscgfgk.html

[R38] 管道串联
来源：http://dali.nwbrower.top/Article/details/gtkizzsqgw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gtcnaklrgy.html

[R39] 重定向标准输出与错误
来源：http://dali.jyoumei.cn/Article/details/gtdbsukizh.html

cmd > out.log 2>&1
来源：http://dali.316326.xyz/Article/details/gtsmdpzmue.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gtngztbqmh.html

echo "log" >> out.log
来源：http://dali.sxryk.cn/Article/details/gtudkvtmic.html

[R41] 丢弃输出
来源：http://dali.andypj.xyz/Article/details/gtbqbuonfn.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtrehgzghs.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gtnwiocraw.html

wc -l < a.txt
来源：http://dali.meibo888.top/Article/details/gtkmosfjoy.html

[R43] 按名字查找文件
来源：http://dali.zycfv.cn/Article/details/gtguleqphz.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gtoygiyoig.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gtdxobyyjc.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gtofjqdolt.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gtghvvihhs.html

find . -name "*.tmp" -delete
来源：http://dali.cdnleiting.top/Article/details/gtqssjdsfk.html

[R46] 递归替换文件内容
来源：http://dali.nwbrower.top/Article/details/gthvzdeamr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gtenxatfsn.html

[R47] sed 单行替换
来源：http://dali.sufxvd.cn/Article/details/gtkpzpcvyf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtayvvllhx.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gtrvdoooiw.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtgidwnhgu.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtactcerel.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gtbyricxcf.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gtzbhoeyou.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cashguo.top/Article/details/gtqayqkjgl.html

[R51] 排序去重取前几
来源：http://dali.jinqigufen.top/Article/details/gtkuwvgnom.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.smart0.xyz/Article/details/gtilxphuxe.html

[R52] 统计行数
来源：http://dali.cqqwz.cn/Article/details/gtckkkkvhm.html

wc -l a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtseflawym.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gtzexwelpu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gtyzyqopdp.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gtclhqhymt.html

diff a.txt b.txt
来源：http://dali.andypj.xyz/Article/details/gtewtvfwcd.html

[R55] 压缩与解压
来源：http://dali.fengsongda.top/Article/details/gtjvdsbber.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ydzc1.top/Article/details/gtahvfpfrv.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gtkvlhqfow.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gtvyyyrtcz.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpwvfssm.html

ssh user@host 'uptime'
来源：http://dali.zycfv.cn/Article/details/gtxjmflqga.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjjxjwlv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gtwarkgnsx.html

[R59] 发 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gtpaspqdsm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gtdkgzgjjx.html

[R60] 只看 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtsirysxbq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gtilkbllpi.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgixrghgn.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gttisfxxja.html

[R62] 找最占空间的文件
来源：http://dali.hongshengwenyu.top/Article/details/gtzwrskdeq.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gtpoflavls.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gtkzsbijcb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoshughw.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhhetdjf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sweek.top/Article/details/gtnrwqzxbl.html

[R65] 查看端口占用
来源：http://dali.havefunace.top/Article/details/gtvvyayegc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aibaodan.cn/Article/details/gttmfoljod.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtnpmhgwct.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gthptypbge.html

[R67] 生成随机十六进制串
来源：http://dali.aizwys.cn/Article/details/gtfpllhfch.html

openssl rand -hex 16
来源：http://dali.quarkkingdee.top/Article/details/gthbxslprg.html

[R68] 计算文件校验值
来源：http://dali.zhiwuduotai.top/Article/details/gtgrxnkdez.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhengqikj.top/Article/details/gtuuqemflh.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gtnzadwaws.html

head -c 16 /dev/urandom | base64
来源：http://dali.yonumen.top/Article/details/gthdypvqnc.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gtwpceezfr.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gtswrohrqs.html

[R71] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcwovtle.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gtiqsplvsk.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtlwtmvbjs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtnquogcxq.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gtrmbmoeoq.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdhcavcd.html

[R74] 批量重命名
来源：http://dali.sufxvd.cn/Article/details/gtdxzcezaw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ivvv.top/Article/details/gtlodupeys.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gtczozrbmk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtecdyjywg.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gtbjnismmb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiiesqtxu.html

[R77] 读取用户输入
来源：http://dali.nanxuanxn.top/Article/details/gtbrbqiuhj.html

read -rp "请输入: " ans
来源：http://dali.zhoulong.xyz/Article/details/gtvexuzynj.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gtrxsbcrdr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhiwuduotai.top/Article/details/gtiuihglou.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gtaieohxcq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gtrsktcxfk.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gtxtjyqcmt.html

time ./run.sh
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvxglcri.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtfahcnxnc.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtvbyfxbiu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtzgqamuba.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gthvneptdb.html

#include <stdio.h>
来源：http://dali.wangshuangyany.cn/Article/details/gtvlzbqwez.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daxiang520.top/Article/details/gtbdwcvicr.html

[S02] C：变量与格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtiybcrcej.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gtrwkgrbai.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gtujnqbxpj.html

int x; scanf("%d", &x);
来源：http://dali.guannengcc.top/Article/details/gtrgyxituk.html

[S04] C：字符串复制
来源：http://dali.tianlin.xyz/Article/details/gtadiiosbo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gtfzoubwaq.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtbdvgpvjs.html


<!-- 参考信息 -->