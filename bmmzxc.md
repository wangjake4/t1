代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gthycwplgf.html

) t WHERE rn = 1;
来源：http://dali.nanxinkj.top/Article/details/gtmlfuvzkn.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gtajcogkxi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtyrbidwgu.html

[Q36] 左连接
来源：http://dali.hongshengwenyu.top/Article/details/gtogrybwqw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdadiuqvo.html

[Q37] 右连接
来源：http://dali.svipenyu.cn/Article/details/gtxngdomqc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gzhubu.top/Article/details/gthvpmfmrt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gtpycvccfw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtonsgrqmk.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gtzaytrwde.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuxming.cn/Article/details/gtutedtayy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.kuanghao11.cn/Article/details/gthzqdyrgr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xylfe.cn/Article/details/gtdfcpejia.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.316326.xyz/Article/details/gtjyxbuftc.html

[Q41] 多表连接
来源：http://dali.chenjidiqi.icu/Article/details/gtvulqupgt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gthkhbikwf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gtzqnjiaxs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gteeruvlpr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gtwxqegcix.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbligfyym.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenzaomai.com/Article/details/gtxpkcblvb.html

[Q43] 标量子查询
来源：http://dali.yvedp.cn/Article/details/gtsnnonlut.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gzhubu.top/Article/details/gtgqnojdas.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gthwveymdu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daxiang520.top/Article/details/gtwfqpsfgh.html

[Q45] EXISTS 判断存在
来源：http://dali.tanke756.top/Article/details/gtokzpzcjy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtgqjlrtow.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dianchejie.cn/Article/details/gtsjwfofua.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gteiucndzr.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gttctgnukw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gtsiakqsgl.html

[Q48] CTE 公用表表达式
来源：http://dali.aizwys.cn/Article/details/gtgohwigmy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gtreeptnmi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yanxiufei.cn/Article/details/gtufebovyy.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gtxqlibxje.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtwwluotpk.html

[Q50] 批量更新
来源：http://dali.c1oappe.top/Article/details/gtsbneuhnk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gtiwssulgs.html

[Q51] 用子查询更新
来源：http://dali.hywenlv.cn/Article/details/gttsndryre.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtiqqvtgvw.html

[Q52] 删除指定行
来源：http://dali.gzhubu.top/Article/details/gtkkzxdewh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtoaehhabh.html

[Q53] 按条件删除
来源：http://dali.xuanzx.com/Article/details/gtoacrnuqq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtrtnyfcjq.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gtwpchnzzq.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gtcerikoiz.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtxuyaramr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtkoeenhwg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gtxasdrtrv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtddbnegmc.html

[Q57] 行号
来源：http://dali.daxiang520.top/Article/details/gtpsxfoalf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gtsoajrsen.html

[Q58] 累计求和
来源：http://dali.chenlongwang.top/Article/details/gtaiyiluek.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtaxdskxcj.html

[Q59] 分组内累计
来源：http://dali.vqdsnc.cn/Article/details/gtttljbnrl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtmnzuimdj.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gttoigagff.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.snrcjt.cn/Article/details/gtrvyuicke.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jianghu66.top/Article/details/gttorfpuhn.html

[Q61] 移动平均
来源：http://dali.yanxiufei.cn/Article/details/gttjrlmark.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtfsvymcbi.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gtlywiqljn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtabpeyjzi.html

[Q63] 开启事务
来源：http://dali.daria6918.cn/Article/details/gtjswkyxyo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gtwsdtmdcb.html

[Q64] 提交事务
来源：http://dali.gzhubu.top/Article/details/gtcsdonkyd.html

COMMIT;
来源：http://dali.yj20258888.top/Article/details/gtgcjfigdp.html

[Q65] 回滚事务
来源：http://dali.ybcxt.top/Article/details/gtygxorclu.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gtwlgmzhrt.html

[Q66] 行锁查询
来源：http://dali.zhoulong.xyz/Article/details/gtavrczbqt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258888.top/Article/details/gtbjfwtyaz.html

