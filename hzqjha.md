代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtnqrlhqqy.html

[Q30] 分组统计
来源：http://dali.shanyushiyangtech.top/Article/details/gtsucsekcv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtljqwefzd.html

[Q31] 分组后过滤
来源：http://dali.tianlin.xyz/Article/details/gtuklqushn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gtlnutkiix.html

[Q32] 分组拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtpvmacrqi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcofntsca.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gtyordffyk.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gtezfibqwd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gtqtlqpbdj.html

[Q34] 每组取第一条
来源：http://dali.yonumen.top/Article/details/gtnsdcmoip.html

SELECT * FROM (
来源：http://dali.ppjwa.cn/Article/details/gtbekziqvn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tianlin.xyz/Article/details/gtnphgxmpw.html

) t WHERE rn = 1;
来源：http://dali.hnqzz.top/Article/details/gtjcniyokk.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gtmknymwzy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtidcndnpm.html

[Q36] 左连接
来源：http://dali.c1oappe.top/Article/details/gtiwiblcnx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtkxvhwexw.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gtdhsryope.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtwafjtcgm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ivvv.top/Article/details/gtvijojlep.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.316326.xyz/Article/details/gtxbniutpw.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gtrkpblafy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gthqlnukoq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gtccghvpoj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxinkj.top/Article/details/gtmqkfmzku.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fengsongda.top/Article/details/gtzjuolgcz.html

[Q41] 多表连接
来源：http://dali.pycfn.com/Article/details/gtzmvzkbvz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuanzhike.top/Article/details/gtyxwhbvsq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pengpengdd.cyou/Article/details/gtfmeixcya.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gtgunbnfos.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gtgnhygmfl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aizwys.cn/Article/details/gthumoonyi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gtrcrwdxkf.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gtfnmugkhv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gtkyhusxvt.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gtyhurqyus.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtklbbqxos.html

[Q45] EXISTS 判断存在
来源：http://dali.ivvv.top/Article/details/gtgkjpbdas.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtqnhxifme.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gtlasyvdhv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtaibinzxe.html

[Q47] 与平均值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiutfunem.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.0kj1m.cn/Article/details/gtslhfvfyr.html

[Q48] CTE 公用表表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrbuqycy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gogol.net.cn/Article/details/gtanlszjaj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenlongwang.top/Article/details/gtzlnuwerw.html

[Q49] 更新单行
来源：http://dali.smart0.xyz/Article/details/gtpbgdaahz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gtrtymbyck.html

[Q50] 批量更新
来源：http://dali.yangfankeji.com/Article/details/gtunezybyg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtxoettprp.html

[Q51] 用子查询更新
来源：http://dali.hnxiangtu.top/Article/details/gtsmbjdpph.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pycfn.com/Article/details/gtffuttwrc.html

[Q52] 删除指定行
来源：http://dali.cucudq.cn/Article/details/gtdvtawqko.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtzsvkajan.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gtqfkeuicw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gtzdketdih.html

[Q54] 清空表
来源：http://dali.iojbl.cn/Article/details/gtlkxycmpq.html

TRUNCATE TABLE logs;
来源：http://dali.yj202588.top/Article/details/gthxyknhbb.html

[Q55] 排名（并列占位）
来源：http://dali.sxryk.cn/Article/details/gtzshdwdnt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtnslgouki.html

[Q56] 密集排名（并列不占位）
来源：http://dali.svipenyu.cn/Article/details/gthonzwxkv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtpkxqsvdj.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupenwrvt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj202588.top/Article/details/gtnjqhqjak.html

[Q58] 累计求和
来源：http://dali.yuxming.cn/Article/details/gtkroeypla.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtazfesjqn.html

[Q59] 分组内累计
来源：http://dali.gogol.net.cn/Article/details/gtmbrnrxgs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gttbvdniuy.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gtsofoybcm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gtwknmzqob.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtbqismmer.html

[Q61] 移动平均
来源：http://dali.xylfe.cn/Article/details/gtqfuypfcd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjkywkws.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gtwxwmbine.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtnknmjiaq.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gtftwdtbep.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gtixextnuv.html

