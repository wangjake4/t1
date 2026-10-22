代发 wailian999

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gt2csirklmw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gt2pcpuyqbw.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjbwujts.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gt2brgqpzgj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gt2yqvdabng.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gt2ppalrgge.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrogbmhc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258888.top/Article/details/gt2elvetypx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2eeqgleua.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gt2yfkrzqzp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gt2phvzlghi.html

[Q41] 多表连接
来源：http://dali.dianchejie.cn/Article/details/gt2efcjwqic.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gt2senvlazt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gt2evaoolmr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tian-w.cn/Article/details/gt2rrmsugxf.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gt2olmhxqio.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gt2zfqugkkr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gt2ucmqazhl.html

[Q43] 标量子查询
来源：http://dali.shzxlz.cn/Article/details/gt2lkfmmlzd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gt2hnhceeqd.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gt2ntdcunxx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gt2dkhtwuoz.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gt2ytjwvyny.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gt2luokdreh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yangfankeji.com/Article/details/gt2pyflyrow.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gt2bzvxebly.html

[Q47] 与平均值比较
来源：http://dali.shzxlz.cn/Article/details/gt2pjgxnhaf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenlongwang.top/Article/details/gt2txybuvwe.html

[Q48] CTE 公用表表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2owkdjbcs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gt2dmozlvcl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gt2gqazkvgx.html

[Q49] 更新单行
来源：http://dali.yj20258.top/Article/details/gt2cfhhynwe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gt2gyylipoq.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gt2bwiklavk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gt2ijkyzpyz.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gt2ghusbcbr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gt2uahcmdre.html

[Q52] 删除指定行
来源：http://dali.xziqi.cn/Article/details/gt2sstmgctn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkmlgbkl.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gt2gkuxkjqq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gt2qhiyqwme.html

[Q54] 清空表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ifrlukqn.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gt2uqowlwwm.html

[Q55] 排名（并列占位）
来源：http://dali.hysaishi.cn/Article/details/gt2urwwhcuv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gt2kdojibpe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gt2xftvdogq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gt2vojtfodv.html

[Q57] 行号
来源：http://dali.gotoacloud.top/Article/details/gt2tntcvkdg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2cwahaeal.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gt2rbvglfgb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2bobozeek.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gt2mjoqjyzy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2xgvgxeee.html

[Q60] 取上一行 / 下一行
来源：http://dali.xylfe.cn/Article/details/gt2lmhydlfe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xylfe.cn/Article/details/gt2rgjudura.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2qgzrvfna.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jwllpesh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2uspecbvq.html

[Q62] 分组占比
来源：http://dali.zhixingplan.top/Article/details/gt2uaxgwxby.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2zwccdoae.html

[Q63] 开启事务
来源：http://dali.9152youxi.cn/Article/details/gt2ncuaeikl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.kuanghao11.cn/Article/details/gt2kzoaepdd.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmwfwere.html

COMMIT;
来源：http://dali.guowangkeji.top/Article/details/gt2usramgki.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gt2sadxmydv.html

ROLLBACK;
来源：http://dali.aibaodan.cn/Article/details/gt2poywbnum.html

[Q66] 行锁查询
来源：http://dali.nanxinkj.top/Article/details/gt2cxhjowjw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.bjfxy.top/Article/details/gt2rugbgmak.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gt2xhkxascf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yongpay.top/Article/details/gt2ofhapnfa.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gt2sefiyets.html

SAVEPOINT sp1;
来源：http://dali.cheryme.top/Article/details/gt2izvxdkop.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gt2bdiztupm.html

[Q69] 查看执行计划
来源：http://dali.jianghu66.top/Article/details/gt2xfnpbiin.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gt2fhkrxmbp.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gt2pblqoupm.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gt2cpyhsqxn.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gt2plantdxl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shuidangran.top/Article/details/gt2ffxidcdi.html

[Q72] 查看索引
来源：http://dali.ydzc1.top/Article/details/gt2bbkurjik.html

SHOW INDEX FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2xzulphga.html

[Q73] 查看表状态
来源：http://dali.xylfe.cn/Article/details/gt2pwzymxsb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkfofli.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gt2qtvagvap.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cheryme.top/Article/details/gt2wkghvsrx.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2akokqenl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2pjmibqql.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.bjfxy.top/Article/details/gt2yagqajcq.html

[Q76] 按天统计
来源：http://dali.sufxvd.cn/Article/details/gt2gqxfqfez.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afmmjefz.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gt2ffajctod.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gt2epnxnhez.html

[Q78] 当前时间
来源：http://dali.zhengqikj.top/Article/details/gt2mczzodrj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tanke756.top/Article/details/gt2valhoujc.html

[Q79] 字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwldoeit.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhiwuduotai.top/Article/details/gt2azeamogl.html

[Q80] 字符串截取
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvppqfww.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2rdygxmgb.html

[Q81] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gt2pdlxwmqp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2mdegioim.html

[Q82] 字符长度与字节长度
来源：http://dali.sxryk.cn/Article/details/gt2tajfykgr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2zvzknwzn.html

[Q83] 大小写转换
来源：http://dali.ivvv.top/Article/details/gt2bfyjrcrc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2wyflmnma.html

