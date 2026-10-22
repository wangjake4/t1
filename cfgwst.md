代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjjwvcjs.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2wdpuldgz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2euqvuvli.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dianchejie.cn/Article/details/gt2nuxauehz.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gt2xgilbqqu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.birdmap.top/Article/details/gt2toueason.html

[Q34] 每组取第一条
来源：http://dali.fengsongda.top/Article/details/gt2znnwcfoi.html

SELECT * FROM (
来源：http://dali.pengpengdd.cyou/Article/details/gt2afyqvdrk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gt2ukcandul.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2msodahkf.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gt2rvyzhbhy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gt2hobvruxr.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gt2ulojviob.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gt2ddsuaiam.html

[Q37] 右连接
来源：http://dali.pycfn.com/Article/details/gt2mtlebqlw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gt2zbjbpdju.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258888.top/Article/details/gt2oyejbfvi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kaoznigg.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gt2gyumfxxg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.bjfxy.top/Article/details/gt2wmlakkst.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgufenzy.top/Article/details/gt2gxvjxsnh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gt2bbzoltye.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gt2xfbuspla.html

[Q41] 多表连接
来源：http://dali.yj202588.top/Article/details/gt2pnfklwwe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.smart0.xyz/Article/details/gt2kghdglfi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.redwolf501.top/Article/details/gt2qsuofqad.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgtpjzwa.html

[Q42] 连接条件附加过滤
来源：http://dali.sufxvd.cn/Article/details/gt2tdmwdiqh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gt2fpyjektj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhongyouzk.top/Article/details/gt2lqsnkzrg.html

[Q43] 标量子查询
来源：http://dali.yj20258888.top/Article/details/gt2ieuodedt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjcfuzhq.html

[Q44] IN 子查询
来源：http://dali.cheryme.top/Article/details/gt2mvfhcvdo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jianghu66.top/Article/details/gt2uqwfnevt.html

[Q45] EXISTS 判断存在
来源：http://dali.hnxiangtu.top/Article/details/gt2upbhaxtm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gt2eqiwwqjs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gt2bssfxswy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gt2npqgpvhz.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2qqqhtbib.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzcfqpxi.html

[Q48] CTE 公用表表达式
来源：http://dali.mhx1999.top/Article/details/gt2vhsbhvsg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gt2kscdjelt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gt2ipzrgxqj.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gt2fcvkkswu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gt2mcqdprty.html

[Q50] 批量更新
来源：http://dali.jianghu66.top/Article/details/gt2vdpjpxfu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cqqwz.cn/Article/details/gt2wuhnxrkq.html

[Q51] 用子查询更新
来源：http://dali.xziqi.cn/Article/details/gt2xngnhhjh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gt2vxxaairm.html

[Q52] 删除指定行
来源：http://dali.pycfn.com/Article/details/gt2syeqwycw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gt2pecqldgd.html

[Q53] 按条件删除
来源：http://dali.yj20258888.top/Article/details/gt2zmalzdyb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gt2psfxsoxl.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gt2ucqsjaop.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvctsmtg.html

[Q55] 排名（并列占位）
来源：http://dali.meibo888.top/Article/details/gt2hikaxfew.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gt2zqszbono.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gt2rofdrjja.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gt2cuejjffv.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gt2lxcnllsf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2lkmceljx.html

[Q58] 累计求和
来源：http://dali.jinqigufen.top/Article/details/gt2mcgzpjdn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2gshakucn.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gt2pcmxqhge.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2iyfbtcnr.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj202588.top/Article/details/gt2yopgrvyg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhoulong.xyz/Article/details/gt2gsphdwnw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2jsrvluui.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gt2rvrkodam.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2bwtsjwyo.html

[Q62] 分组占比
来源：http://dali.shuidangran.top/Article/details/gt2xfzwzdfv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gt2zxamqknm.html

[Q63] 开启事务
来源：http://dali.nanxuanxn.top/Article/details/gt2dkkfiqpo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xylfe.cn/Article/details/gt2lpfvaewp.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gt2kklzdysy.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gt2guaftwgf.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gt2lzqlwnxi.html

ROLLBACK;
来源：http://dali.quarkkingdee.top/Article/details/gt2oazanijo.html

[Q66] 行锁查询
来源：http://dali.tanke756.top/Article/details/gt2vfjciuqw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gt2wmceptyj.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwtaoudy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gt2oeyljcpg.html

[Q68] 保存点
来源：http://dali.iojbl.cn/Article/details/gt2rzrbapcq.html

SAVEPOINT sp1;
来源：http://dali.yueranfly.top/Article/details/gt2qvtxtuck.html

ROLLBACK TO sp1;
来源：http://dali.hywenlv.cn/Article/details/gt2epdkzcal.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gt2eouhkfmo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.bjfxy.top/Article/details/gt2dhlyviei.html

[Q70] 更新统计信息
来源：http://dali.yuxming.cn/Article/details/gt2jqfgwydj.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecqyuxvv.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gt2mbohidda.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zdqjudy.top/Article/details/gt2dssgorrw.html

[Q72] 查看索引
来源：http://dali.yj202588.top/Article/details/gt2trybcprd.html

SHOW INDEX FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2svdjollq.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdlkrxyy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gt2pnktuwif.html

[Q74] 强制使用索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jyirytym.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.quarkkingdee.top/Article/details/gt2lgdtqnrp.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2eclstnah.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gt2ywpsdqof.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cqqwz.cn/Article/details/gt2clwqwgnt.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gt2uuogmzlx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxuanxn.top/Article/details/gt2akcpmheu.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gt2vjwzcqdm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gt2vuonmpxj.html

[Q78] 当前时间
来源：http://dali.nanxinkj.top/Article/details/gt2zojesgoh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gt2hzhtlryb.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gt2ofwboyvz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258.top/Article/details/gt2vvlfsfoc.html

[Q80] 字符串截取
来源：http://dali.cucudq.cn/Article/details/gt2fhtnsffd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2xakhiunw.html

[Q81] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gt2igwhshxz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2rgtmfhos.html

[Q82] 字符长度与字节长度
来源：http://dali.xylfe.cn/Article/details/gt2ylkqtngp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2wrcpzact.html

[Q83] 大小写转换
来源：http://dali.sweek.top/Article/details/gt2bfsjcfzr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2llrqhesy.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gt2uazegyoo.html

SELECT TRIM(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2nebfrfrw.html

[Q85] 数值取整
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jndblyjz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hongshengwenyu.top/Article/details/gt2netdxfgw.html

[Q86] 读取 JSON 字段
来源：http://dali.0kj1m.cn/Article/details/gt2ntvybbfa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.meibo888.top/Article/details/gt2ujripjja.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gt2tcvxjqah.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xnzfndpy.html

[Q88] 行转列（条件聚合）
来源：http://dali.redwolf501.top/Article/details/gt2gdxlwkwi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gt2rajjltxd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gt2ivgkiakg.html

[Q89] 判断表是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwuwrnuw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cashguo.top/Article/details/gt2hsrgfyyr.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dypkrueo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gt2qrwrtcjp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2pwnrauzr.html

R. Bash 专题
来源：http://dali.smart0.xyz/Article/details/gt2zfvywfkh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2vpeqwnrq.html

[R01] shebang 与严格模式
来源：http://dali.jianghu66.top/Article/details/gt2hdiqyckl.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gt2nylxnjey.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqenuacv.html

[R02] 变量赋值与使用
来源：http://dali.iojbl.cn/Article/details/gt2xtsxfizi.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2temhiolo.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gt2udbikaxi.html

readonly PI=3.14
来源：http://dali.fengsongda.top/Article/details/gt2rsagpcmr.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gt2geynmapn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gt2fgqefren.html

[R05] 参数默认值
来源：http://dali.hnxiangtu.top/Article/details/gt2nqghduvx.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gt2tdwnvqsx.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gt2jbpaecbn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gt2icdyxwzk.html

[R07] if 判断文件
来源：http://dali.aibaodan.cn/Article/details/gt2qvmeurrm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2dtbkiigu.html

[R08] 数值比较
来源：http://dali.aizwys.cn/Article/details/gt2uygihyag.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2wmdwxihe.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gt2iylpplvr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gt2birdxpgu.html

[R10] 正则匹配
来源：http://dali.tianlin.xyz/Article/details/gt2unltutcp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ybcxt.top/Article/details/gt2hxemjypu.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gt2gwbdnnsy.html

case "$1" in
来源：http://dali.xuetiantiany.cn/Article/details/gt2dhtegpgs.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gt2sndhordz.html

stop)  echo "停止" ;;
来源：http://dali.cheryme.top/Article/details/gt2cmeggxgx.html

*)     echo "未知命令" ;;
来源：http://dali.pycfn.com/Article/details/gt2auzbjkcg.html