[Q64] 提交事务
来源：http://dali.ivvv.top/Article/details/gtxtzhjymt.html

COMMIT;
来源：http://dali.nanxinkj.top/Article/details/gthjbrxkcc.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gtexaeywod.html

ROLLBACK;
来源：http://dali.yuanzhike.top/Article/details/gttjbpxsid.html

[Q66] 行锁查询
来源：http://dali.gogol.net.cn/Article/details/gtopaanoah.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj202588.top/Article/details/gtsngcdcmf.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gtujtinska.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gtriegcacs.html

[Q68] 保存点
来源：http://dali.nanxuanxn.top/Article/details/gtlaosbucn.html

SAVEPOINT sp1;
来源：http://dali.havefunace.top/Article/details/gtjnmpfkcg.html

ROLLBACK TO sp1;
来源：http://dali.jianghu66.top/Article/details/gttsrwpvrd.html

[Q69] 查看执行计划
来源：http://dali.redwolf501.top/Article/details/gtesfkvobf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hongshengwenyu.top/Article/details/gtgcgfhmmc.html

[Q70] 更新统计信息
来源：http://dali.snrcjt.cn/Article/details/gtkfccbvpc.html

ANALYZE TABLE users;
来源：http://dali.cashguo.top/Article/details/gtymwaunnw.html

[Q71] 查看建表语句
来源：http://dali.yonumen.top/Article/details/gtnldvbmvb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgfzy.top/Article/details/gtikxwdyvf.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gttgovzeuo.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtwxgtpfje.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gtqwmikkme.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.bjfxy.top/Article/details/gtuehbcitx.html

[Q74] 强制使用索引
来源：http://dali.haohaochexian.top/Article/details/gtsqcthncd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cheryme.top/Article/details/gtdhpokvoz.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtygxadgtt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtiqtbtbya.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jlsjyb.cn/Article/details/gtyzbscdrs.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gtbsmtzxdn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuxming.cn/Article/details/gtbanjhvih.html

[Q77] 时间加减
来源：http://dali.guowangkeji.top/Article/details/gtcbuhwkcz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gtcennorgi.html

[Q78] 当前时间
来源：http://dali.svipenyu.cn/Article/details/gtxskquyua.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cashguo.top/Article/details/gtciqzjtyd.html

[Q79] 字符串拼接
来源：http://dali.fzhhl.top/Article/details/gtbfdipilj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.smart0.xyz/Article/details/gtybuqbnuz.html

[Q80] 字符串截取
来源：http://dali.yj202588.top/Article/details/gtbmebjdzw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gthncpoece.html

[Q81] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtzqzqkpal.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gttdbfegvf.html

[Q82] 字符长度与字节长度
来源：http://dali.guannengcc.top/Article/details/gtsbcqvgxu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtcuaodevl.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtvxbukfke.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtlxtdspzm.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gtijzfhsje.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtkxjwmkis.html

[Q85] 数值取整
来源：http://dali.yueranfly.top/Article/details/gtzvsyrhas.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gtscvoerrm.html

[Q86] 读取 JSON 字段
来源：http://dali.shzxlz.cn/Article/details/gtedfbqzrm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xylfe.cn/Article/details/gtspoabbdu.html

[Q87] JSON 字段做条件
来源：http://dali.yangfankeji.com/Article/details/gtfiistzwq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gtpzjxblkq.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gtxaxdvhzf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangdashe.top/Article/details/gtodlnglej.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gtgukhmech.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gtoftzluey.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fzhhl.top/Article/details/gtvrrierqf.html

[Q90] 生成序号列
来源：http://dali.yongpay.top/Article/details/gttpkwwuoy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gtwkppvbca.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbhrtyofw.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtpbkrcesg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtqekdefvw.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gtbboikjys.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gtcqpsuxkd.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gtulzjhqml.html

[R02] 变量赋值与使用
来源：http://dali.redwolf501.top/Article/details/gtdjjmrgkc.html

name="Tom"; echo "$name"
来源：http://dali.zycfv.cn/Article/details/gttopiqhhm.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gtdbtyghvg.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gtrcxrywss.html

