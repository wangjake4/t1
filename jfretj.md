代发 wailian999

[Q33] 多列分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppgjnoxj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ehwqpu.com/Article/details/gtnunsofbf.html

[Q34] 每组取第一条
来源：http://dali.hammf.cn/Article/details/gtxxowqpmq.html

SELECT * FROM (
来源：http://dali.xuanzx.com/Article/details/gtgyaqsarp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtghwqyckp.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gtjrdfzmka.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gtsxcxyunl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gtiqhwpznh.html

[Q36] 左连接
来源：http://dali.andypj.xyz/Article/details/gtzaxgyioy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtvieylaxw.html

[Q37] 右连接
来源：http://dali.chenzaomai.com/Article/details/gtdywvksie.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cdnleiting.top/Article/details/gtczyapdja.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gtaefjpebk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtrpggctfw.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gtdyqtkrsg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.redwolf501.top/Article/details/gtalfzznai.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sufxvd.cn/Article/details/gtzjlqfatv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gtoentwbkj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gtbqcnorck.html

[Q41] 多表连接
来源：http://dali.tianlin.xyz/Article/details/gtchrdvwhw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cqqwz.cn/Article/details/gtotiesgtb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gtrlcqzift.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigufen.top/Article/details/gtxfhsmtem.html

[Q42] 连接条件附加过滤
来源：http://dali.jyoumei.cn/Article/details/gtgdtszfkf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sysykeji.top/Article/details/gtqclutmmu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxuanxn.top/Article/details/gtkjowrxgz.html

[Q43] 标量子查询
来源：http://dali.nanxuanxn.top/Article/details/gtoubfisnl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258.top/Article/details/gtuofagett.html

[Q44] IN 子查询
来源：http://dali.birdmap.top/Article/details/gtynhhphrw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmneewbxk.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gtieyjffsx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtpoxoakuw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zdqjudy.top/Article/details/gtdesssqnj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtdrwrntwh.html

[Q47] 与平均值比较
来源：http://dali.tanke756.top/Article/details/gtcajhmugh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gtgzrkcwdx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhixingplan.top/Article/details/gthgifxpwi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.meibo888.top/Article/details/gtrqwxflnw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dashuyun.cn/Article/details/gtelmrhonb.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gtiamqiwzv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtpemoyxkm.html

[Q50] 批量更新
来源：http://dali.pycfn.com/Article/details/gtddvriheo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fengsongda.top/Article/details/gtecjzlgbz.html

[Q51] 用子查询更新
来源：http://dali.sxryk.cn/Article/details/gtfwwaywnt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gtqfqkaecd.html

[Q52] 删除指定行
来源：http://dali.cashguo.top/Article/details/gtciudfxjb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtdyjhhtts.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzijckcqi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtivjygzhv.html

[Q54] 清空表
来源：http://dali.0kj1m.cn/Article/details/gtqmkgdvag.html

TRUNCATE TABLE logs;
来源：http://dali.xuanzx.com/Article/details/gtcabagwlc.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gtkwihgqwc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtbblxrgfa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jiagoushi.top/Article/details/gthkmcbuxb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtroxmabog.html

[Q57] 行号
来源：http://dali.sweek.top/Article/details/gtpyjjgtyp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gtccitfuib.html

[Q58] 累计求和
来源：http://dali.hongshengwenyu.top/Article/details/gtslmgpwgg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtnxjythnb.html

[Q59] 分组内累计
来源：http://dali.havefunace.top/Article/details/gtumkeubyg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtofxmhthg.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gtouremjya.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.kuanghao11.cn/Article/details/gtvelgfxuc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtwflyjpud.html

[Q61] 移动平均
来源：http://dali.hywenlv.cn/Article/details/gtjtupblah.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtmaujswik.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtcrsnyiwp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtcusdvzyq.html

[Q63] 开启事务
来源：http://dali.ydzc1.top/Article/details/gtlcmuftzy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.smart0.xyz/Article/details/gtagmrprun.html

[Q64] 提交事务
来源：http://dali.zhongyouzk.top/Article/details/gtdlpdubcq.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gtxgfjajyy.html

[Q65] 回滚事务
来源：http://dali.nanxinkj.top/Article/details/gtthorohjp.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gtxuczepnu.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gtfviczmns.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gtdvivkkmq.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gtijmiqzyi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenzaomai.com/Article/details/gtrcvgzkfe.html

[Q68] 保存点
来源：http://dali.hammf.cn/Article/details/gtanldrlyl.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gttyiwtkob.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gtcsvazkwv.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gtbcvilvtx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gthhrbifov.html

[Q70] 更新统计信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrutvvnju.html

ANALYZE TABLE users;
来源：http://dali.ehwqpu.com/Article/details/gttuvevxvt.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gtnxhhbxix.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sysykeji.top/Article/details/gtyzzywuqr.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gtimkhnmuh.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gtawwjrrub.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gtpvoghthb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtsalghxsw.html

[Q74] 强制使用索引
来源：http://dali.jinqigfzy.top/Article/details/gtobgkpbdy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gtaajiotgr.html

[Q75] 日期格式化
来源：http://dali.sweek.top/Article/details/gtvabahsnt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtxgqliwjk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnagoupe.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gtbatftzxm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shangyingyoupin.top/Article/details/gtponkczis.html

[Q77] 时间加减
来源：http://dali.hongshengwenyu.top/Article/details/gtrrlavszp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sysykeji.top/Article/details/gttrkjqhis.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gthxtdktje.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gtranbjymi.html

[Q79] 字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtjonuxvjz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gtndbwyuqe.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gtqkktjjgw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtgjikekxk.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtxpralhjw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.c1oappe.top/Article/details/gtwqzhfefz.html

[Q82] 字符长度与字节长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfphfizir.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtpncqscgk.html

[Q83] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtgxreqqxw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtktusrvhv.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtoibuweax.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtwothupur.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gtgatlzbgy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gtzhgpmiyd.html

[Q86] 读取 JSON 字段
来源：http://dali.shangyingyoupin.top/Article/details/gthwqschmu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shuidangran.top/Article/details/gtrzjtmupp.html

[Q87] JSON 字段做条件
来源：http://dali.daria6918.cn/Article/details/gthfyaixnz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.vqdsnc.cn/Article/details/gtaeurjbgv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gtjntijucw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gtdmfncehv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtiilbfgor.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtyxkrubnn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gtwhyufgve.html

[Q90] 生成序号列
来源：http://dali.ehwqpu.com/Article/details/gtzcadufba.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.mhx1999.top/Article/details/gteqzteifq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtjmnymqpw.html

R. Bash 专题
来源：http://dali.pycfn.com/Article/details/gtyezmvkhw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttymlbevt.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gtnxlialur.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gtfokcqier.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gtkzbwigii.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gtlaeotrbu.html

name="Tom"; echo "$name"
来源：http://dali.shuidangran.top/Article/details/gtgijereom.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gtteomohrm.html

readonly PI=3.14
来源：http://dali.pycfn.com/Article/details/gtsaoedwpu.html

[R04] 位置参数
来源：http://dali.gogol.net.cn/Article/details/gtlxqhstja.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gtlskwczll.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gtvlezglyy.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gtbvqguzzd.html

[R06] 判断命令是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtcgrcrxps.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdxwzngla.html

[R07] if 判断文件
来源：http://dali.sxryk.cn/Article/details/gtqotgydot.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gtitoaieig.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gtbmqwdjhr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gtchsqysio.html

[R09] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtnuypwlza.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.redwolf501.top/Article/details/gtzbtnxusy.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gthqbnycst.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gtpdmtgiaj.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gtaflbqnue.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfrjkfdm.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtqwpmyeyt.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gtwdbjyyfg.html

*)     echo "未知命令" ;;
来源：http://dali.sysykeji.top/Article/details/gtgkwbgdzu.html

