代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zycfv.cn/Article/details/gtcmomvymv.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gthqasroik.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gtxdcjmbzb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtqocglzdh.html

[Q36] 左连接
来源：http://dali.haohaochexian.top/Article/details/gtmdwcbiwq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtejgxryvu.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gtiqsnkrbt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gtefbxefjw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgufenzy.top/Article/details/gtayiiqlyr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.redwolf501.top/Article/details/gtcyumzlff.html

[Q39] 自连接（查上下级）
来源：http://dali.redwolf501.top/Article/details/gtacwvcolx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gtycqogbsb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gtiobmthnr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xinyue.icu/Article/details/gtrbnicxvm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ehwqpu.com/Article/details/gtsihpkvhl.html

[Q41] 多表连接
来源：http://dali.zhongyouzk.top/Article/details/gtodduxuvm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuanzhike.top/Article/details/gthtbzxhvg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhiwuduotai.top/Article/details/gtwjyhkzxg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuanzx.com/Article/details/gtiwchqwip.html

[Q42] 连接条件附加过滤
来源：http://dali.sweek.top/Article/details/gtrcjfqvit.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gtcedsbxwp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.kuanghao11.cn/Article/details/gtizkygcyp.html

[Q43] 标量子查询
来源：http://dali.yueranfly.top/Article/details/gtwjyugfsh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gtdkgsiktu.html

[Q44] IN 子查询
来源：http://dali.jqgfzy.top/Article/details/gtgifocsrm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangshuangyany.cn/Article/details/gtryarqasg.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gtwlaljqlb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtmaoxnfvq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dianchejie.cn/Article/details/gtxgytoerm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gtxzmzbkea.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gtveijxvlj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jianghu66.top/Article/details/gtyfedtrhw.html

[Q48] CTE 公用表表达式
来源：http://dali.haohaochexian.top/Article/details/gtzfxwbvci.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gtzwikrkfh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtorjaqkdf.html

[Q49] 更新单行
来源：http://dali.jiagoushi.top/Article/details/gtettnlmme.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusxltfnf.html

[Q50] 批量更新
来源：http://dali.sweek.top/Article/details/gtjbvsocul.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gtbcufkttv.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gthsrvrjba.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gtuvdpuenj.html

[Q52] 删除指定行
来源：http://dali.nanxinkj.top/Article/details/gtwwijxfvd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtstytcsmv.html

[Q53] 按条件删除
来源：http://dali.xuetiantiany.cn/Article/details/gtpjzequkd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtliuhmxib.html

[Q54] 清空表
来源：http://dali.shangyingyoupin.top/Article/details/gtmdltkmvw.html

TRUNCATE TABLE logs;
来源：http://dali.chenlongwang.top/Article/details/gtqvtrbefh.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gtxowejerx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmbukjtj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tianlin.xyz/Article/details/gttwfwfcpg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtmjltmdiq.html

[Q57] 行号
来源：http://dali.pengpengdd.cyou/Article/details/gtnbguslvj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.c1oappe.top/Article/details/gtawnrhjhr.html

[Q58] 累计求和
来源：http://dali.yj20258888.top/Article/details/gtczmhfjgl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtrlznhkkp.html

[Q59] 分组内累计
来源：http://dali.xinyue.icu/Article/details/gtsxoxdged.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gthivfowvg.html

[Q60] 取上一行 / 下一行
来源：http://dali.bjfxy.top/Article/details/gtxsbtwpho.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gtauxhuasl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwvobfzz.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gtizblcuqw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gttbocejhk.html

[Q62] 分组占比
来源：http://dali.xinyue.icu/Article/details/gtfuhvnqph.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gthhsvdibi.html

[Q63] 开启事务
来源：http://dali.fengsongda.top/Article/details/gtphpbhafj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tanke756.top/Article/details/gtcpootzxn.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gtgzjrhxha.html

COMMIT;
来源：http://dali.yueranfly.top/Article/details/gtxtldokzb.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gtzdpuedst.html

ROLLBACK;
来源：http://dali.haohaochexian.top/Article/details/gtnfsbgycr.html

[Q66] 行锁查询
来源：http://dali.svipenyu.cn/Article/details/gtlwgkkgjg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.kuanghao11.cn/Article/details/gtwiwrwmew.html

[Q67] 设置隔离级别
来源：http://dali.hfpthk.cn/Article/details/gtxhitggni.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegnsxvcy.html

[Q68] 保存点
来源：http://dali.daxiang520.top/Article/details/gthbjaccjc.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gtmsabhzam.html

ROLLBACK TO sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtwhxxnaow.html

[Q69] 查看执行计划
来源：http://dali.zdqjudy.top/Article/details/gtfspbuxgp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwazrxlge.html

[Q70] 更新统计信息
来源：http://dali.zhengqikj.top/Article/details/gtzgajemhf.html

ANALYZE TABLE users;
来源：http://dali.9152youxi.cn/Article/details/gtuhoytbqt.html

[Q71] 查看建表语句
来源：http://dali.kuanghao11.cn/Article/details/gtejhqpezy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuanzx.com/Article/details/gtygyadtfi.html

