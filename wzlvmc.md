代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daxiang520.top/Article/details/gt2rbkizlts.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cqqwz.cn/Article/details/gt2zidhqbzh.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gt2fnppfbgg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.havefunace.top/Article/details/gt2wfvhaokw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gt2aduradko.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpmzpdvb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efzxncyt.html

[Q41] 多表连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2olmmnirw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tianlin.xyz/Article/details/gt2twzbxsyc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yanxiufei.cn/Article/details/gt2autdqzvh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihfpvqwx.html

[Q42] 连接条件附加过滤
来源：http://dali.yongpay.top/Article/details/gt2rwmjtunq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.iojbl.cn/Article/details/gt2lqooygkm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuanzx.com/Article/details/gt2pzbxppru.html

[Q43] 标量子查询
来源：http://dali.guannengcc.top/Article/details/gt2qgqaddjf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gt2gxjwarqm.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gt2vicifwys.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gt2ykwjfemx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gt2nwdtecps.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gt2sqjvsdbv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zdqjudy.top/Article/details/gt2xavlkrtz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gt2rpahggeq.html

[Q47] 与平均值比较
来源：http://dali.snrcjt.cn/Article/details/gt2hdferstg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpvfkes.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gt2bijvukil.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gt2yminhimq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.316326.xyz/Article/details/gt2drbuxyso.html

[Q49] 更新单行
来源：http://dali.dianchejie.cn/Article/details/gt2ishyqywp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gt2cbrxbycf.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gt2omeckyly.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ivvv.top/Article/details/gt2tmuxuabd.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gt2szwupjkt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtwiebsq.html

[Q52] 删除指定行
来源：http://dali.hammf.cn/Article/details/gt2zbmleakr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gt2yzqekudb.html

[Q53] 按条件删除
来源：http://dali.chenzaomai.com/Article/details/gt2ahafgnio.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.svipenyu.cn/Article/details/gt2fihquqvg.html

[Q54] 清空表
来源：http://dali.0kj1m.cn/Article/details/gt2iilrlnhs.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gt2sudgaryh.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gt2hcrkdxqw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yueranfly.top/Article/details/gt2rdypsuqk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.andypj.xyz/Article/details/gt2duuymovk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gt2akraipdy.html

[Q57] 行号
来源：http://dali.cucudq.cn/Article/details/gt2oomrjapd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2axainjvz.html

[Q58] 累计求和
来源：http://dali.gotoacloud.top/Article/details/gt2irrymswm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2kjmqffzy.html

[Q59] 分组内累计
来源：http://dali.birdmap.top/Article/details/gt2aysnnjbm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2jjcfqred.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhengqikj.top/Article/details/gt2xdbcizhp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gt2duhwnrwm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2tqumqwel.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gt2ytggltko.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2grgodygq.html

[Q62] 分组占比
来源：http://dali.316326.xyz/Article/details/gt2bcmglzsy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2giiyjgrc.html

[Q63] 开启事务
来源：http://dali.daria6918.cn/Article/details/gt2tglzvmxn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.kuanghao11.cn/Article/details/gt2wltkfeey.html

[Q64] 提交事务
来源：http://dali.nwbrower.top/Article/details/gt2klxaimgg.html

COMMIT;
来源：http://dali.cheryme.top/Article/details/gt2rvavgsqi.html

[Q65] 回滚事务
来源：http://dali.jinqigfzy.top/Article/details/gt2plbzzlrg.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gt2leqyrqwj.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gt2jnymplxl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sufxvd.cn/Article/details/gt2zijghnwm.html

[Q67] 设置隔离级别
来源：http://dali.yj202588.top/Article/details/gt2bpqtgzcd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258888.top/Article/details/gt2eyktgbyh.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gt2yyoisums.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gt2jjibwelo.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gt2yzrwgjvc.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gt2nneurmja.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuxming.cn/Article/details/gt2rskaqjwr.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxhjbnab.html

ANALYZE TABLE users;
来源：http://dali.zhoulong.xyz/Article/details/gt2kttlktjb.html