esac
来源：http://dali.ppjwa.cn/Article/details/gtaqvflqxo.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gtxwowmaqi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gtbpfqwwuy.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gtpkytmsab.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtqygxbwpe.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gtcokckafu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtwxunaibf.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtduwvkpgg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gtzepfqjzm.html

[R16] until 等待条件
来源：http://dali.c1oappe.top/Article/details/gtwdqzicaf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtnvuhepsy.html

[R17] 数组定义与取值
来源：http://dali.hnqzz.top/Article/details/gthpzljtkx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtvyfpdzid.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gtjygocgxh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuxming.cn/Article/details/gtsqvncyuj.html

[R19] 数组长度
来源：http://dali.hnqzz.top/Article/details/gtoypmlfil.html

echo "${#arr[@]}"
来源：http://dali.xziqi.cn/Article/details/gthwaznqgy.html

[R20] 关联数组（字典）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkntkrxv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.snrcjt.cn/Article/details/gtqgbrtbpo.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gtavphtvme.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gttagegsns.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtxludcurw.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gtqhrbvugg.html

[R23] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gtogovfdaq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258.top/Article/details/gtmzabwufg.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gttfjnktna.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpwrdvfy.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gtwhjhxshj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gtcqebkvmi.html

[R26] 命令替换
来源：http://dali.redwolf501.top/Article/details/gtlddidcfu.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gtlevidhdj.html

[R27] 算术展开
来源：http://dali.kuanghao11.cn/Article/details/gtysarrpfq.html

echo $((1 + 2 * 3))
来源：http://dali.dianchejie.cn/Article/details/gtydexovbn.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gtengxdqet.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gtvwczlrrm.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtrkoaxife.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gtljjdemrs.html

[R30] 函数返回状态码
来源：http://dali.jianghu66.top/Article/details/gtyzjpvlrx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gtwsvpfnls.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gthebjozao.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gtiblchihm.html

[R32] 参数个数校验
来源：http://dali.sysykeji.top/Article/details/gtbevkkzgh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtifouhzyn.html