[Q67] 设置隔离级别
来源：http://dali.fzhhl.top/Article/details/gtmnjdhuzx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhixingplan.top/Article/details/gtyaplvzym.html

[Q68] 保存点
来源：http://dali.bjfxy.top/Article/details/gtrdyabnib.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gtxcfxusry.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gtwlvkmrtw.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gthanvqcgl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gthzemddio.html

[Q70] 更新统计信息
来源：http://dali.fzhhl.top/Article/details/gtvgoxqolu.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gtfysakztl.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gtwlhztpeq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gtyubjcgsx.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gtnfjrjich.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtjjiztvvw.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gtgkshvsaj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258.top/Article/details/gtkunobqgx.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gtmoyakcew.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhongyouzk.top/Article/details/gteuxlxywe.html

[Q75] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtppqewxmi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtnhiugsqn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gtukfawzmf.html

[Q76] 按天统计
来源：http://dali.daxiang520.top/Article/details/gtuazvhlga.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jlsjyb.cn/Article/details/gtmbszcdvl.html

[Q77] 时间加减
来源：http://dali.jyoumei.cn/Article/details/gtyoqsjzel.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sweek.top/Article/details/gtutlaksde.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gttrimbfsh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuanzhike.top/Article/details/gthgmdlaag.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmgungps.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xylfe.cn/Article/details/gtuelxylbh.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gtetewlbbr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttorbptnm.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtvspdttky.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtgjfisbpr.html

[Q82] 字符长度与字节长度
来源：http://dali.havefunace.top/Article/details/gtjrtzplno.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtuoskbsyo.html

[Q83] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtueeibaqz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gthlwmfrhs.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gtfygowpvu.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvliuphh.html

[Q85] 数值取整
来源：http://dali.yj20258.top/Article/details/gtkwwlawox.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gtczhxteok.html

[Q86] 读取 JSON 字段
来源：http://dali.tian-w.cn/Article/details/gtscarvnxq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gtxtiegapk.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gtqkmljjts.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.meibo888.top/Article/details/gtxmsrrceh.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuetiantiany.cn/Article/details/gthntddcqm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gtbrbwruhk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gtcddeileq.html

[Q89] 判断表是否存在
来源：http://dali.haohaochexian.top/Article/details/gtsxqjaxhv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hysaishi.cn/Article/details/gthmzjhfue.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gtsvqggmnc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yvedp.cn/Article/details/gtnkmrugsw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtkpesphtv.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gtclnieigw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvoudiwcj.html

[R01] shebang 与严格模式
来源：http://dali.sxryk.cn/Article/details/gtjulchcvs.html

#!/usr/bin/env bash
来源：http://dali.xziqi.cn/Article/details/gtqioxurdd.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gtfsudhgwj.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gtqpozevyb.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gtcxyxibmn.html

[R03] 只读变量
来源：http://dali.quarkkingdee.top/Article/details/gtkmlwfgpo.html

readonly PI=3.14
来源：http://dali.yonumen.top/Article/details/gtmjyvexyr.html

[R04] 位置参数
来源：http://dali.0kj1m.cn/Article/details/gtzwokgocs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gtxrqhksal.html

[R05] 参数默认值
来源：http://dali.aizwys.cn/Article/details/gtwubwcthq.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gtfrhsttsv.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gtnutgrdex.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtoaaowzvp.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gtwflmeaso.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuanzhike.top/Article/details/gtwuatprpv.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtpvswnmam.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gtqhzpgbcd.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gtbmqoalbz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gtjjcrfevf.html

[R10] 正则匹配
来源：http://dali.svipenyu.cn/Article/details/gtzdlgokkz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ppjwa.cn/Article/details/gtyikmaigz.html

[R11] case 多分支
来源：http://dali.zdqjudy.top/Article/details/gthkhgzobq.html

case "$1" in
来源：http://dali.ivvv.top/Article/details/gtarcvcmwp.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gtrsgcfpmo.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtncvcukzb.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gthmfegdic.html

