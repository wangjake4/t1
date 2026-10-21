代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gttiuvzlmd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gtoyvrwsqo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zycfv.cn/Article/details/gthlquognp.html

[Q27] 条件计数
来源：http://dali.xinyue.icu/Article/details/gtfmhcouxs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gtwattaxol.html

[Q28] 求和与平均
来源：http://dali.aizwys.cn/Article/details/gtvxxwsheo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtwiqisbct.html

[Q29] 最大最小值
来源：http://dali.yonumen.top/Article/details/gtousgoouo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtdejqorag.html

[Q30] 分组统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemuvnwdz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gthuukfmwp.html

[Q31] 分组后过滤
来源：http://dali.zhongyouzk.top/Article/details/gtqtttmttg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ehwqpu.com/Article/details/gtjtjycqpq.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gtoissxzfn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtuhyzilai.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gtuxcvjlob.html

[Q33] 多列分组
来源：http://dali.jinqigfzy.top/Article/details/gtcymuzgik.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangdashe.top/Article/details/gtcnefyyyx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gtusssiglx.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gtnwwlexle.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258.top/Article/details/gtuehplitq.html

) t WHERE rn = 1;
来源：http://dali.sufxvd.cn/Article/details/gtdtssnnqy.html

[Q35] 内连接
来源：http://dali.cheryme.top/Article/details/gtgxsoufys.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gthtvehxzs.html

[Q36] 左连接
来源：http://dali.jlsjyb.cn/Article/details/gtuiverpwg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtcwxbdnmx.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gtgvrqfwnw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.quarkkingdee.top/Article/details/gtagxkqepv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yangfankeji.com/Article/details/gtcwxltvxy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tianlin.xyz/Article/details/gtzjchjluv.html

[Q39] 自连接（查上下级）
来源：http://dali.xylfe.cn/Article/details/gtkbuybner.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ehwqpu.com/Article/details/gtgcqzxqmi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yueranfly.top/Article/details/gtbyujxjyp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.redwolf501.top/Article/details/gtwciftjqz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fzhhl.top/Article/details/gtyrltpblg.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gtmyxoohvh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gthcmjpouf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gtysrgzdeo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gtbpafpdwz.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gtezcksdno.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jyoumei.cn/Article/details/gtsehcusav.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgfzy.top/Article/details/gtigfxwazg.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gtgoukpoth.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigufen.top/Article/details/gtchyxirxl.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gtfvzokyib.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daxiang520.top/Article/details/gtpkffooet.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawuaxxzl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gtddvokfjn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ehwqpu.com/Article/details/gtkfujoeuv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gtxhtdqrgj.html

[Q47] 与平均值比较
来源：http://dali.shzxlz.cn/Article/details/gtsmvaoead.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gogol.net.cn/Article/details/gtroqbqadd.html

[Q48] CTE 公用表表达式
来源：http://dali.yvedp.cn/Article/details/gtiyyznfpp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shzxlz.cn/Article/details/gtndmplaru.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gtszwicoui.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gtqclkqjvu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtcsgjfgsx.html

[Q50] 批量更新
来源：http://dali.yuanzhike.top/Article/details/gtmgurxkot.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtkgjvaprh.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gtypnkkwtx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hywenlv.cn/Article/details/gtqinfoupw.html

[Q52] 删除指定行
来源：http://dali.jqgfzy.top/Article/details/gtbjrsnnxm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtraranurc.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gtswztinbr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gtteirjxrd.html

[Q54] 清空表
来源：http://dali.hfpthk.cn/Article/details/gtueyauqgt.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gtlavwxabf.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gtgtbkmexs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258.top/Article/details/gtophqqpqg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtayxgvvnr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtyzlgtzdd.html

[Q57] 行号
来源：http://dali.cucudq.cn/Article/details/gtbmwswiyd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ivvv.top/Article/details/gtjgffpbnz.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gtblowjyyi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gttktlyucr.html