[Q72] 查看索引
来源：http://dali.birdmap.top/Article/details/gtdcmaysmf.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gtbyouggsz.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gtvpjryjpa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.vqdsnc.cn/Article/details/gtnhtscpek.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gtbepjfadm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gtroughtba.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvrggtug.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtjtlpokjm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtwevlhjjk.html

[Q76] 按天统计
来源：http://dali.pycfn.com/Article/details/gtizyldihw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtulrimxjo.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gtuayqgcmx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tanke756.top/Article/details/gtlgdauvpo.html

[Q78] 当前时间
来源：http://dali.tian-w.cn/Article/details/gtbwoqsvdp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daria6918.cn/Article/details/gtxeozrdos.html

[Q79] 字符串拼接
来源：http://dali.aizwys.cn/Article/details/gtzlusrels.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gtuehpkahh.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gtvhenqiwd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtmqcnzghf.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtzknyziih.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gtuuxtzksk.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gtvqrqiyix.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtdggrykcx.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtjsoxxvwc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtqberxwro.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gttdcsreyq.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtgvyrkmmt.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gtpbvpplcn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gzhubu.top/Article/details/gtxipeprft.html

[Q86] 读取 JSON 字段
来源：http://dali.jyoumei.cn/Article/details/gtqwigxmky.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gtxyonekuf.html

[Q87] JSON 字段做条件
来源：http://dali.daria6918.cn/Article/details/gtddescdfz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gtvlkqheac.html

[Q88] 行转列（条件聚合）
来源：http://dali.redwolf501.top/Article/details/gtuzrenhum.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gtoeuntnhn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gtwnrchvhn.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gtsllwonut.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gtqulruknj.html

[Q90] 生成序号列
来源：http://dali.xuanzx.com/Article/details/gtyuvjgwcp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gotoacloud.top/Article/details/gtgngldtdc.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtildvslnh.html

R. Bash 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxmxuzsc.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtzvmbdfjr.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gtphunzsep.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gtzpcpmlsk.html

set -euo pipefail
来源：http://dali.fengsongda.top/Article/details/gtudbbhrkh.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gtcuropsvx.html

name="Tom"; echo "$name"
来源：http://dali.zycfv.cn/Article/details/gtvhrtbuvy.html

[R03] 只读变量
来源：http://dali.jqgfzy.top/Article/details/gtnfuczgow.html

readonly PI=3.14
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyljbgqyu.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gtgyeekncn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sweek.top/Article/details/gtkwsvkahx.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gtezrwajha.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gtspgddchf.html

[R06] 判断命令是否存在
来源：http://dali.yangfankeji.com/Article/details/gtvmraywvh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtibjuvbxe.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gtdzivzjjn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtzmameqgm.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gtbfpctwbn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jyoumei.cn/Article/details/gtjjbmxtci.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtvhiluoqx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtjbjnvthl.html

[R10] 正则匹配
来源：http://dali.birdmap.top/Article/details/gttsinompi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtfjjlutse.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gtlnncrirx.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gtbnuicfta.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrunuvwl.html

stop)  echo "停止" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtfzwufrkb.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gtjicowniw.html

esac
来源：http://dali.ybcxt.top/Article/details/gtcanmukqn.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gtfoayrhin.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtufqmayij.html

[R13] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gtkqqnhnfg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gttvbwofza.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvysyfyq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gtmjvjtzhe.html

[R15] while 逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtvdaclnge.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtfywbfqpa.html

[R16] until 等待条件
来源：http://dali.c1oappe.top/Article/details/gtdjsgxdtw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdixgqmp.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotwjhsoa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.havefunace.top/Article/details/gtkebwbguo.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gtcpdzqczs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258.top/Article/details/gtlqjbfatz.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtvdkmrsnp.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gtvkyhohiw.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gtugbxwfmq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gttzenplcw.html

[R21] 字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtsxdyinfa.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gtjiawfdna.html

[R22] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gtdrjzydkh.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gtyjwblatd.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtpfductad.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gtqfuqwgyb.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gthantuhyo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gtzxperutb.html

[R25] 去后缀 / 去前缀
来源：http://dali.ppjwa.cn/Article/details/gtwoafoghl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hfpthk.cn/Article/details/gtawgbpmnx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gtlnxspeeb.html

now=$(date +%F); echo "$now"
来源：http://dali.hnxiangtu.top/Article/details/gteazmxyhy.html

[R27] 算术展开
来源：http://dali.dashuyun.cn/Article/details/gtprjuwuui.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gtqjaxovzm.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gtvofkychh.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gtavmfhnau.html

[R29] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gtybbjjnmk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pycfn.com/Article/details/gtbyqntsew.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gtnxinvloe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gtgklxvend.html

[R31] 局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgctwzqyh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gtikjvdtlc.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gtfifoqjxm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtjydcefap.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gtqebqhttr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shzxlz.cn/Article/details/gtmooewqks.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtjmojybjo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtgmoqbibf.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gtxggfomit.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.feifeiyinyue.top/Article/details/gtexcobjwu.html