[Q84] 去除首尾空格
来源：http://dali.yanxiufei.cn/Article/details/gt2qbbdhfkq.html

SELECT TRIM(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2dhipucjd.html

[Q85] 数值取整
来源：http://dali.yvedp.cn/Article/details/gt2jzefwvpg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shzxlz.cn/Article/details/gt2ouskisuu.html

[Q86] 读取 JSON 字段
来源：http://dali.yj202588.top/Article/details/gt2rhsxysxb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2olmrcrfd.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gt2rrqvfrkj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xylfe.cn/Article/details/gt2nwwytobo.html

[Q88] 行转列（条件聚合）
来源：http://dali.ppjwa.cn/Article/details/gt2xdfhfqnf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hwgnjgqv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2xuhjvhhh.html

[Q89] 判断表是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2eahejdfq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gt2vpyuyayp.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gt2oeohjwxn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daxiang520.top/Article/details/gt2yjfaerml.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2xomtycey.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gt2pfdyspnl.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2gvqgskou.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gt2deordqcx.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tekqyrui.html

set -euo pipefail
来源：http://dali.jlsjyb.cn/Article/details/gt2qmjiqzpp.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxuzjlat.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gt2lagxlymf.html

[R03] 只读变量
来源：http://dali.yueranfly.top/Article/details/gt2kkzwlgzy.html

readonly PI=3.14
来源：http://dali.9152youxi.cn/Article/details/gt2yanftyie.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gt2mmvpfoab.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gt2isgfubfg.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gt2bseshfwk.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gt2gdvippiu.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gt2tvzunpdo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gt2mqlkektn.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gt2cndvjsjv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gt2gjfwdiim.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gt2ilxwzjkp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpefykac.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gt2wwoljqsv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gt2axrvcoiy.html

[R10] 正则匹配
来源：http://dali.sysykeji.top/Article/details/gt2tormfyaa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gt2bilnjeim.html

[R11] case 多分支
来源：http://dali.feifeiyinyue.top/Article/details/gt2pgnlbcps.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gt2loixztwg.html

start) echo "启动" ;;
来源：http://dali.shuidangran.top/Article/details/gt2xqkgzcyb.html

stop)  echo "停止" ;;
来源：http://dali.jqgfzy.top/Article/details/gt2djkutgsg.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gt2gqdjyjxy.html

esac
来源：http://dali.hongshengwenyu.top/Article/details/gt2ayakawch.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xogiupzn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xinyue.icu/Article/details/gt2huhmtvmk.html

[R13] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2nvdlcfoi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gt2twhocitv.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gt2midzkuom.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gt2rldllkbv.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gt2ukcfpzoc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gt2dccrdham.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gt2ewbfojab.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gt2qbpvoxmz.html

[R17] 数组定义与取值
来源：http://dali.9152youxi.cn/Article/details/gt2thqomltg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gt2sxpnuuog.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gt2xkotpbxk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gt2fxjfjzpy.html

[R19] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gt2bqhtoytq.html

echo "${#arr[@]}"
来源：http://dali.yongpay.top/Article/details/gt2kdgomawg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2izrswyrj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sysykeji.top/Article/details/gt2snhbpiug.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gt2ozkgigon.html

echo "${#s}"
来源：http://dali.mhx1999.top/Article/details/gt2qdtbexzf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2swktepgb.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqaawarp.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gt2txgmmvks.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ybcxt.top/Article/details/gt2fpiutarh.html

[R24] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gt2oysbrlnr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gyruprjy.html

[R25] 去后缀 / 去前缀
来源：http://dali.fzhhl.top/Article/details/gt2qgahovjz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gt2halageez.html

[R26] 命令替换
来源：http://dali.zhixingplan.top/Article/details/gt2qrdqvyqb.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gt2rbaoxnfb.html

[R27] 算术展开
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbpckogv.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gt2vmptwyvd.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gt2nscedefu.html

echo "scale=2; 10/3" | bc
来源：http://dali.yvedp.cn/Article/details/gt2sxspozyd.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gt2fldezlkk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daria6918.cn/Article/details/gt2eigptyrg.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwisjwfl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gt2trrkmrum.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gt2bowjhvnf.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gt2czdckcjw.html

[R32] 参数个数校验
来源：http://dali.yonumen.top/Article/details/gt2lnipblio.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gt2mtvqvifu.html

[R33] 捕获错误并提示行号
来源：http://dali.daria6918.cn/Article/details/gt2edyfgwhc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gt2oamotbar.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzodrzlj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxnasnaa.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gt2tjfvhcta.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.iojbl.cn/Article/details/gt2etmomnmp.html

[R36] 并发执行多个任务
来源：http://dali.gaohongyu789.top/Article/details/gt2giuuvqia.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gt2iviazilo.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gt2rptinhgj.html

