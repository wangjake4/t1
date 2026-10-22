代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuetiantiany.cn/Article/details/gtezhdysse.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtwavegfgx.html

[Q35] 内连接
来源：http://dali.yonumen.top/Article/details/gtkhdvxoex.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtrujytkxi.html

[Q36] 左连接
来源：http://dali.haohaochexian.top/Article/details/gthmvwpbya.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gtdumvfnzt.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtxhuzqlgu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtjhbthbiv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gtemoyckno.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhixingplan.top/Article/details/gtegbemebh.html

[Q39] 自连接（查上下级）
来源：http://dali.316326.xyz/Article/details/gthlivuxfm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxuanxn.top/Article/details/gtwghrissm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gtoufjxruf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258888.top/Article/details/gtlywwspkb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgfzy.top/Article/details/gtxtrgkfht.html

[Q41] 多表连接
来源：http://dali.snrcjt.cn/Article/details/gtfeuxcagq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gthsffayrg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gtqjcwdlja.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gtbrnhpwsb.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gtoqetdyof.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cucudq.cn/Article/details/gtlixdkynb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtutoicqzf.html

[Q43] 标量子查询
来源：http://dali.aibaodan.cn/Article/details/gtfdhzsnwq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shzxlz.cn/Article/details/gtfmeocscy.html

[Q44] IN 子查询
来源：http://dali.xziqi.cn/Article/details/gtcetsbipc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gtugmmukaf.html

[Q45] EXISTS 判断存在
来源：http://dali.chenzaomai.com/Article/details/gteswijvcc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtivwokgxn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guannengcc.top/Article/details/gtsowzhvpf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gttxvhfhlu.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gtvnpqhbdy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dianchejie.cn/Article/details/gtboimvbop.html

[Q48] CTE 公用表表达式
来源：http://dali.yvedp.cn/Article/details/gtpznuqewx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gtglqkenjf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.snrcjt.cn/Article/details/gtjyqgqlxw.html

[Q49] 更新单行
来源：http://dali.cdnleiting.top/Article/details/gtdkndusho.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtyelafvxk.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gtabtyudek.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hammf.cn/Article/details/gtmjfokbcv.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gtyydxojwg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guowangkeji.top/Article/details/gtmbaootne.html

[Q52] 删除指定行
来源：http://dali.cdnleiting.top/Article/details/gtwglbzyly.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtxksakunl.html

[Q53] 按条件删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyfpcpeu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtkhjxlqwk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gtduerjqjb.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gtpxysqdtb.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gtjvlfifgo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gtgoyvoarw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnfenbqz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtjztspjpt.html

[Q57] 行号
来源：http://dali.nanxinkj.top/Article/details/gtqgqfyksh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtzchbklqp.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gtgkdshrje.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtelzlijud.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gtnlisexwi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvzrhchw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gtjunreagd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guowangkeji.top/Article/details/gtrbvpcjke.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtppahdyla.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtaxombuar.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtqhvcrfgo.html

[Q62] 分组占比
来源：http://dali.feifeiyinyue.top/Article/details/gtpktexaxz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtjptuuyve.html

[Q63] 开启事务
来源：http://dali.zhoulong.xyz/Article/details/gtqosuhljk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gtadgweflg.html

[Q64] 提交事务
来源：http://dali.dashuyun.cn/Article/details/gtvbynujzi.html

COMMIT;
来源：http://dali.nanxuanxn.top/Article/details/gtdbwblyrg.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gtftvlymhr.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gtiyelyvzk.html

[Q66] 行锁查询
来源：http://dali.xuetiantiany.cn/Article/details/gtnutgrnwn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjskyjywm.html

[Q67] 设置隔离级别
来源：http://dali.jlsjyb.cn/Article/details/gtsjvfekph.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258888.top/Article/details/gtgttdhsja.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gtudzngfot.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gtiuvicjga.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gtwcwoisth.html

[Q69] 查看执行计划
来源：http://dali.yvedp.cn/Article/details/gtqwtbguem.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gtbnsfwdos.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gtxlufkjoa.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gtpstdmeee.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gtvuvkxysh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gtaexspxxy.html

[Q72] 查看索引
来源：http://dali.cucudq.cn/Article/details/gtaqeiiefr.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtwehttiol.html

[Q73] 查看表状态
来源：http://dali.gogol.net.cn/Article/details/gtpqjzuudz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtqyhuuflv.html

[Q74] 强制使用索引
来源：http://dali.pycfn.com/Article/details/gtxeavqlgb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gtnyhopgcg.html

[Q75] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtzjnsnsaq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtxoxhmkhv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gtznadjrkc.html

[Q76] 按天统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnzccrcx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenjidiqi.icu/Article/details/gtwlejvysk.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gtlookosuf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gtdgsmtlxo.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gtskqevokk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aizwys.cn/Article/details/gtyxenhpgz.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gtkhpivgox.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gtncduzpoa.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gtynvuusbz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtfonwarwc.html