esac
来源：http://dali.bjfxy.top/Article/details/gt2ainuuxyc.html

[R12] for 遍历文件
来源：http://dali.yuxming.cn/Article/details/gt2oxnnqynk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gt2opnqoqkn.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hldfqrns.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gt2fxstwxet.html

[R14] C 风格 for
来源：http://dali.cucudq.cn/Article/details/gt2qhmpzqam.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gt2zjlinzqe.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2utmdogkd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gt2mfvmjikd.html

[R16] until 等待条件
来源：http://dali.jianghu66.top/Article/details/gt2sekoitch.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gt2vtkaszes.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gt2kuigsnah.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hfpthk.cn/Article/details/gt2xfwkwcwt.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gt2baleovge.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.redwolf501.top/Article/details/gt2khafwzlb.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gt2obyvbmth.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gt2fglwuzlt.html

[R20] 关联数组（字典）
来源：http://dali.gaohongyu789.top/Article/details/gt2apvsfmtt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sufxvd.cn/Article/details/gt2bbqebdvh.html

[R21] 字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gt2shmanmdf.html

echo "${#s}"
来源：http://dali.tianlin.xyz/Article/details/gt2yjanvjex.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gt2ekbsxyjn.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gt2xyvorlle.html

[R23] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gt2fyatgiij.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gt2pxwcdkfy.html