files=$(ls -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gaqqgevw.html

[R38] 管道串联
来源：http://dali.wangdashe.top/Article/details/gt2yahgegkd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenzaomai.com/Article/details/gt2lnuznwcp.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gt2ngdgpnbp.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gt2tofnjzws.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gt2bdrdkqfa.html

echo "log" >> out.log
来源：http://dali.sxryk.cn/Article/details/gt2reqquhsy.html

[R41] 丢弃输出
来源：http://dali.gogol.net.cn/Article/details/gt2gqfyenkv.html

cmd >/dev/null 2>&1
来源：http://dali.xziqi.cn/Article/details/gt2sprpnzuj.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gt2ombfmkzb.html

wc -l < a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2kmujuucu.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gt2xagcklgs.html

find . -name "*.log" -type f
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqcidmlo.html

[R44] 按修改时间查找
来源：http://dali.vqdsnc.cn/Article/details/gt2oluyuugz.html

find . -mtime -7 -type f
来源：http://dali.yj20258.top/Article/details/gt2hfnodqrz.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gt2ptroooao.html

find . -name "*.tmp" -delete
来源：http://dali.iojbl.cn/Article/details/gt2xdvvxggt.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dapsokog.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gt2laplbsdc.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gt2hlbtqiwm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2siiovaul.html

[R48] awk 取指定列
来源：http://dali.chenzaomai.com/Article/details/gt2loeomjcp.html

awk '{print $1, $3}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2wqkyahae.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgbwfeuy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.0kj1m.cn/Article/details/gt2vzlhkclq.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gt2adztdtqy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2osjfpsjy.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etfvovvy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.smart0.xyz/Article/details/gt2zbksjncd.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gt2qltgqufj.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2ltibnywx.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gt2zytxihze.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sufxvd.cn/Article/details/gt2dqsxluvi.html

[R54] 比较两个文件
来源：http://dali.jyoumei.cn/Article/details/gt2sabexrfp.html

diff a.txt b.txt
来源：http://dali.ivvv.top/Article/details/gt2arygzmjj.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gt2pkybjlrl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqefptru.html

[R56] 远程拷贝
来源：http://dali.yuanzhike.top/Article/details/gt2dquhhgac.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gt2ylpvxbgc.html

[R57] 远程执行命令
来源：http://dali.yj20258.top/Article/details/gt2qxrzlzms.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gt2nzhbfrui.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gt2epknubzk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenlongwang.top/Article/details/gt2cnaqatjz.html

[R59] 发 POST JSON
来源：http://dali.fzhhl.top/Article/details/gt2yiaksbxu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gt2kzqhyytn.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gt2uvfwbaij.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gt2gzgvrnwo.html

[R61] 磁盘占用
来源：http://dali.ehwqpu.com/Article/details/gt2aoqawxmy.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gt2xivsgxoj.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gt2mcychjtl.html

du -ah . | sort -rh | head -10
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxnzeclw.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gt2opkehkwo.html

free -h;  ps aux | grep nginx
来源：http://dali.cashguo.top/Article/details/gt2cambygwb.html

[R64] 结束进程
来源：http://dali.cucudq.cn/Article/details/gt2kclptybe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gt2rhxrbbva.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gt2ieocsoxi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gt2pgqatyew.html

[R66] 定时任务
来源：http://dali.haohaochexian.top/Article/details/gt2mpdqwzxn.html

crontab -e;  crontab -l
来源：http://dali.zdqjudy.top/Article/details/gt2ljxkxftg.html

[R67] 生成随机十六进制串
来源：http://dali.zhengqikj.top/Article/details/gt2uezznkpv.html

openssl rand -hex 16
来源：http://dali.yonumen.top/Article/details/gt2cuqzdmor.html

[R68] 计算文件校验值
来源：http://dali.yj202588.top/Article/details/gt2rjfqmrnm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xicljhoi.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gt2clobuwmi.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gt2ebiqffqc.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gt2rdsiwtta.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gt2cbutvkwo.html

[R71] 日期格式化
来源：http://dali.pycfn.com/Article/details/gt2vnjncyph.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gt2xeyavzpg.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gt2dxnsdjdq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gt2khcbyvyo.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gt2pdxwgqma.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpvdjkdr.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gt2laynpnfm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhixingplan.top/Article/details/gt2yxuorwgh.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gt2lvlifrrq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfbwxwyl.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gt2csngezyb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2ixhfjuss.html

[R77] 读取用户输入
来源：http://dali.andypj.xyz/Article/details/gt2pbaugdhq.html

read -rp "请输入: " ans
来源：http://dali.yj20258.top/Article/details/gt2pdzkhckj.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gt2hjqsqjoc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yanxiufei.cn/Article/details/gt2gjkyqedj.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gt2itlbiilo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gt2rynmvisr.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gt2buyyvvzc.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gt2rxnpocaa.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2dttfhhgz.html

S. C / C++ 专题
来源：http://dali.shuidangran.top/Article/details/gt2hehexnjp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2lukptulp.html

[S01] C：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2iyugkpvq.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gt2iimecbcl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gt2gnotsndd.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2pfusemqs.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gt2zrhlgdqx.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gt2wzwvgxpf.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gt2pumukifu.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gt2gzsyvgcp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2stymeznq.html

[S05] C：字符串长度
来源：http://dali.yj202588.top/Article/details/gt2qdykqtqd.html


<!-- 参考信息 -->