[Q71] 查看建表语句
来源：http://dali.yonumen.top/Article/details/gt2wlnofjcg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cashguo.top/Article/details/gt2sslhlbmo.html

[Q72] 查看索引
来源：http://dali.wangdashe.top/Article/details/gt2xeoikwjz.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2spsqteeu.html

[Q73] 查看表状态
来源：http://dali.gogol.net.cn/Article/details/gt2zcfaniah.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuanzx.com/Article/details/gt2yshfvfzi.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gt2kcnyhiuq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gt2fvukdrsm.html

[Q75] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2msbdioyx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2lluqwfpe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2damadkyd.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gt2vkmbgslx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.smart0.xyz/Article/details/gt2ftpetbsq.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gt2ienllixq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shzxlz.cn/Article/details/gt2rsteblyi.html

[Q78] 当前时间
来源：http://dali.yueranfly.top/Article/details/gt2iqdhtqve.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cqqwz.cn/Article/details/gt2dulwmvry.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gt2pxbvzoit.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixuepygx.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gt2pfqzdlbs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwqdzfqn.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gt2rkgximea.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2detfafsm.html

[Q82] 字符长度与字节长度
来源：http://dali.jianghu66.top/Article/details/gt2sadrfnme.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhxjkede.html

[Q83] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gt2ajwrdchs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2angxytrc.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hiljoujw.html

SELECT TRIM(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2vkxfimqe.html

[Q85] 数值取整
来源：http://dali.birdmap.top/Article/details/gt2gmiccslk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gt2zmjvkjji.html

[Q86] 读取 JSON 字段
来源：http://dali.hnxiangtu.top/Article/details/gt2hhpmyyqk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gt2xgfzgmrl.html

[Q87] JSON 字段做条件
来源：http://dali.sysykeji.top/Article/details/gt2kmabfxqp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gt2hahyppwz.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gt2esoxkawx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cdnleiting.top/Article/details/gt2nzynlrib.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2btmrnrzn.html

[Q89] 判断表是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2roloqrcr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sysykeji.top/Article/details/gt2cshxlxnt.html

[Q90] 生成序号列
来源：http://dali.daria6918.cn/Article/details/gt2irepwykt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.smart0.xyz/Article/details/gt2kcpdgmay.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2joaxumak.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gt2nbelbham.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmxhpnju.html

[R01] shebang 与严格模式
来源：http://dali.yonumen.top/Article/details/gt2rvplznhh.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gt2spildwtr.html

set -euo pipefail
来源：http://dali.ivvv.top/Article/details/gt2zbaszxjr.html

[R02] 变量赋值与使用
来源：http://dali.xinyue.icu/Article/details/gt2ujukonfa.html

name="Tom"; echo "$name"
来源：http://dali.yangfankeji.com/Article/details/gt2yhvnuwek.html

[R03] 只读变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2lqmkggju.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gt2wfpagjes.html

[R04] 位置参数
来源：http://dali.pycfn.com/Article/details/gt2vnbuhpee.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xziqi.cn/Article/details/gt2sezudqvs.html

[R05] 参数默认值
来源：http://dali.nanxinkj.top/Article/details/gt2xrapvkmf.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gt2ncrjabae.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gt2sxbjefdh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gt2tlndxeps.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gt2swypxmce.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yonumen.top/Article/details/gt2zsekqkfg.html

[R08] 数值比较
来源：http://dali.daxiang520.top/Article/details/gt2hmkczsuj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2mxkcbchs.html

[R09] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gt2lvmteuzm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2bhenpuwh.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmkkgyyg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sxryk.cn/Article/details/gt2sipvbaxp.html

[R11] case 多分支
来源：http://dali.jqgufenzy.top/Article/details/gt2gshljdzu.html

case "$1" in
来源：http://dali.hammf.cn/Article/details/gt2fwgowfbq.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gt2nijmieyv.html

stop)  echo "停止" ;;
来源：http://dali.c1oappe.top/Article/details/gt2tfmvotwc.html

*)     echo "未知命令" ;;
来源：http://dali.meibo888.top/Article/details/gt2shzcgmxa.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzuzuzcd.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gt2rptqvkla.html