[R36] 并发执行多个任务
来源：http://dali.yongpay.top/Article/details/gtjlpjzjcb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.haohaochexian.top/Article/details/gtztdtweeu.html

[R37] 把输出赋给变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gteiscgtjz.html

files=$(ls -1)
来源：http://dali.tianlin.xyz/Article/details/gtiwhfziqz.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gtkxtupzcx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gtqavsubkt.html

[R39] 重定向标准输出与错误
来源：http://dali.xziqi.cn/Article/details/gtnneyjyta.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzswdzusa.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gtbbxfbaxm.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gtafdnfzbj.html

[R41] 丢弃输出
来源：http://dali.ydzc1.top/Article/details/gthxphuxxl.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gtoapvmyoq.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gtagsfmoax.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gtblexueqg.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gtzafhxupx.html

find . -name "*.log" -type f
来源：http://dali.zdqjudy.top/Article/details/gtknlutedo.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gthpifunwa.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gthtwejwxt.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtnvxbmcxx.html

find . -name "*.tmp" -delete
来源：http://dali.xuanzx.com/Article/details/gtwsninmih.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gtyggmwjdu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.birdmap.top/Article/details/gtczwnlanm.html

[R47] sed 单行替换
来源：http://dali.aibaodan.cn/Article/details/gthnxfwmep.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gtozwxtvce.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gtlnkpbtdl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtvheestuc.html

[R49] awk 带条件
来源：http://dali.daria6918.cn/Article/details/gtontfpxic.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gtuidoohmp.html

[R50] awk 求和
来源：http://dali.dashuyun.cn/Article/details/gtyparfwer.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtmtqchuax.html

[R51] 排序去重取前几
来源：http://dali.yangfankeji.com/Article/details/gtzgnajwci.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hongshengwenyu.top/Article/details/gtwizxwymn.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gtyinqtldq.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gttvlqhdci.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gteidnpceh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofjnefgx.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gtcvpymeyc.html

diff a.txt b.txt
来源：http://dali.zycfv.cn/Article/details/gtejlsqovy.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtfhdiilil.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gtzaganeoc.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gtnhcrbwkb.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauvuzrlf.html

[R57] 远程执行命令
来源：http://dali.zhengqikj.top/Article/details/gtmzznmtef.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gtfyafboox.html

[R58] 下载文件
来源：http://dali.ppjwa.cn/Article/details/gtsocflwxi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gtvrqkdikq.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtrszgoubq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhoulong.xyz/Article/details/gtigdwaewm.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtpcobwckw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gtwcbdkopt.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gtgjjtmxuu.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gthseevmzp.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gttiixevdf.html

du -ah . | sort -rh | head -10
来源：http://dali.mhx1999.top/Article/details/gtdqfntnba.html

[R63] 内存与进程
来源：http://dali.dashuyun.cn/Article/details/gtkipjmcbq.html

free -h;  ps aux | grep nginx
来源：http://dali.cqqwz.cn/Article/details/gtspfpufbm.html

[R64] 结束进程
来源：http://dali.cqqwz.cn/Article/details/gtutbcchjv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gtasdkarzv.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gtebvibjze.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gtimoonhbj.html

[R66] 定时任务
来源：http://dali.yj20258.top/Article/details/gtnbdzlcvm.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gtiglejizz.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gtjslahmvd.html

openssl rand -hex 16
来源：http://dali.svipenyu.cn/Article/details/gtglzsoblt.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gtwgbanean.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gteaeqgnip.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmplypkp.html

head -c 16 /dev/urandom | base64
来源：http://dali.cashguo.top/Article/details/gtugdymspt.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtcdqgvhaz.html

date +%s;  date -d @1700000000
来源：http://dali.quarkkingdee.top/Article/details/gtukevbazi.html

[R71] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtclaqqiwj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cqqwz.cn/Article/details/gtfusxiaoq.html

[R72] 等待端口就绪
来源：http://dali.quarkkingdee.top/Article/details/gtmgbumywf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtrwuicdoc.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrthlrxm.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gthvxaelbn.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtxehiiryb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.smart0.xyz/Article/details/gtngdpxulf.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gtozekemhc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xinyue.icu/Article/details/gtfewrvnmz.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gthgtyuxqq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtdnhbnwnc.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gtyrgweggw.html

read -rp "请输入: " ans
来源：http://dali.sufxvd.cn/Article/details/gtnrfezexx.html

[R78] 交互式菜单
来源：http://dali.meibo888.top/Article/details/gtqaucrmqk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxieeezyx.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gtkvgrsxyp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuanzhike.top/Article/details/gtmifdujst.html

[R80] 查看脚本执行耗时
来源：http://dali.gotoacloud.top/Article/details/gtyvhtakiq.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gtvnooudvf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gthhgorpjd.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gtzuqvqwmr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtsaakbosm.html

[S01] C：Hello World
来源：http://dali.cheryme.top/Article/details/gtlremdvmh.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gtkwbdcfeu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gtadsbruab.html

[S02] C：变量与格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtknmbpexg.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtmmyysjhh.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtusxavqfj.html


<!-- 参考信息 -->