[Q59] 分组内累计
来源：http://dali.hfpthk.cn/Article/details/gtovgvamiy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtufzfmgph.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhixingplan.top/Article/details/gthznecozw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cdnleiting.top/Article/details/gtnmzvqffl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtfncjdump.html

[Q61] 移动平均
来源：http://dali.aibaodan.cn/Article/details/gtgminurjr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtpxthelnk.html

[Q62] 分组占比
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqeluftxr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtlcetdhfn.html

[Q63] 开启事务
来源：http://dali.hfpthk.cn/Article/details/gtdnowmuso.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gtzvgxqcxm.html

[Q64] 提交事务
来源：http://dali.fengsongda.top/Article/details/gteguxtdol.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtbfuvqnhh.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gtmqqjahid.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gtegjybkke.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gtvhrnjgxe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxinkj.top/Article/details/gtknxrrpbr.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gtvsmrsczj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnbnbopq.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gtnnlzmbmu.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gtnuxwcllm.html

ROLLBACK TO sp1;
来源：http://dali.jinqigufen.top/Article/details/gtsjbujvrp.html

[Q69] 查看执行计划
来源：http://dali.hfpthk.cn/Article/details/gtbgdjkhyk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gtfolrwfio.html

[Q70] 更新统计信息
来源：http://dali.wangdashe.top/Article/details/gtiikpyrxl.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtoqthheaj.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gtkzipajyx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gtpyqczyje.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gtfarsecfc.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtioiyjeve.html

[Q73] 查看表状态
来源：http://dali.guowangkeji.top/Article/details/gtktexlzqg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gtcrigbirs.html

[Q74] 强制使用索引
来源：http://dali.jqgfzy.top/Article/details/gtnsimyuoz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258.top/Article/details/gtpnzvcbua.html

[Q75] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtvmqgdlrw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtzalslydj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivsyohns.html

[Q76] 按天统计
来源：http://dali.316326.xyz/Article/details/gtzqqizcbh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cucudq.cn/Article/details/gtroifuesm.html

[Q77] 时间加减
来源：http://dali.sysykeji.top/Article/details/gtoypccacp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gtgcfmzwuq.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtnxwqllfi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tianlin.xyz/Article/details/gthtjhpawl.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gtnqnoapfx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.smart0.xyz/Article/details/gtqbawkdix.html

[Q80] 字符串截取
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbxkgjam.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yongpay.top/Article/details/gtfhsgwgja.html

[Q81] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gtbyxlbbnn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtdlkvatdm.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gtzjgdcgtx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtvfeecqhc.html

[Q83] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gtuiyducsn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtlpsebuzl.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gtfttddajl.html

SELECT TRIM(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtxocjkkzr.html

[Q85] 数值取整
来源：http://dali.chenzaomai.com/Article/details/gtklvqzehx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gtkapyllxf.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gtrxencyot.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xziqi.cn/Article/details/gttobscswj.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258.top/Article/details/gtoxmewilh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xinyue.icu/Article/details/gtyudnfvzm.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gtjydnvtbc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gtqqscnhxz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtgmffjcap.html

[Q89] 判断表是否存在
来源：http://dali.bjfxy.top/Article/details/gtcskaxnbh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guowangkeji.top/Article/details/gtsxxyprxc.html

[Q90] 生成序号列
来源：http://dali.cqqwz.cn/Article/details/gtnwdothwe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gttvoakpzw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtgrqcklos.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gtoajjhcjn.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtamalqxys.html

[R01] shebang 与严格模式
来源：http://dali.zhixingplan.top/Article/details/gtaarlirtf.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gtpfjgzate.html

set -euo pipefail
来源：http://dali.yueranfly.top/Article/details/gtvbushlyi.html

[R02] 变量赋值与使用
来源：http://dali.iojbl.cn/Article/details/gtbqazqcdk.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gtbiykwkdh.html

[R03] 只读变量
来源：http://dali.cqqwz.cn/Article/details/gtjhgwoaow.html

readonly PI=3.14
来源：http://dali.jyoumei.cn/Article/details/gtckkpiamr.html

[R04] 位置参数
来源：http://dali.snrcjt.cn/Article/details/gttctnjfxr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gtghdbvxnp.html

[R05] 参数默认值
来源：http://dali.yuanzhike.top/Article/details/gtvohvvrix.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gtemgxvzrk.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gtzcvheguf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gtyyzsdsge.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gtpnvrdkio.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenzaomai.com/Article/details/gteelgxzkq.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtqonbthag.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gtawwecfgk.html

[R09] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtjrcaowfl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sufxvd.cn/Article/details/gtsscjlyor.html

[R10] 正则匹配
来源：http://dali.guannengcc.top/Article/details/gtyajphuce.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gtoxudklzz.html

[R11] case 多分支
来源：http://dali.kuanghao11.cn/Article/details/gtciaueqsx.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtrugjtvad.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gthpawexgu.html

stop)  echo "停止" ;;
来源：http://dali.zycfv.cn/Article/details/gtubcrhniw.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtmonrtzjh.html

