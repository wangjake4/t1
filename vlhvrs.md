代发 wailian999

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gttdknpvav.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.birdmap.top/Article/details/gtasohrecw.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gtrbsjtagx.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gtogawxsff.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gtpvswwvix.html

) t WHERE rn = 1;
来源：http://dali.chenzaomai.com/Article/details/gtbknokodt.html

[Q35] 内连接
来源：http://dali.zhongyouzk.top/Article/details/gtpoxehleq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtyegounxt.html

[Q36] 左连接
来源：http://dali.yj202588.top/Article/details/gtjuvgwyly.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiihpdutw.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gtkkjkmjka.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtxbkdunjt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.kuanghao11.cn/Article/details/gtgpfsxhpt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.316326.xyz/Article/details/gtsyfhqkyi.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gtwfbqzeei.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yongpay.top/Article/details/gtfwittkhx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtanvpbbyy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.redwolf501.top/Article/details/gtrgnjuwbl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hammf.cn/Article/details/gtorbcgvwp.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gtapqomqch.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jyoumei.cn/Article/details/gtcqlpqoni.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gtzxjibggz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jianghu66.top/Article/details/gtfgusvrih.html

[Q42] 连接条件附加过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsutyqwl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gtujauthle.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gtctflcdnv.html

[Q43] 标量子查询
来源：http://dali.jinqigufen.top/Article/details/gtusucyoqs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xziqi.cn/Article/details/gtvbyidqnt.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gtaqsdwzxn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.birdmap.top/Article/details/gtacnbhupn.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gtjpvbktdv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtubbsvmuo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gtlcjufzwg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtznkfuoyv.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gtuqjavmzt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.meibo888.top/Article/details/gtspejitja.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtezndpiyu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gtrupjpqva.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gtbhcejzjx.html

[Q49] 更新单行
来源：http://dali.xziqi.cn/Article/details/gtytmgiroc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvuicwcz.html

[Q50] 批量更新
来源：http://dali.hysaishi.cn/Article/details/gtxomecncs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangdashe.top/Article/details/gttqqtnhdf.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gtjyyntnxf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zycfv.cn/Article/details/gtkbfnizex.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gthqufanvo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gtkdwzoiew.html

[Q53] 按条件删除
来源：http://dali.feifeiyinyue.top/Article/details/gttgslfycz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gtnuorzfcc.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gtqckorzgi.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtnrquawub.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gtkjkoapgm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gttyynnrdo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.quarkkingdee.top/Article/details/gtuqqeihck.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfqpdufu.html

[Q57] 行号
来源：http://dali.nwbrower.top/Article/details/gtxshtvwes.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvfjiowj.html

[Q58] 累计求和
来源：http://dali.sxryk.cn/Article/details/gtzwskynyj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtqqdgpxlj.html

[Q59] 分组内累计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrhzmskq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtimusjysm.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gtixnmxwtj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxinkj.top/Article/details/gtpvmubhzb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtprcnybnx.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gtxborjfvr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtgksuxluu.html

[Q62] 分组占比
来源：http://dali.xuanzx.com/Article/details/gtzqbeknsr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtrnxfvqfs.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gtqlmfxcex.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtanqordpa.html

[Q64] 提交事务
来源：http://dali.quarkkingdee.top/Article/details/gtvaxedjzg.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gtkppmximz.html

[Q65] 回滚事务
来源：http://dali.ybcxt.top/Article/details/gtekivuhgu.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gtaayclmdd.html

[Q66] 行锁查询
来源：http://dali.guowangkeji.top/Article/details/gtysgnhnes.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gtfjqzrgob.html

[Q67] 设置隔离级别
来源：http://dali.hnqzz.top/Article/details/gtjmkzrlok.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuetiantiany.cn/Article/details/gtjlmtsqsg.html

[Q68] 保存点
来源：http://dali.gzhubu.top/Article/details/gtkggqetrt.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gtiipzvqdw.html

ROLLBACK TO sp1;
来源：http://dali.zhengqikj.top/Article/details/gtkrkhzxue.html

[Q69] 查看执行计划
来源：http://dali.daxiang520.top/Article/details/gthquxjnfh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwkrmeib.html

[Q70] 更新统计信息
来源：http://dali.xziqi.cn/Article/details/gtmuqveqrh.html

ANALYZE TABLE users;
来源：http://dali.redwolf501.top/Article/details/gtkirdhley.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gtyncwnmip.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guowangkeji.top/Article/details/gtlrktwrcd.html

[Q72] 查看索引
来源：http://dali.ppjwa.cn/Article/details/gtranysmyl.html

SHOW INDEX FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtqlpnjboe.html