esac
来源：http://dali.fzhhl.top/Article/details/gtgoavqsld.html

[R12] for 遍历文件
来源：http://dali.tianlin.xyz/Article/details/gtkugqhrah.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gtrovtpbhu.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gtcwhcizsi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtqpirvrxq.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gtffohmjrk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkuzzelw.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtxrslfjdz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.mhx1999.top/Article/details/gtspshnugb.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gthinhuiyz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtlrvesftg.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gtumwnahkt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hfpthk.cn/Article/details/gtszaxyldr.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gtbayryxmg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fzhhl.top/Article/details/gttapuabxj.html

[R19] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtlqbjxcty.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gtmqodhosd.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gthafcxofv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gttatncdjk.html

[R21] 字符串长度
来源：http://dali.fengsongda.top/Article/details/gtobosfroo.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gttlkdmwaz.html

[R22] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtgjlryvxa.html

echo "${s:0:5}"
来源：http://dali.yj20258888.top/Article/details/gtkuubsrgb.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtlplrhpqu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yonumen.top/Article/details/gtzhfsjrek.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gttkvpgnen.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gtibmzlnuu.html

[R25] 去后缀 / 去前缀
来源：http://dali.redwolf501.top/Article/details/gtlrgwufhz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenjidiqi.icu/Article/details/gtuwrfsxtw.html

[R26] 命令替换
来源：http://dali.sufxvd.cn/Article/details/gtftviszur.html

now=$(date +%F); echo "$now"
来源：http://dali.wangdashe.top/Article/details/gtrmnbxirz.html

[R27] 算术展开
来源：http://dali.aizwys.cn/Article/details/gtnoxrrdcc.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gtqytockys.html

[R28] 浮点运算
来源：http://dali.jianghu66.top/Article/details/gtfgbzpldo.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxinkj.top/Article/details/gthapbrkmd.html

[R29] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtmjjmbhqu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gtuybbbxcx.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewznqztb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gtiixjtgcs.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gtibdivlpg.html

f() { local x=1; echo "$x"; }
来源：http://dali.mhx1999.top/Article/details/gtioutyuuf.html

[R32] 参数个数校验
来源：http://dali.c1oappe.top/Article/details/gtpxqjdgav.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gtunkkcmbk.html

[R33] 捕获错误并提示行号
来源：http://dali.snrcjt.cn/Article/details/gtiiwgjuzz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tian-w.cn/Article/details/gteaqcatch.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gtjooltrpt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtiamfavdf.html

[R35] 后台执行并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtvotrrrfg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zycfv.cn/Article/details/gtappzvwuy.html

[R36] 并发执行多个任务
来源：http://dali.gaohongyu789.top/Article/details/gtoglldulw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pengpengdd.cyou/Article/details/gtavraiqjk.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gtmmercbea.html

files=$(ls -1)
来源：http://dali.cqqwz.cn/Article/details/gtqcobsamg.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gtbbbofybw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gtthanqrly.html

[R39] 重定向标准输出与错误
来源：http://dali.shzxlz.cn/Article/details/gtzcudxlgv.html

cmd > out.log 2>&1
来源：http://dali.tian-w.cn/Article/details/gtvozfeqtv.html

[R40] 追加写日志
来源：http://dali.hnqzz.top/Article/details/gtrvnlcjjl.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gtggmhozsr.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gthpabkuvp.html

cmd >/dev/null 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtqhjefkiw.html

[R42] 输入重定向
来源：http://dali.tianlin.xyz/Article/details/gtpabuslym.html

wc -l < a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtpbxttrrg.html

[R43] 按名字查找文件
来源：http://dali.cucudq.cn/Article/details/gtnrtohptd.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtctlpdvly.html

[R44] 按修改时间查找
来源：http://dali.zycfv.cn/Article/details/gtueuhkfze.html

find . -mtime -7 -type f
来源：http://dali.gzhubu.top/Article/details/gtsclhecdg.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gtnvcuywcp.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxmrzuqq.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gtwudrtcln.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gtbypuavge.html