[Q81] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafmrbwhs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtrlrydlbk.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gtaexnxtkj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtrkiywnqo.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtmtefpmbl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtljpfdtdg.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gtwxzjvntu.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtdjorbgky.html

[Q85] 数值取整
来源：http://dali.xuetiantiany.cn/Article/details/gtjzptuzqy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyfuzhma.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gtmgvtojkw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dianchejie.cn/Article/details/gtywktdlxl.html

[Q87] JSON 字段做条件
来源：http://dali.gzhubu.top/Article/details/gtkhpqkbxg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gttkrcpnyb.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gtvradqllr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gtrqwbrusj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gttevewqps.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gtglyoslqb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shuidangran.top/Article/details/gtpysfsavb.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gttjotrskd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gtjodrlxsh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gteqjnwavy.html

R. Bash 专题
来源：http://dali.zycfv.cn/Article/details/gthmwkbhay.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtirhmsahb.html

[R01] shebang 与严格模式
来源：http://dali.xylfe.cn/Article/details/gtoisylyym.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gttqhemgsm.html

set -euo pipefail
来源：http://dali.yj20258888.top/Article/details/gtsiafppxp.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gtjsfvqegq.html

name="Tom"; echo "$name"
来源：http://dali.jyoumei.cn/Article/details/gtcfnhkckg.html

[R03] 只读变量
来源：http://dali.xinyue.icu/Article/details/gtfkuxzgpm.html

readonly PI=3.14
来源：http://dali.dianchejie.cn/Article/details/gtodmzklqy.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gttkqukdvf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gtntvtmybn.html

[R05] 参数默认值
来源：http://dali.jiagoushi.top/Article/details/gtphdptzxr.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gtubfkmtst.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtppepbxlu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtqqfzicww.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzrxmuos.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gtngvsihjc.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gtfetqplhb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtmklvpejq.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtqgoljdll.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtsinecvtd.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gtwkbirdfx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gtkfcozmxz.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtooipwssv.html

case "$1" in
来源：http://dali.dianchejie.cn/Article/details/gtarxzydko.html

start) echo "启动" ;;
来源：http://dali.yangfankeji.com/Article/details/gthubqtbwx.html

stop)  echo "停止" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtrvycbdro.html

*)     echo "未知命令" ;;
来源：http://dali.hysaishi.cn/Article/details/gtjrsxhqed.html

esac
来源：http://dali.yangfankeji.com/Article/details/gtigugtrcg.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gtpixymiul.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gtcfifjnxh.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gtatugaygt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gteavatvfx.html

[R14] C 风格 for
来源：http://dali.zhixingplan.top/Article/details/gtbxkzrixd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctzaghpm.html

[R15] while 逐行读文件
来源：http://dali.316326.xyz/Article/details/gtbnezbrmm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cdnleiting.top/Article/details/gtyvoizmdv.html

[R16] until 等待条件
来源：http://dali.nanxuanxn.top/Article/details/gtzxolmsqz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gttlxdvitl.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gtzrqejjiz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnqzz.top/Article/details/gtogayodaq.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gtfogfpfgz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gtqthzhutl.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtrtakxrov.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gttimdxsjr.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gtompzjkav.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gtiatnpevz.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gthixrnvru.html

echo "${#s}"
来源：http://dali.ppjwa.cn/Article/details/gtqjvmagik.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtuuanizsm.html

echo "${s:0:5}"
来源：http://dali.daria6918.cn/Article/details/gtvuwtjnit.html

[R23] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gttcpexhif.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.svipenyu.cn/Article/details/gtgtntkrei.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtormbnzfu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ydzc1.top/Article/details/gtzrbpegvg.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gtxjyvvzvj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnxiangtu.top/Article/details/gtkeiuvork.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gtuoczkehc.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gtbawrugdx.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gtcrdsaevy.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gtdcvsqabr.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gtjopsgbju.html

echo "scale=2; 10/3" | bc
来源：http://dali.yueranfly.top/Article/details/gtvogecihd.html

[R29] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtxilkding.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gtvucbvetq.html

[R30] 函数返回状态码
来源：http://dali.guannengcc.top/Article/details/gtfpfkpayh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gtcgepfpsc.html

[R31] 局部变量
来源：http://dali.yonumen.top/Article/details/gtbqsusgfg.html

f() { local x=1; echo "$x"; }
来源：http://dali.sxryk.cn/Article/details/gttiqtamwq.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gttgwbxdvp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtzyknuswz.html

[R33] 捕获错误并提示行号
来源：http://dali.hnqzz.top/Article/details/gtvlzeacgg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sweek.top/Article/details/gtrnedihzb.html

[R34] 退出时清理
来源：http://dali.jiagoushi.top/Article/details/gtsedebvyq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtbfaejuxd.html

[R35] 后台执行并等待
来源：http://dali.hywenlv.cn/Article/details/gtgvrzpkfl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gtyqvqcacv.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gtziukqanl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtpdcsqibm.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gtmwijxxmq.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gtgbkrsnnw.html