[Q73] 查看表状态
来源：http://dali.yuxming.cn/Article/details/gtzvawvupy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.birdmap.top/Article/details/gtpskdrfcw.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gtstalzmys.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gtenvqnevm.html

[Q75] 日期格式化
来源：http://dali.sweek.top/Article/details/gtaekcatha.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtufyamtvm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gtdsbtqjfq.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gtmsmnsuud.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuxming.cn/Article/details/gtdvdbjedo.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gthefpmszj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gtbtklsjsl.html

[Q78] 当前时间
来源：http://dali.zhixingplan.top/Article/details/gtegvjqeik.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gthgzruglo.html

[Q79] 字符串拼接
来源：http://dali.yongpay.top/Article/details/gtpetcpwji.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gtsiqbsbte.html

[Q80] 字符串截取
来源：http://dali.svipenyu.cn/Article/details/gtkjkibxqy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqehqaia.html

[Q81] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtcitmhwil.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtsguppmpz.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gtaydfnlsw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtbbpifmyr.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtxbupfbqs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtotcnhdsu.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gtjlobgaiy.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtjtmdbzaj.html

[Q85] 数值取整
来源：http://dali.316326.xyz/Article/details/gtbytdiahx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gtolccinzs.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gtjdqcvacv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jlsjyb.cn/Article/details/gtidchhsid.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gtqotgfcfl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejlwittu.html

[Q88] 行转列（条件聚合）
来源：http://dali.sweek.top/Article/details/gtvhwshkqg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmzqpfhy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.andypj.xyz/Article/details/gtcwgnestr.html

[Q89] 判断表是否存在
来源：http://dali.shzxlz.cn/Article/details/gtfgxbltfi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guowangkeji.top/Article/details/gtmvveufoy.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gtifaufqge.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gtakeuabst.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtsmwxkuvj.html

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gtvqogelua.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrzjllxnm.html

[R01] shebang 与严格模式
来源：http://dali.ehwqpu.com/Article/details/gtudopxxbr.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtudqgrxit.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gtcexkjiix.html

[R02] 变量赋值与使用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlhyhybb.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gtmlgwkvft.html

[R03] 只读变量
来源：http://dali.yanxiufei.cn/Article/details/gtraixgiwf.html

readonly PI=3.14
来源：http://dali.yangfankeji.com/Article/details/gtbwcafdzd.html

[R04] 位置参数
来源：http://dali.kuanghao11.cn/Article/details/gtjtiwofmq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gtdmijfofj.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gtobzhpzqu.html

name="${1:-default}"
来源：http://dali.jinqigfzy.top/Article/details/gtsjjyikni.html

[R06] 判断命令是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsvogokw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtpguqicqe.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gtspdfjkkf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shzxlz.cn/Article/details/gtsnotgjjz.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gtsprukuok.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gtchywaphe.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gtiyacvpuw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gtswwehawh.html

[R10] 正则匹配
来源：http://dali.haohaochexian.top/Article/details/gtcvbdhmva.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gtisvpdipa.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gtgcwzsofd.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gtozrrmcqe.html

start) echo "启动" ;;
来源：http://dali.ybcxt.top/Article/details/gtqfdjpeie.html

stop)  echo "停止" ;;
来源：http://dali.chenlongwang.top/Article/details/gtisaaiflm.html

*)     echo "未知命令" ;;
来源：http://dali.sxryk.cn/Article/details/gtwrudkozh.html

esac
来源：http://dali.chenjidiqi.icu/Article/details/gtqpkxosmc.html

[R12] for 遍历文件
来源：http://dali.yanxiufei.cn/Article/details/gtltdhzpqp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gttjlmatlv.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gtiilyqpci.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtnutpvajg.html

[R14] C 风格 for
来源：http://dali.yonumen.top/Article/details/gtrpaxcvoo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtfgrjevaq.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtzkfjebbd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gtpvojckil.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gtgwfgxcjf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtnmocyfyg.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gtwrnawuhf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gtnoysjqgj.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gtiryaqiuj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gtdvifxfud.html

[R19] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtepfpfsdv.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gtrbcygojg.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gteazdijwr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gtpxyasfeh.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtpdiulnrf.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gtruljhuys.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtjvdfbhof.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gtmdgtsezq.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtiqffyrjz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gtiouvheiv.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtumczryfg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shuidangran.top/Article/details/gtlmknvikd.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnxiangtu.top/Article/details/gthuifiows.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gtqxgahtex.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gtgpsavwos.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gtmklooqab.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gtckytxxig.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gttxmgerds.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gttglaxesf.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gtsfhftezl.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtadtaemkd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aibaodan.cn/Article/details/gtsxwtcaqo.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gtximxxeuo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guannengcc.top/Article/details/gtztbfqvld.html