[R24] 大小写转换
来源：http://dali.tanke756.top/Article/details/gt2xxluyubo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gt2ctqfvfwj.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gt2mcrsnjxo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbjpluao.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gt2sdvetpym.html

now=$(date +%F); echo "$now"
来源：http://dali.snrcjt.cn/Article/details/gt2mpglpgiv.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gt2hinlssrx.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gt2sbbfmaus.html

[R28] 浮点运算
来源：http://dali.sxryk.cn/Article/details/gt2xqaahkol.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gt2mydisamb.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2vphetcjv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gt2khyxukxm.html

[R30] 函数返回状态码
来源：http://dali.pycfn.com/Article/details/gt2qxvnefbf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gt2hkovcsir.html

[R31] 局部变量
来源：http://dali.gzhubu.top/Article/details/gt2pvmhyfcr.html

f() { local x=1; echo "$x"; }
来源：http://dali.cqqwz.cn/Article/details/gt2pnvhkgsp.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gt2aeaxlekv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2bjolfhby.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ownxmaez.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgufenzy.top/Article/details/gt2tqxykvnz.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gt2ixwjhwpp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2csvkkklw.html

[R35] 后台执行并等待
来源：http://dali.wangdashe.top/Article/details/gt2udsnnjic.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xziqi.cn/Article/details/gt2btpiqfef.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gt2vgodbvgf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.0kj1m.cn/Article/details/gt2iigkliel.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gt2eqwgqovw.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gt2xqtlbasz.html

[R38] 管道串联
来源：http://dali.feifeiyinyue.top/Article/details/gt2evvclbgj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gt2ryfmlklv.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2iagnkrdh.html

cmd > out.log 2>&1
来源：http://dali.xylfe.cn/Article/details/gt2rcltpylm.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gt2qaertriq.html

echo "log" >> out.log
来源：http://dali.yvedp.cn/Article/details/gt2blwygplf.html

[R41] 丢弃输出
来源：http://dali.9152youxi.cn/Article/details/gt2zamehzbj.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gt2nrirxtyt.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gt2sbdjrkrq.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gt2xyeormry.html

[R43] 按名字查找文件
来源：http://dali.pycfn.com/Article/details/gt2rhjwcshp.html

