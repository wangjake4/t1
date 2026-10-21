代发 wailian999

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gtnuesdksr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gtsfoqqcdl.html

[Q37] 右连接
来源：http://dali.sufxvd.cn/Article/details/gtwklnioxq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gtxmjorsib.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zdqjudy.top/Article/details/gtnorntzih.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gtlwszqkur.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gtrupbfurv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktaimtuu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gtjdhcysrm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinghuilouyu.cn/Article/details/gtspvfocma.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gtxhivrjbw.html

[Q41] 多表连接
来源：http://dali.jqgufenzy.top/Article/details/gtjpuvgzfr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gtpykxeekw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.birdmap.top/Article/details/gtkkzpqctd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gtibhhsikz.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gtzicrfdgn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gtjylpkeru.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gtbdxufxwa.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gtvhbhigyh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjjbvdhj.html

[Q44] IN 子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtyltozedr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guannengcc.top/Article/details/gtqiswplmr.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gteqrnaqjh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtflsxfskh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtcepsiwgp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtppyiwycz.html

[Q47] 与平均值比较
来源：http://dali.fengsongda.top/Article/details/gtwedwisxs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gtmmjdxmgf.html

[Q48] CTE 公用表表达式
来源：http://dali.aizwys.cn/Article/details/gtixghawlt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hysaishi.cn/Article/details/gtkotdtzir.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gtwbefqjqf.html

[Q49] 更新单行
来源：http://dali.tanke756.top/Article/details/gtvxitzwqh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gthgsrunlc.html

[Q50] 批量更新
来源：http://dali.quarkkingdee.top/Article/details/gthseybqum.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gtqvrzqlin.html

[Q51] 用子查询更新
来源：http://dali.hongshengwenyu.top/Article/details/gtwqptleas.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gtbwnzaaoj.html

[Q52] 删除指定行
来源：http://dali.yj20258.top/Article/details/gtpwudfjji.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtxwnxzpkk.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gtfpehughn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gtragxeecm.html

[Q54] 清空表
来源：http://dali.pengpengdd.cyou/Article/details/gtfbmiwmcy.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtxdpexhry.html

[Q55] 排名（并列占位）
来源：http://dali.bjfxy.top/Article/details/gtuqlpvqzd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtvmdjhwrn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pycfn.com/Article/details/gtoqajthgb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gtgwiwehbz.html

[Q57] 行号
来源：http://dali.yongpay.top/Article/details/gtyxquyhlw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gtzgeyndho.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gtqnpkkrpr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gtkgudjykd.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtcnuwrixa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtrrftemiz.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gtdjkwevnb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shangyingyoupin.top/Article/details/gtxdtuktra.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cheryme.top/Article/details/gttxykotaw.html

[Q61] 移动平均
来源：http://dali.haohaochexian.top/Article/details/gtdjyocfrz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gthfckqdjy.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gtwewismxh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfahlsoe.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gtoykkywku.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhoulong.xyz/Article/details/gtdkkdwcet.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gtzdwyksiu.html

COMMIT;
来源：http://dali.guowangkeji.top/Article/details/gtsfugdhwb.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gtlaswhtvy.html

ROLLBACK;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxlbxtpx.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikldkytb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbacrnfwo.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gtadpxazdg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtrcqzhpmf.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gthzmebuxo.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgzzwykz.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gtoqabwtww.html

[Q69] 查看执行计划
来源：http://dali.pycfn.com/Article/details/gtkkmshgbi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gtplcgezbi.html

[Q70] 更新统计信息
来源：http://dali.sweek.top/Article/details/gtdckmqiae.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gtsvgxcvat.html

[Q71] 查看建表语句
来源：http://dali.andypj.xyz/Article/details/gtqyjrxlhy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cdnleiting.top/Article/details/gtcrfjnlgf.html

[Q72] 查看索引
来源：http://dali.hongshengwenyu.top/Article/details/gtpmdhjndg.html

SHOW INDEX FROM users;
来源：http://dali.cashguo.top/Article/details/gtadzqndhh.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gtmkjjzkrs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtdadmmjpi.html

[Q74] 强制使用索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsxwabrg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gtbgtiqpje.html

[Q75] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtrprwuxzl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gtahgpwfla.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgfzy.top/Article/details/gtkezqqfvj.html

[Q76] 按天统计
来源：http://dali.svipenyu.cn/Article/details/gthfrlwucf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.iojbl.cn/Article/details/gtwldvjrqx.html

[Q77] 时间加减
来源：http://dali.gaohongyu789.top/Article/details/gtvndxptil.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubbohkmv.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gtgiytovvw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gtcxwohypw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtkoqzbdjf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gtgbbclvyp.html

[Q80] 字符串截取
来源：http://dali.jiagoushi.top/Article/details/gtmcwqowbk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtdioydoth.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtsktguzbb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtjkpjello.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgfzy.top/Article/details/gtwjcjowve.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtepfynrmq.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtiduapbzb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtcaafcibo.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gtdcblpbkm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtcktffkhs.html