esac
来源：http://dali.yj20258.top/Article/details/gtnjjrnzlt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gtzskbumnk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigfzy.top/Article/details/gthmwsxnut.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gtslgnzdvh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtvpzwwlto.html

[R14] C 风格 for
来源：http://dali.shzxlz.cn/Article/details/gtldqglyfa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtyklppsok.html

[R15] while 逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtobuldgof.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gtwqdqstbv.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gtykqrogam.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtvgocskrr.html

[R17] 数组定义与取值
来源：http://dali.jyoumei.cn/Article/details/gtlzmsxfkn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daxiang520.top/Article/details/gtjltjyrvy.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwghkcdmn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtkgczqwsy.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gtgnuigful.html

echo "${#arr[@]}"
来源：http://dali.tanke756.top/Article/details/gtfjdyltnr.html

[R20] 关联数组（字典）
来源：http://dali.tianlin.xyz/Article/details/gtgbmuwhaf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gtfroiorlj.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtvgozziqc.html

echo "${#s}"
来源：http://dali.cqqwz.cn/Article/details/gtthwrunqi.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gtvnsxjtnp.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gtutrpwgot.html

[R23] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtghtoszah.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gtbolkoqvt.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtyoksuyan.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuanzx.com/Article/details/gtrrqnlxfa.html

[R25] 去后缀 / 去前缀
来源：http://dali.hammf.cn/Article/details/gtxbajloab.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.redwolf501.top/Article/details/gtxnnrzszo.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gtasctvoiq.html

now=$(date +%F); echo "$now"
来源：http://dali.cqqwz.cn/Article/details/gtatmzrnzq.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gtbltgsgtf.html

echo $((1 + 2 * 3))
来源：http://dali.sxryk.cn/Article/details/gtomzizbeh.html

[R28] 浮点运算
来源：http://dali.316326.xyz/Article/details/gtzdplvffd.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gtrlzputvh.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gtvscjqcnn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aibaodan.cn/Article/details/gtgkqoqtmm.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvimubrj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtogyuzkgj.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gtyohxdlip.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gtooixzxkm.html

[R32] 参数个数校验
来源：http://dali.zdqjudy.top/Article/details/gtskhgxmzr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtxojxwqbd.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gtottnlzvj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gtbceilepx.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gtoudnrmpw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gtpduggowa.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gtduhtcuep.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hysaishi.cn/Article/details/gtyakgnvsh.html

[R36] 并发执行多个任务
来源：http://dali.ivvv.top/Article/details/gtlkkjpfdt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtltcmrriq.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gthaehcqgj.html

files=$(ls -1)
来源：http://dali.gzhubu.top/Article/details/gtbxmemlwc.html

[R38] 管道串联
来源：http://dali.ehwqpu.com/Article/details/gtrgjencnj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gtgxszhjbi.html