for f in *.txt; do echo "$f"; done
来源：http://dali.svipenyu.cn/Article/details/gt2zryptvyi.html

[R13] for 计数循环
来源：http://dali.dianchejie.cn/Article/details/gt2awazkyse.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gt2flqocobm.html

[R14] C 风格 for
来源：http://dali.dianchejie.cn/Article/details/gt2nwnuhmdx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gt2lejetquh.html

[R15] while 逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2diilaknr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gt2kucwpjyp.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gt2pntkmjie.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gt2agipuxff.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gt2onmblwco.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gt2ggiemfja.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gt2iuhwpfxl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.9152youxi.cn/Article/details/gt2vlxvgjro.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gt2mhcnvgvs.html

echo "${#arr[@]}"
来源：http://dali.sysykeji.top/Article/details/gt2mzluewqi.html

[R20] 关联数组（字典）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejmzcsny.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gt2ugowdfoc.html

[R21] 字符串长度
来源：http://dali.xuanzx.com/Article/details/gt2kjfewzco.html

echo "${#s}"
来源：http://dali.mhx1999.top/Article/details/gt2ahwhzitj.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2kabhfsfe.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjdgkcee.html

[R23] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gt2saohtrew.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hywenlv.cn/Article/details/gt2abodbybm.html

[R24] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gt2pojtnnyc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gt2oitarrir.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gt2jbifsljv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gt2lhvqiqrx.html

[R26] 命令替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjgstmwg.html

now=$(date +%F); echo "$now"
来源：http://dali.yanxiufei.cn/Article/details/gt2jnvkifrv.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gt2kncimpcs.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gt2prpzpcwh.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gt2hsgqjmbr.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gt2muzsqokk.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nyhjmylq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gt2olwbsvoo.html

[R30] 函数返回状态码
来源：http://dali.aizwys.cn/Article/details/gt2itvubrha.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gt2xnyrxqta.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gt2bgmarcwp.html

f() { local x=1; echo "$x"; }
来源：http://dali.9152youxi.cn/Article/details/gt2lgccnono.html

[R32] 参数个数校验
来源：http://dali.yj20258.top/Article/details/gt2unoofoki.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2qidglzgy.html

[R33] 捕获错误并提示行号
来源：http://dali.zdqjudy.top/Article/details/gt2oespmzlm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gt2nkufamfy.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gt2mncvqbxf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gt2oerqopaa.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gt2txkemhap.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.iojbl.cn/Article/details/gt2yqbhxlav.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gt2hnvihjwy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.haohaochexian.top/Article/details/gt2rrktvxvm.html

[R37] 把输出赋给变量
来源：http://dali.jinqigufen.top/Article/details/gt2bqsyvkxd.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gt2frkcdier.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gt2aggrnxpo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gt2kdqebqyf.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gt2isncipwy.html

cmd > out.log 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gt2diwguget.html

[R40] 追加写日志
来源：http://dali.gaohongyu789.top/Article/details/gt2endiqllm.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gt2wubhyggs.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2igolzepl.html

cmd >/dev/null 2>&1
来源：http://dali.meibo888.top/Article/details/gt2fxcphtgb.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gt2ryvezqyb.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2ckppqetb.html

[R43] 按名字查找文件
来源：http://dali.guannengcc.top/Article/details/gt2ypozzpol.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gt2zbtdasjz.html

[R44] 按修改时间查找
来源：http://dali.c1oappe.top/Article/details/gt2gthmoljh.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gt2xudwasyk.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gt2lebkgqzs.html

find . -name "*.tmp" -delete
来源：http://dali.gzhubu.top/Article/details/gt2ypnybuth.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pvygyero.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigufen.top/Article/details/gt2yhicnkps.html

[R47] sed 单行替换
来源：http://dali.yangfankeji.com/Article/details/gt2ynlpbwcu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2kqsuqlfq.html

[R48] awk 取指定列
来源：http://dali.dashuyun.cn/Article/details/gt2tdxgbfts.html

awk '{print $1, $3}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2loohntow.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gt2llampvet.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cqqwz.cn/Article/details/gt2qulgnnng.html