[Q85] 数值取整
来源：http://dali.sufxvd.cn/Article/details/gtqmhodlab.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.316326.xyz/Article/details/gtudmjmjjv.html

[Q86] 读取 JSON 字段
来源：http://dali.xylfe.cn/Article/details/gtedcoiorp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gtwtecdiut.html

[Q87] JSON 字段做条件
来源：http://dali.hfpthk.cn/Article/details/gtmlskqyil.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gtsyvzuzfu.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gtshqmtjne.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gtmdevnkgf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuanzx.com/Article/details/gtdvknnguf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtnjewnkjc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtisttjsuw.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gtejmarqij.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gtojpdcmkm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtcbbfwgny.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebbwunpn.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtweykeytk.html

[R01] shebang 与严格模式
来源：http://dali.hysaishi.cn/Article/details/gthqbgqoan.html

#!/usr/bin/env bash
来源：http://dali.316326.xyz/Article/details/gtzzgpihmk.html

set -euo pipefail
来源：http://dali.fengsongda.top/Article/details/gtmlimqlla.html

[R02] 变量赋值与使用
来源：http://dali.zhixingplan.top/Article/details/gtlomvhgva.html

name="Tom"; echo "$name"
来源：http://dali.hnqzz.top/Article/details/gtmxvhaqkp.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gtcdlgbvrh.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gtvsppjsvy.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gthokumqsb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gtnehfmzrq.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gtpunlcvsj.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtstjdvinv.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gtfsxtogfc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtcjfbalih.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gtpinmtarn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.havefunace.top/Article/details/gtsoaebkxu.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gthtbqeibk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guowangkeji.top/Article/details/gtfkyvzwjj.html

[R09] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtlsyppxvu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gtzarbyclo.html

[R10] 正则匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtmnlrqepr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.c1oappe.top/Article/details/gtwqddyoce.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjpkodws.html

case "$1" in
来源：http://dali.daxiang520.top/Article/details/gtwhhlkvdd.html

start) echo "启动" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtpfyxhtyp.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gthwslajlv.html

*)     echo "未知命令" ;;
来源：http://dali.sysykeji.top/Article/details/gtggfbberm.html

esac
来源：http://dali.tanke756.top/Article/details/gtbvvhvxdd.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhsybqpd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yanxiufei.cn/Article/details/gtuyamiagz.html

[R13] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtbudozmhn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtafyvbjee.html

[R14] C 风格 for
来源：http://dali.hnqzz.top/Article/details/gtoocyviov.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtqjkianpp.html

[R15] while 逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtiedokoom.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gttugwovvw.html

[R16] until 等待条件
来源：http://dali.xuanzx.com/Article/details/gtfemiycfc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtaynkdsdt.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gthesgruni.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtxpdjcbcd.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gticbaljfw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenzaomai.com/Article/details/gtdqybdamk.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtecicgknj.html

echo "${#arr[@]}"
来源：http://dali.pycfn.com/Article/details/gtvyagzlon.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtxwnyhlcu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtzqdtsluu.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtwmbhwqoc.html

echo "${#s}"
来源：http://dali.ivvv.top/Article/details/gtvzijpjpe.html

[R22] 截取子串
来源：http://dali.hnqzz.top/Article/details/gtyrlnsgds.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtnmirtavb.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtzlgtmhmi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gtwpcatbcd.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtjcvnzfzi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gtryxecixl.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gtdcglyuqx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gtxjbtppla.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gtdpjcyitb.html

now=$(date +%F); echo "$now"
来源：http://dali.xylfe.cn/Article/details/gtyaarxhxa.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtlczvvwak.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtpouizlno.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gtaddkjyfc.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangdashe.top/Article/details/gtelcxywli.html

[R29] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtvyolxaei.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuanzhike.top/Article/details/gtmulnfpsw.html

[R30] 函数返回状态码
来源：http://dali.yuxming.cn/Article/details/gtkjcduvpx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ppjwa.cn/Article/details/gtercnjkkj.html

[R31] 局部变量
来源：http://dali.mhx1999.top/Article/details/gtargptrmk.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gtxzkjbyaq.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gtjxhzlmqd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaaayhcj.html

[R33] 捕获错误并提示行号
来源：http://dali.tianlin.xyz/Article/details/gtjbvkhpql.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ydzc1.top/Article/details/gtdluevmjv.html

[R34] 退出时清理
来源：http://dali.zhengqikj.top/Article/details/gttcplajua.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtfnlsvtua.html

[R35] 后台执行并等待
来源：http://dali.shzxlz.cn/Article/details/gtytiymptf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gtwtitdnzj.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gtcfyvqbsp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gtlujwtaxn.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblnoljju.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gtvrgsuqav.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gtantqwxgu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqjbiblw.html

[R39] 重定向标准输出与错误
来源：http://dali.gotoacloud.top/Article/details/gtlzibazhj.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gtxsgzqshh.html

[R40] 追加写日志
来源：http://dali.zhoulong.xyz/Article/details/gtonemgout.html