[R04] 位置参数
来源：http://dali.gzhubu.top/Article/details/gtposypjow.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jianghu66.top/Article/details/gtylrecpwx.html

[R05] 参数默认值
来源：http://dali.yvedp.cn/Article/details/gtnogycjhx.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gtrmhwlcua.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gtnsjrpwne.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvwhuxeau.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gtvyaoabks.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gtecofdtfg.html

[R08] 数值比较
来源：http://dali.pengpengdd.cyou/Article/details/gthpcsggxf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.svipenyu.cn/Article/details/gtkzupjfon.html

[R09] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtdvzipnnr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gtwxbqtbpn.html

[R10] 正则匹配
来源：http://dali.smart0.xyz/Article/details/gtjvepdpnv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gtwnapdfih.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gttezvipnr.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gtxakpcvma.html

start) echo "启动" ;;
来源：http://dali.chenlongwang.top/Article/details/gtdgsyxppn.html

stop)  echo "停止" ;;
来源：http://dali.gotoacloud.top/Article/details/gtpmbvjosv.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gtffsaaolu.html

esac
来源：http://dali.fzhhl.top/Article/details/gtuastsmpo.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvbxdoeu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gtvhkohgdh.html

[R13] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthowyzsgz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gtothylkff.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gtkntcvemj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdiixgaeb.html

[R15] while 逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtadsqvmtd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gtwliwxlko.html

[R16] until 等待条件
来源：http://dali.jianghu66.top/Article/details/gtqignqdqp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gtutkztiti.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gtdilhozrq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daxiang520.top/Article/details/gtujeinrfv.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gtltxfgfgy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtbzdbhxtz.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtzkohwqal.html

echo "${#arr[@]}"
来源：http://dali.svipenyu.cn/Article/details/gtbttviocm.html

[R20] 关联数组（字典）
来源：http://dali.ybcxt.top/Article/details/gtadzwtfka.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gtndcuppau.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtwthdhxyh.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gtjniavahh.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtwpwgkkhs.html

echo "${s:0:5}"
来源：http://dali.quarkkingdee.top/Article/details/gtkdjxzhgr.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtuccjxzuw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gtptjaqxsk.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtuonvppac.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zycfv.cn/Article/details/gtdmrewjzw.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gticofqhrx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tianlin.xyz/Article/details/gtdbkvlphn.html

[R26] 命令替换
来源：http://dali.316326.xyz/Article/details/gtyphlidtx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gtsjzpmezb.html

[R27] 算术展开
来源：http://dali.ybcxt.top/Article/details/gtvfvuhitb.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gtovkvrqew.html

[R28] 浮点运算
来源：http://dali.zhixingplan.top/Article/details/gtzaujfacx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gtnncibpun.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtbbhlxone.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gtlgmaaqfw.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gtxburcvqv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gthrimvmmd.html

[R31] 局部变量
来源：http://dali.mhx1999.top/Article/details/gtbdjfopih.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gtmhpqwkwr.html

[R32] 参数个数校验
来源：http://dali.aizwys.cn/Article/details/gtxtjajchv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtmarzcina.html

[R33] 捕获错误并提示行号
来源：http://dali.ivvv.top/Article/details/gtcgfhbuma.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gtbzqajfem.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gtdiruolwn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtjzzsbplz.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtmusizaaa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gtfpjqcmmu.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gthkalzgvo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.meibo888.top/Article/details/gtjgxdxmlu.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gtmmfhlxxh.html

files=$(ls -1)
来源：http://dali.aizwys.cn/Article/details/gtibnopzzj.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gtnkmqxbfq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gtjfasvgfa.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gthqfypcww.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtvrpxnmxp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gtrogrvdel.html

echo "log" >> out.log
来源：http://dali.dianchejie.cn/Article/details/gtcehubisp.html

[R41] 丢弃输出
来源：http://dali.sweek.top/Article/details/gtflvpynur.html

cmd >/dev/null 2>&1
来源：http://dali.meibo888.top/Article/details/gtcferyudk.html