[R50] awk 求和
来源：http://dali.andypj.xyz/Article/details/gt2almdsmbv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gt2xhcpqvmf.html

[R51] 排序去重取前几
来源：http://dali.9152youxi.cn/Article/details/gt2xxewaicg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gt2emxmrbgu.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gt2dnlrammj.html

wc -l a.txt
来源：http://dali.xylfe.cn/Article/details/gt2irlghzhz.html

[R53] 查看文件头与实时尾
来源：http://dali.tian-w.cn/Article/details/gt2xwweglim.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hywenlv.cn/Article/details/gt2qhnywhoq.html

[R54] 比较两个文件
来源：http://dali.cashguo.top/Article/details/gt2oxtunoao.html

diff a.txt b.txt
来源：http://dali.yonumen.top/Article/details/gt2eanzgijb.html

[R55] 压缩与解压
来源：http://dali.9152youxi.cn/Article/details/gt2ifkrxpws.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gt2gzpnzhji.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkpduqyn.html

scp file user@host:/path/
来源：http://dali.gaohongyu789.top/Article/details/gt2octyfllr.html

[R57] 远程执行命令
来源：http://dali.guowangkeji.top/Article/details/gt2vjnyeygt.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gt2xgadheyj.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gt2aoctpkom.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zdqjudy.top/Article/details/gt2riykryzb.html

[R59] 发 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gt2ysvrmijq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjgihihc.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gt2psxrjumu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgufenzy.top/Article/details/gt2xdtwtoye.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gt2ysnnvkvw.html

df -h;  du -sh *
来源：http://dali.wangdashe.top/Article/details/gt2kjsogzyq.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gt2allnhnmv.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwpykhns.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gt2ytdsevdk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmoardcu.html

[R64] 结束进程
来源：http://dali.quarkkingdee.top/Article/details/gt2iatgiddf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gt2wraoceto.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gt2sclditqf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gt2jznlhila.html

[R66] 定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gt2ngegthar.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gt2opvcfzvs.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gt2jziuazpa.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gt2xjizocxq.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pbindhvp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gt2euwbzcfi.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gt2mwtnntyx.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gt2plpqnscv.html

[R70] 时间戳与互转
来源：http://dali.yj20258888.top/Article/details/gt2brnncpgh.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gt2gcqefjih.html

[R71] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2ymfospds.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.316326.xyz/Article/details/gt2ppfsbfqz.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gt2plubuail.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gt2jbqfjroj.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gt2oxqpcdnb.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljauyuqn.html

[R74] 批量重命名
来源：http://dali.hywenlv.cn/Article/details/gt2kcphmjbf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhixingplan.top/Article/details/gt2dzxehgbm.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gt2kgyjpsgq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sufxvd.cn/Article/details/gt2rbdgdzro.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gt2rteqojuh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gt2hynisdee.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gt2oldybcnc.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gt2ysbbiztb.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gt2eenxzdut.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guannengcc.top/Article/details/gt2uzicnorj.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gt2xyamblim.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuanzhike.top/Article/details/gt2yrylnuns.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gt2jeczcgkt.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gt2dzevupme.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2lmwyggzv.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gt2vvpdlsss.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2fqigkqud.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2yougjpyt.html

#include <stdio.h>
来源：http://dali.jqgufenzy.top/Article/details/gt2ynuxourq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.havefunace.top/Article/details/gt2dwiisple.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gt2ydffbjos.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bndoknru.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gt2hatrzdfw.html

int x; scanf("%d", &x);
来源：http://dali.sufxvd.cn/Article/details/gt2ovmiatgb.html

[S04] C：字符串复制
来源：http://dali.wangdashe.top/Article/details/gt2xtgqmmyj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2dqmwzabz.html

[S05] C：字符串长度
来源：http://dali.guowangkeji.top/Article/details/gt2pqosjhyc.html

strlen(s)
来源：http://dali.xuanzx.com/Article/details/gt2rjppqldm.html

[S06] C：字符串比较
来源：http://dali.birdmap.top/Article/details/gt2hscjiquy.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gt2fijkivfn.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gt2sabpiogq.html


<!-- 参考信息 -->