[R39] 重定向标准输出与错误
来源：http://dali.shangyingyoupin.top/Article/details/gtdiaodgbj.html

cmd > out.log 2>&1
来源：http://dali.daxiang520.top/Article/details/gtozbqdaaz.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtufcqawbu.html

echo "log" >> out.log
来源：http://dali.dashuyun.cn/Article/details/gtuzwomyms.html

[R41] 丢弃输出
来源：http://dali.ybcxt.top/Article/details/gtmhdicvks.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtzbouwxcw.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gtfxnyskcz.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtgbkjrjkk.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gttrghszhr.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtkupifwwf.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gthjtkdebm.html

find . -mtime -7 -type f
来源：http://dali.zhixingplan.top/Article/details/gtqnvkvotx.html

[R45] 批量删除
来源：http://dali.hongshengwenyu.top/Article/details/gtejftuhue.html

find . -name "*.tmp" -delete
来源：http://dali.meibo888.top/Article/details/gtdctvxodn.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gtisdjjrxq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gterrafwom.html

[R47] sed 单行替换
来源：http://dali.yanxiufei.cn/Article/details/gteytavrpe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtvnvtbwty.html

[R48] awk 取指定列
来源：http://dali.gogol.net.cn/Article/details/gttegtumql.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtaanrecmr.html

[R49] awk 带条件
来源：http://dali.feifeiyinyue.top/Article/details/gtsduhlcjb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gtwlnrjmah.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gtrwykwiqm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtvbmnrrcz.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangtech.top/Article/details/gtorowlwtf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xziqi.cn/Article/details/gtecdrkxte.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gtytpgcscm.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gtrannzlfh.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gtxipknvzv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtwqwrekyh.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtfyrrcwkq.html

diff a.txt b.txt
来源：http://dali.jianghu66.top/Article/details/gtpcsazniw.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gtqyqxwsve.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gtawggvjww.html

[R56] 远程拷贝
来源：http://dali.nwbrower.top/Article/details/gtkzrqfhlk.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gtzddjxvfe.html

[R57] 远程执行命令
来源：http://dali.chenlongwang.top/Article/details/gtxfpjhlne.html

ssh user@host 'uptime'
来源：http://dali.zycfv.cn/Article/details/gtsygpzatg.html

[R58] 下载文件
来源：http://dali.cqqwz.cn/Article/details/gtmvrfdnbk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gtufifpwuk.html

[R59] 发 POST JSON
来源：http://dali.cashguo.top/Article/details/gtwqdbvbnp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gtnulbsgub.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtuupifsne.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gtpjbpthwc.html

[R61] 磁盘占用
来源：http://dali.yongpay.top/Article/details/gtdelnovvf.html

df -h;  du -sh *
来源：http://dali.yj20258888.top/Article/details/gtlhmjuyrs.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gtljcywdpl.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gtdfzvlhxq.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gtcsebdpzp.html

free -h;  ps aux | grep nginx
来源：http://dali.nwbrower.top/Article/details/gtnfdgtapr.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gtdbzduhqg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gtawqoosgl.html

[R65] 查看端口占用
来源：http://dali.hnxiangtu.top/Article/details/gtzjqjavcl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sufxvd.cn/Article/details/gtosmaamge.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gtyjydwnev.html

crontab -e;  crontab -l
来源：http://dali.wangshuangyany.cn/Article/details/gtvuymrcar.html

[R67] 生成随机十六进制串
来源：http://dali.tanke756.top/Article/details/gtgutpfvbx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gtdwfqjzmx.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtqgimexuf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtxyqwjojn.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gtiyvtremb.html

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gtwlzbvzyh.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gtqbfqeter.html

date +%s;  date -d @1700000000
来源：http://dali.ivvv.top/Article/details/gtzbammgso.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtzdtrfwsc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gthgkrnjke.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gteossziyj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtuhibhzbj.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gtixgirrck.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gtywajzmid.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gtjgixuvbx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gthiqtaasb.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtuuupcedz.html


<!-- 参考信息 -->