[R38] 管道串联
来源：http://dali.shzxlz.cn/Article/details/gtpqqgpyzs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gtzkrzapzt.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gthyjwbwur.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtowagbsyz.html

[R40] 追加写日志
来源：http://dali.316326.xyz/Article/details/gtbzncedgj.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gttpyfojfv.html

[R41] 丢弃输出
来源：http://dali.jianghu66.top/Article/details/gtiqzltbtg.html

cmd >/dev/null 2>&1
来源：http://dali.tian-w.cn/Article/details/gtlqbtugdu.html

[R42] 输入重定向
来源：http://dali.jqgfzy.top/Article/details/gtynoulvoo.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gtllqlbcrw.html

[R43] 按名字查找文件
来源：http://dali.fengsongda.top/Article/details/gtknwjljzy.html

find . -name "*.log" -type f
来源：http://dali.gotoacloud.top/Article/details/gtbmzdadyz.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gtyzcvlahe.html

find . -mtime -7 -type f
来源：http://dali.guannengcc.top/Article/details/gtziibpoeu.html

[R45] 批量删除
来源：http://dali.jinqigfzy.top/Article/details/gtkzeeyfwj.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gtzhhbzebz.html

[R46] 递归替换文件内容
来源：http://dali.nwbrower.top/Article/details/gtovxaxbeg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gtzvtghind.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gtbelzpcgj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xylfe.cn/Article/details/gtyxkouemj.html

[R48] awk 取指定列
来源：http://dali.dashuyun.cn/Article/details/gtazbtqlqw.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtnuxzodwg.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gtfgndaoua.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gtvpcsyhwp.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gtznyrqqru.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtqeuyhdja.html

[R51] 排序去重取前几
来源：http://dali.birdmap.top/Article/details/gtguwcwdnc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gtfnpcymhi.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gterwosazj.html

wc -l a.txt
来源：http://dali.jianghu66.top/Article/details/gtgqoglqsb.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gtfugvbiwe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.mhx1999.top/Article/details/gtajlvaeog.html

[R54] 比较两个文件
来源：http://dali.cdnleiting.top/Article/details/gtwzukreuc.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshaeothh.html

[R55] 压缩与解压
来源：http://dali.yanxiufei.cn/Article/details/gtfxphggje.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhiwuduotai.top/Article/details/gtassaszel.html

[R56] 远程拷贝
来源：http://dali.guowangkeji.top/Article/details/gtqcrnxmpn.html

scp file user@host:/path/
来源：http://dali.shangyingyoupin.top/Article/details/gtyjkfzvuy.html

[R57] 远程执行命令
来源：http://dali.yanxiufei.cn/Article/details/gtyezkyskh.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gtsfxjdmxn.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gtrveamhsr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gtqaxxhhzg.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtfvhhjopc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrngsdbu.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtfzkthofl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yongpay.top/Article/details/gtsamklwfj.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gtminqxxwa.html

df -h;  du -sh *
来源：http://dali.yj202588.top/Article/details/gtlogyrypr.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gtulttuffd.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gtoiuvajiw.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gtzyfsquae.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gtieknqfli.html

[R64] 结束进程
来源：http://dali.daria6918.cn/Article/details/gtxjtnrifz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gtbkjtdaap.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gtyewzeiwr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gtbisrrkev.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gtqollwiir.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gtsvkeyobd.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gtjjmljtil.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gttywmhilc.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gtdvjocyve.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtubkndjot.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gthljmrsfn.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnxiangtu.top/Article/details/gtmqrdjosn.html

[R70] 时间戳与互转
来源：http://dali.kuanghao11.cn/Article/details/gtdyleyjvp.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfgxsrzn.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtrqshdnny.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwuyycjk.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gtoicqwxla.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtjpambwpq.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiysqcmqy.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gtutrmaupt.html

[R74] 批量重命名
来源：http://dali.hammf.cn/Article/details/gtihiwmmkp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gtknmlbacw.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gtnwstqnxf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gtxlffgfqz.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfffvsuo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnlizavh.html

[R77] 读取用户输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdagupdnq.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gtexgnhfyf.html

[R78] 交互式菜单
来源：http://dali.hywenlv.cn/Article/details/gtlftchxim.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tianlin.xyz/Article/details/gtrinbtsos.html

[R79] 解析命令行选项
来源：http://dali.hammf.cn/Article/details/gtnkdrgfue.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gtihejusvd.html

[R80] 查看脚本执行耗时
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsetbbux.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gtgumbhmyf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtppeixpxl.html

S. C / C++ 专题
来源：http://dali.sxryk.cn/Article/details/gtbyfgttuc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtpbltfdsd.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtcnbrjwle.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gtcsccynhf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gtverejnbm.html

[S02] C：变量与格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gtbynfegvg.html

int a = 10; printf("%d\n", a);
来源：http://dali.dashuyun.cn/Article/details/gtpmsmnlul.html

[S03] C：读入整数
来源：http://dali.iojbl.cn/Article/details/gtzhbqkefj.html


<!-- 参考信息 -->