find . -name "*.log" -type f
来源：http://dali.yuxming.cn/Article/details/gt2iqdiqcfo.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gt2boirxzwr.html

find . -mtime -7 -type f
来源：http://dali.aizwys.cn/Article/details/gt2gldhrcei.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gt2fgwenkwv.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gt2ccyzuznj.html

[R46] 递归替换文件内容
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqdkhhmw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenzaomai.com/Article/details/gt2imeogxoq.html

[R47] sed 单行替换
来源：http://dali.316326.xyz/Article/details/gt2llphpyhj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2safeuzpg.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gt2oedthexs.html

awk '{print $1, $3}' a.txt
来源：http://dali.ivvv.top/Article/details/gt2iyptghzk.html

[R49] awk 带条件
来源：http://dali.316326.xyz/Article/details/gt2odlxhbjz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gt2luumbbfv.html

[R50] awk 求和
来源：http://dali.0kj1m.cn/Article/details/gt2qjjrsowk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2lxfakmfw.html

[R51] 排序去重取前几
来源：http://dali.sweek.top/Article/details/gt2lpayubbm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.vqdsnc.cn/Article/details/gt2pwtwlryp.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmlswaei.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2ochuzgny.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gt2rulcsqig.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hammf.cn/Article/details/gt2trjaskgn.html

[R54] 比较两个文件
来源：http://dali.cucudq.cn/Article/details/gt2mvvmnhyn.html

diff a.txt b.txt
来源：http://dali.hfpthk.cn/Article/details/gt2dnyonjmn.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gt2zxwwvhoo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gt2ejegeouj.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gt2istthver.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gt2ufvrygdq.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gt2juaohjjc.html

ssh user@host 'uptime'
来源：http://dali.zhoulong.xyz/Article/details/gt2qtvckian.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gt2lryyjvqi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gt2zqrkfrby.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gt2vbstxppg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gt2cswalhmk.html

[R60] 只看 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gt2afpuixjk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.9152youxi.cn/Article/details/gt2foysrawz.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gt2mgaywwkr.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gt2xehbdqyb.html

[R62] 找最占空间的文件
来源：http://dali.guowangkeji.top/Article/details/gt2cocdqrcr.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gt2wvtbwczd.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gt2tnyeiqon.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gt2ihkibpsg.html

[R64] 结束进程
来源：http://dali.hywenlv.cn/Article/details/gt2ywrydkoz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gt2sterflpn.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gt2gihzopym.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gt2niqgoaly.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gt2fpqqtvpl.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gt2zxwsbxmx.html

[R67] 生成随机十六进制串
来源：http://dali.yongpay.top/Article/details/gt2bvgpyser.html

openssl rand -hex 16
来源：http://dali.hysaishi.cn/Article/details/gt2hmskhcpi.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gt2wmlbgvaz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2xvtgpifu.html

[R69] 生成随机密码
来源：http://dali.shangyingyoupin.top/Article/details/gt2vftjvkxj.html

head -c 16 /dev/urandom | base64
来源：http://dali.yangfankeji.com/Article/details/gt2qcaojkfr.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gt2puszlkbh.html

date +%s;  date -d @1700000000
来源：http://dali.hammf.cn/Article/details/gt2sukckqdx.html

[R71] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gt2dyelmmef.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.vqdsnc.cn/Article/details/gt2onvzmpqo.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gt2ihlwzqkq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gt2zevsmtvv.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gt2yqgzybhi.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gt2pgvypdqw.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gt2glhdbrlo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gt2jrvluzwk.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktqabtyw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gt2eisefdfb.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gt2bpfpxrdq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gt2gzrlcvdi.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvnayobr.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gt2kmvsjmnk.html

[R78] 交互式菜单
来源：http://dali.haohaochexian.top/Article/details/gt2ylrbvxid.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gogol.net.cn/Article/details/gt2ekwijuhg.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gt2uouezjnb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.iojbl.cn/Article/details/gt2zigxyimu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gt2hynierci.html

time ./run.sh
来源：http://dali.yj20258.top/Article/details/gt2omnxqchc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2tqsyarcm.html


<!-- 参考信息 -->