echo "log" >> out.log
来源：http://dali.gzhubu.top/Article/details/gthvvjfdqu.html

[R41] 丢弃输出
来源：http://dali.hnxiangtu.top/Article/details/gtedhrbmps.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtilruwidh.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gtfdritylv.html

wc -l < a.txt
来源：http://dali.birdmap.top/Article/details/gtkxzzlvyy.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gtzupsywlg.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gtsoovjjky.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gtejbyqwlo.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gtoheqwrtd.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gtxfemabut.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gtnpbmgubz.html

[R46] 递归替换文件内容
来源：http://dali.zhiwuduotai.top/Article/details/gtepmuqxbp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yanxiufei.cn/Article/details/gtbwwdhtyj.html

[R47] sed 单行替换
来源：http://dali.yueranfly.top/Article/details/gtiatmqpzx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtdowykamn.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtxohxuzjt.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtwqksoobh.html

[R49] awk 带条件
来源：http://dali.wangshuangyany.cn/Article/details/gtyqkcioum.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.snrcjt.cn/Article/details/gtwipeuach.html

[R50] awk 求和
来源：http://dali.jyoumei.cn/Article/details/gtmoigygjh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gttczzagsh.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtixesykkr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shzxlz.cn/Article/details/gtcibjlkem.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gtmxtfjquz.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gtggsnkvvz.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gtieuuatrb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.birdmap.top/Article/details/gtbtfpuilp.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gtmrnunckj.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gtnudzjywz.html

[R55] 压缩与解压
来源：http://dali.ivvv.top/Article/details/gtnnbrvzzo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhiwuduotai.top/Article/details/gtzgkzhlin.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxjeszcl.html

scp file user@host:/path/
来源：http://dali.gaohongyu789.top/Article/details/gtxxekfaxn.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gtqjeghrzk.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gtficrtdgy.html

[R58] 下载文件
来源：http://dali.snrcjt.cn/Article/details/gtegkajzto.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gtqwzpawal.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtyyqtsbbv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenlongwang.top/Article/details/gtpsrleteb.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtpmyjpzrg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenlongwang.top/Article/details/gtpdamqzsg.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gtwobpyfoc.html

df -h;  du -sh *
来源：http://dali.tianlin.xyz/Article/details/gtmcrydwer.html

[R62] 找最占空间的文件
来源：http://dali.andypj.xyz/Article/details/gtwbkszdkl.html

du -ah . | sort -rh | head -10
来源：http://dali.9152youxi.cn/Article/details/gtxyrnjutz.html

[R63] 内存与进程
来源：http://dali.hywenlv.cn/Article/details/gtcbnccumy.html

free -h;  ps aux | grep nginx
来源：http://dali.sysykeji.top/Article/details/gtfzebnkce.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gtnrbrmppk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gtohincuhs.html

[R65] 查看端口占用
来源：http://dali.guowangkeji.top/Article/details/gtwzhpfliy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gtgbbandsz.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gtuxvcbxnh.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gtefbqdbue.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gtlpbwbuek.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gtkbjnbsmd.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymfzhlfv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cdnleiting.top/Article/details/gticpgzlcr.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gtwyrtryzo.html

head -c 16 /dev/urandom | base64
来源：http://dali.yvedp.cn/Article/details/gtqlxsefez.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gtjbyxktgs.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gtarmaugei.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtmxbcpuws.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnssvvozq.html

[R72] 等待端口就绪
来源：http://dali.wangshuangyany.cn/Article/details/gtaugyejvc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtymzfessf.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gtbxzumhhl.html

split -l 1000 big.log part_
来源：http://dali.yanxiufei.cn/Article/details/gtuykzugfx.html

[R74] 批量重命名
来源：http://dali.ybcxt.top/Article/details/gtkmdglkul.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ehwqpu.com/Article/details/gtpjsjzpti.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtemlhivri.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gttyobeuok.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gthilkybkp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnivueft.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gtxeknjgkt.html

read -rp "请输入: " ans
来源：http://dali.tanke756.top/Article/details/gtzblcnnli.html

[R78] 交互式菜单
来源：http://dali.c1oappe.top/Article/details/gtzfopouzc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhixingplan.top/Article/details/gtazvvqibv.html

[R79] 解析命令行选项
来源：http://dali.tian-w.cn/Article/details/gtyisujybh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.meibo888.top/Article/details/gtriqqxwni.html

[R80] 查看脚本执行耗时
来源：http://dali.zhiwuduotai.top/Article/details/gtyyochsyz.html

time ./run.sh
来源：http://dali.ehwqpu.com/Article/details/gtekhvvmwn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmjjhohw.html

S. C / C++ 专题
来源：http://dali.vqdsnc.cn/Article/details/gtvgrkrghf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gteuiliebu.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gtaufuouap.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gtcsfaihnf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangshuangyany.cn/Article/details/gtosowygvb.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gtqtyiavgh.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gtkdctmkej.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gtbbdznbfr.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjuxbofp.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gtzksosewk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtsiakpvus.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gttjbbsczh.html


<!-- 参考信息 -->