[R42] 输入重定向
来源：http://dali.c1oappe.top/Article/details/gtwhwtzbie.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gtuknpnaoq.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gtfcqxpxgi.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvoqaqlav.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gtmbjocjug.html

find . -mtime -7 -type f
来源：http://dali.snrcjt.cn/Article/details/gtbofyjerj.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gtrvybuozv.html

find . -name "*.tmp" -delete
来源：http://dali.xuanzx.com/Article/details/gtnjzfytlq.html

[R46] 递归替换文件内容
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwntmcqu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gtbgvguusw.html

[R47] sed 单行替换
来源：http://dali.xziqi.cn/Article/details/gtoefrhpal.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gtasaxtraa.html

[R48] awk 取指定列
来源：http://dali.haohaochexian.top/Article/details/gtneqnfhbb.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtaecccmxz.html

[R49] awk 带条件
来源：http://dali.hammf.cn/Article/details/gtkpuprfnu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gtnnjtvtya.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gtimsoqjsu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtwvzehcop.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gtggngpbru.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.0kj1m.cn/Article/details/gtqmtmmzmm.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gtejsgyjee.html

wc -l a.txt
来源：http://dali.wangdashe.top/Article/details/gtplrswmku.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gtmxsjbrny.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gtjluhzszp.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gtbdptmhkv.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gtefqonpvz.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gthktcvfcx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258888.top/Article/details/gtuidmafpy.html

[R56] 远程拷贝
来源：http://dali.yuanzhike.top/Article/details/gtnnobkhyx.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gtahhxhzws.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gtmvlatcwy.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gtixxztito.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaulzziqz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gaohongyu789.top/Article/details/gtkcqavymn.html

[R59] 发 POST JSON
来源：http://dali.birdmap.top/Article/details/gtohbskzfz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ehwqpu.com/Article/details/gtwxkwdhqi.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtlcvtweps.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzknjkth.html

[R61] 磁盘占用
来源：http://dali.smart0.xyz/Article/details/gteimdwyfk.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gtyxbflcsj.html

[R62] 找最占空间的文件
来源：http://dali.yj20258888.top/Article/details/gtpilsixly.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gtkglqcbcg.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gtwcilkitz.html

free -h;  ps aux | grep nginx
来源：http://dali.chenzaomai.com/Article/details/gtcvdrlabj.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gtviwzhxwb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gtppnlmnne.html

[R65] 查看端口占用
来源：http://dali.shangyingyoupin.top/Article/details/gtljxsalnx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gtarvwoobu.html

[R66] 定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gtfzelkeca.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gtxpfidwhf.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtnjrmpnll.html

openssl rand -hex 16
来源：http://dali.hammf.cn/Article/details/gtvjlivawy.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyvcoddo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gttrycvhbc.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gturwpfkxg.html

head -c 16 /dev/urandom | base64
来源：http://dali.yueranfly.top/Article/details/gtenvgkdoj.html

[R70] 时间戳与互转
来源：http://dali.daria6918.cn/Article/details/gtitwlwnds.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gtwmcsihfm.html

[R71] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtzourmnts.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gtinzbaiaa.html

[R72] 等待端口就绪
来源：http://dali.yvedp.cn/Article/details/gtrrxoeuoh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtnukfnstr.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gtstqccwuc.html

split -l 1000 big.log part_
来源：http://dali.yj20258888.top/Article/details/gtoakgqjlp.html

[R74] 批量重命名
来源：http://dali.ehwqpu.com/Article/details/gtrnmmgbhk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj202588.top/Article/details/gtnwhhrwru.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gtzcyivvea.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gtoctpqbkv.html

[R76] 使用临时文件
来源：http://dali.sufxvd.cn/Article/details/gtbxixtply.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtdgrytuun.html

[R77] 读取用户输入
来源：http://dali.bjfxy.top/Article/details/gtlnckppvo.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gtuglxmzsz.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrohwkqs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.havefunace.top/Article/details/gtunvmonol.html

[R79] 解析命令行选项
来源：http://dali.gogol.net.cn/Article/details/gtunrixuuv.html


<!-- 参考信息 -->