[R47] sed 单行替换
来源：http://dali.sweek.top/Article/details/gtqtmwdime.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gtunmzhupr.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtrvwgfqvx.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirsjalmp.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtvgeyipcp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gtwijxbhob.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gtgtkfycja.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtdlggebio.html

[R51] 排序去重取前几
来源：http://dali.sweek.top/Article/details/gtkpuxykns.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.quarkkingdee.top/Article/details/gteiqqhgri.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gttbvbqezt.html

wc -l a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmmsuerf.html

[R53] 查看文件头与实时尾
来源：http://dali.mhx1999.top/Article/details/gtgikpqiej.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnxiangtu.top/Article/details/gtsvutceqg.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gtbddybukp.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gthwqboojs.html

[R55] 压缩与解压
来源：http://dali.316326.xyz/Article/details/gtzgqnefbh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gtlgyldick.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gtweomoire.html

scp file user@host:/path/
来源：http://dali.sufxvd.cn/Article/details/gtijetmdwx.html

[R57] 远程执行命令
来源：http://dali.yongpay.top/Article/details/gtzkkmecrf.html

ssh user@host 'uptime'
来源：http://dali.guannengcc.top/Article/details/gtqketuyks.html

[R58] 下载文件
来源：http://dali.yuanzhike.top/Article/details/gtpjdxwctw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gtifoqviih.html

[R59] 发 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtzskwcefe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gtzstfnuzw.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtrowvqvcu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gtknzvdypb.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gtjrkyvebj.html

df -h;  du -sh *
来源：http://dali.guowangkeji.top/Article/details/gtsyyghzih.html

[R62] 找最占空间的文件
来源：http://dali.yongpay.top/Article/details/gtqzehakig.html

du -ah . | sort -rh | head -10
来源：http://dali.cqqwz.cn/Article/details/gtmvqvyzdm.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gtqfnncjjz.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gtansdrkzg.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gtqxmntzup.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gtvbwmadzi.html

[R65] 查看端口占用
来源：http://dali.zhoulong.xyz/Article/details/gtdowpeerp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jlsjyb.cn/Article/details/gtlcebkrqs.html

[R66] 定时任务
来源：http://dali.0kj1m.cn/Article/details/gtvgfhkyue.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gtdaapkecs.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gtibxctmkt.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gtzekajaxx.html

[R68] 计算文件校验值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsefhptma.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hysaishi.cn/Article/details/gtfgiowtkn.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gtgewvvstp.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gtgezdqbid.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gtnhmuuejl.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtrckujpel.html

[R71] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlaivouw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gtukphfvuq.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gtbazwsfsi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtmnliwlzk.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gtjcmywzqh.html

split -l 1000 big.log part_
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunqgjoiw.html

[R74] 批量重命名
来源：http://dali.yueranfly.top/Article/details/gtbvstgguk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gtemxtsrye.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gtyiwesxxu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jlsjyb.cn/Article/details/gtfvitfaau.html

[R76] 使用临时文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavghcnts.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtelkvrnlj.html

[R77] 读取用户输入
来源：http://dali.9152youxi.cn/Article/details/gtfcnpznad.html

read -rp "请输入: " ans
来源：http://dali.aibaodan.cn/Article/details/gttsjoioin.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gtkfakvbxr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gtikagwqyc.html

[R79] 解析命令行选项
来源：http://dali.tianlin.xyz/Article/details/gtzbjclrmj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gtcnnfijhu.html

[R80] 查看脚本执行耗时
来源：http://dali.tian-w.cn/Article/details/gtemqbnhqc.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gtnsnfbaon.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkdixjkep.html

S. C / C++ 专题
来源：http://dali.tanke756.top/Article/details/gtcmbbfvyk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbuxradyr.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtaczeaegt.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gtiygzanim.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gtgjryextk.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtamtvuwbq.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gtnzxliscq.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gtaspcrxls.html


<!-- 参考信息 -->