[R33] 捕获错误并提示行号
来源：http://dali.sufxvd.cn/Article/details/gtmcuyyikl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtkxbjrjoq.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtenaemkhi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtiwcewwhn.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gturcxhrpc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258.top/Article/details/gtclvurbnr.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gtumtgtwdm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gtupjkyeni.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gtgdrduttg.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gtqmstsgop.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gtbjtlgnuo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fzhhl.top/Article/details/gtqykklwda.html

[R39] 重定向标准输出与错误
来源：http://dali.gogol.net.cn/Article/details/gtqoirgeuw.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtcnucyoak.html

[R40] 追加写日志
来源：http://dali.yonumen.top/Article/details/gtzoqgdbyo.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gtxccefysd.html

[R41] 丢弃输出
来源：http://dali.andypj.xyz/Article/details/gtxfyvmoou.html

cmd >/dev/null 2>&1
来源：http://dali.cqqwz.cn/Article/details/gtqgpujarc.html

[R42] 输入重定向
来源：http://dali.snrcjt.cn/Article/details/gtjsciecfo.html

wc -l < a.txt
来源：http://dali.smart0.xyz/Article/details/gtojhsjvlm.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gtptgodchu.html

find . -name "*.log" -type f
来源：http://dali.aizwys.cn/Article/details/gtqlojljjz.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gtvbkylcqm.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gteqgrjqxw.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtdzdjvzcv.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gthjusxlxy.html

[R46] 递归替换文件内容
来源：http://dali.jinqigfzy.top/Article/details/gtcitpsftv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlclperaz.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gtrjtbsnhl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gtccvmujou.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gthqwdtbji.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtyxlvzvkz.html

[R49] awk 带条件
来源：http://dali.zdqjudy.top/Article/details/gtyxxkfyhd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gtkdivpjkp.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gtihturzwx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yongpay.top/Article/details/gtctxmsqcl.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gtewistlgp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gtmognkggt.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gtdivzifwn.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gtqaozbuzs.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovmofyjb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhlecwfz.html

[R54] 比较两个文件
来源：http://dali.xinyue.icu/Article/details/gteqrjwldk.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gtftmbuyqx.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gtdcfxtmwx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gtbcncuhtc.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gtzwlwcsez.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gtcmrxeldq.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gtbazigtub.html

ssh user@host 'uptime'
来源：http://dali.shuidangran.top/Article/details/gtswfdkndx.html

[R58] 下载文件
来源：http://dali.hywenlv.cn/Article/details/gteohqsvbq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gtydlpaggq.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtfkwcdwxf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jyoumei.cn/Article/details/gtrxnsgnfi.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtzokaewsw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jyoumei.cn/Article/details/gtuqdnodao.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gtcjjjnyos.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gtwafzezqw.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gtbngqtnld.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gtyzjsswsc.html

[R63] 内存与进程
来源：http://dali.redwolf501.top/Article/details/gtuzgiuwzt.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gtgmmfkbjj.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gtybxrsfvn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gtpnebpumf.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gtvghmvxts.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gtckwoiaqu.html

[R66] 定时任务
来源：http://dali.zycfv.cn/Article/details/gtpfjalzfq.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gtiexjfyte.html

[R67] 生成随机十六进制串
来源：http://dali.smart0.xyz/Article/details/gtilrubgsk.html

openssl rand -hex 16
来源：http://dali.zhongyouzk.top/Article/details/gtktjvzlyf.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gtfxmpenef.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtfgoaorod.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gtfqhkxmif.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gtkyyojyfp.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrrhctzi.html

date +%s;  date -d @1700000000
来源：http://dali.guannengcc.top/Article/details/gtlsjbtntq.html

[R71] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtfromavex.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gthoincryc.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gtajywbsbz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtjwxzzgii.html

[R73] 分割大日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcumwdyuj.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gthjojqsgx.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gtziakpjrj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gteqphwyeh.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gthbbnvwds.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.9152youxi.cn/Article/details/gtihwfccby.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gtelyvweef.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gttbcjaolb.html

[R77] 读取用户输入
来源：http://dali.zdqjudy.top/Article/details/gtxpdopuei.html

read -rp "请输入: " ans
来源：http://dali.xuetiantiany.cn/Article/details/gticvorryc.html

[R78] 交互式菜单
来源：http://dali.xuetiantiany.cn/Article/details/gtjxhmtigo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtvugtogau.html

[R79] 解析命令行选项
来源：http://dali.wangdashe.top/Article/details/gturnawacu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gtupalobdf.html

[R80] 查看脚本执行耗时
来源：http://dali.dianchejie.cn/Article/details/gtdkoovovc.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtlhsggmnf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqnxgtutb.html

S. C / C++ 专题
来源：http://dali.zdqjudy.top/Article/details/gtqdjvahte.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gttymjjghp.html

[S01] C：Hello World
来源：http://dali.ydzc1.top/Article/details/gtwjjhbnoc.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gtbtzcwhhd.html


<!-- 参考信息 -->