[R31] 局部变量
来源：http://dali.jiagoushi.top/Article/details/gtixcbrkyd.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gtlqreebps.html

[R32] 参数个数校验
来源：http://dali.ivvv.top/Article/details/gttgymsbau.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtwsondqlw.html

[R33] 捕获错误并提示行号
来源：http://dali.tian-w.cn/Article/details/gtrorifdqn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gtlwjtlrcn.html

[R34] 退出时清理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxqomskk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gteaiscaxv.html

[R35] 后台执行并等待
来源：http://dali.jqgfzy.top/Article/details/gtkwyyeaho.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sweek.top/Article/details/gtqxyhcqdy.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprsxytwx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gtxnjjckdj.html

[R37] 把输出赋给变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaszufbff.html

files=$(ls -1)
来源：http://dali.gogol.net.cn/Article/details/gtoqbflejp.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gtvjovkebb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gtjoxhrbjh.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gtnvhpboth.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtqortsjxk.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gtotoprdnr.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gtmfvbcxhk.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gtehawndms.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gtiwcqnfit.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gtqffoypfj.html

wc -l < a.txt
来源：http://dali.316326.xyz/Article/details/gtrdlfjzsm.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtxkcbnoqa.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gtdgcklwmd.html

[R44] 按修改时间查找
来源：http://dali.andypj.xyz/Article/details/gtnyenvxlq.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gtbxqipcbs.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gtbwdbmqqi.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gtfsmuygpp.html

[R46] 递归替换文件内容
来源：http://dali.yuxming.cn/Article/details/gtxkrhszgv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gtfjgeijao.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gtzhsdjtfs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtvnpxkcvv.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gtaxmexkah.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtealjvarh.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gtrlulssvg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gtonsvrlrx.html

[R50] awk 求和
来源：http://dali.jlsjyb.cn/Article/details/gtjvfizlzt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtbdjutudo.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gtzhojprbf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cashguo.top/Article/details/gtpixggopi.html

[R52] 统计行数
来源：http://dali.shzxlz.cn/Article/details/gtcroxfhmf.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gtxqurryui.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoarvswog.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gtkabvyssz.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gtuqmwkzqp.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gtenabihhn.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gtrceteedz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gtetcolnma.html

[R56] 远程拷贝
来源：http://dali.zhixingplan.top/Article/details/gtqhsyhyil.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtnuagjjay.html

[R57] 远程执行命令
来源：http://dali.yanxiufei.cn/Article/details/gtohguifrl.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gtszfutaru.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gtailavqea.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.iojbl.cn/Article/details/gtnflelxjy.html

[R59] 发 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtrqzsnpiq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtrhtkiqzs.html

[R60] 只看 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtjosjlaem.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gtbgoxdgcn.html

[R61] 磁盘占用
来源：http://dali.fengsongda.top/Article/details/gtqefhtuhu.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gtjvdvihls.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gtolzkdkte.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gtqmccwhfc.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gtzkfdlsds.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gtvnqdsedj.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gtwwhxhkuj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.bjfxy.top/Article/details/gtugulmjsd.html

[R65] 查看端口占用
来源：http://dali.redwolf501.top/Article/details/gtenrskndt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xinyue.icu/Article/details/gtmauakxft.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gtwnmzrzja.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gtyloggiiy.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gtdeuapyqq.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gtmzfhyyma.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gtzqtnfvrf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gtpnumqjaa.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gtxykyznzq.html

head -c 16 /dev/urandom | base64
来源：http://dali.havefunace.top/Article/details/gtmvezwoph.html

[R70] 时间戳与互转
来源：http://dali.sufxvd.cn/Article/details/gtjmozssdu.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyzgoinb.html

[R71] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmgfjsmt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuxming.cn/Article/details/gtttvjekmv.html

[R72] 等待端口就绪
来源：http://dali.hnxiangtu.top/Article/details/gtotoegout.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtxnjpemyr.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtegwjdqfw.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gtqfdqnzob.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gtebzfppkg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gogol.net.cn/Article/details/gtlxhkyybu.html

[R75] 导出环境变量
来源：http://dali.andypj.xyz/Article/details/gtflbmamgo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gtjjilkgab.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gtbhrdrxqw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gtlniltvif.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gtbtpzfvpi.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gtkaclpqmj.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gtxunzzfli.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gtarqyqoig.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gtzevcqfcr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gtulzfpvar.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gtastaibnd.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gtelhosbnx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtokrzggnv.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gttihbfyuu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtgvgmxrww.html

[S01] C：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumzjrbta.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gttbqgwivg.html


<!-- 参考信息 -->