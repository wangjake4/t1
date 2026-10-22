代发 wailian999

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gtlkavgynm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gtxbgoatir.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gtzzwlpxxe.html

SELECT * FROM (
来源：http://dali.jyoumei.cn/Article/details/gtmqeocvgj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gtozvbvgmy.html

) t WHERE rn = 1;
来源：http://dali.shuidangran.top/Article/details/gtikngsrxf.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gtyylkccqt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gtkirzdddr.html

[Q36] 左连接
来源：http://dali.zhengqikj.top/Article/details/gtjljlrrul.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gtwgcgwslv.html

[Q37] 右连接
来源：http://dali.quarkkingdee.top/Article/details/gtjbcimrng.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gtiwueizhp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gtsjweypuu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtfdxlflgb.html

[Q39] 自连接（查上下级）
来源：http://dali.ivvv.top/Article/details/gtpjcsuwzx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gtgvdwbxrt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gtefmkrced.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhengqikj.top/Article/details/gttpzyteul.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ehwqpu.com/Article/details/gtvfkrspja.html

[Q41] 多表连接
来源：http://dali.quarkkingdee.top/Article/details/gtuwubvilz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigufen.top/Article/details/gthedigtcu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gttkmcnjst.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dashuyun.cn/Article/details/gtrbkjbrtp.html

[Q42] 连接条件附加过滤
来源：http://dali.yueranfly.top/Article/details/gtllqqhuff.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ydzc1.top/Article/details/gtfdpiivht.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ehwqpu.com/Article/details/gtzvcnoegn.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gtkfsbtfih.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtvimoohqw.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gthbbjncyc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gtymventdz.html

[Q45] EXISTS 判断存在
来源：http://dali.nwbrower.top/Article/details/gttrnscgcq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gtkuohpaew.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tian-w.cn/Article/details/gtddonziph.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtfiuopfea.html

[Q47] 与平均值比较
来源：http://dali.316326.xyz/Article/details/gtcmgmpiyc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gtmaypgoap.html

[Q48] CTE 公用表表达式
来源：http://dali.tianlin.xyz/Article/details/gtatwxgrdh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenzaomai.com/Article/details/gtlnvydysp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xziqi.cn/Article/details/gtyxfcjknk.html

[Q49] 更新单行
来源：http://dali.bjfxy.top/Article/details/gtuttmtmon.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gtzwuwrrco.html

[Q50] 批量更新
来源：http://dali.xinyue.icu/Article/details/gtocsnsdgm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gtgwzbghmi.html

[Q51] 用子查询更新
来源：http://dali.cucudq.cn/Article/details/gtpjzmaxma.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtoctajedd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gtnvziqpya.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gthxqbbwix.html

[Q53] 按条件删除
来源：http://dali.guowangkeji.top/Article/details/gtzsvuuvoe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyflusgs.html

[Q54] 清空表
来源：http://dali.hysaishi.cn/Article/details/gtxxamnacf.html

TRUNCATE TABLE logs;
来源：http://dali.zhongyouzk.top/Article/details/gtemjkuujm.html

[Q55] 排名（并列占位）
来源：http://dali.jianghu66.top/Article/details/gtgjkzxvnt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtphqptuzr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sxryk.cn/Article/details/gtvzuctkkn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbumgeks.html

[Q57] 行号
来源：http://dali.yj20258888.top/Article/details/gtwdofcyci.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtgeqbwamj.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gtdkvnrpyd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkczosyjt.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gtmdhaosja.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtxvsfaeqk.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gtlzlffwlz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gtnwsrqqjm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtwcyjxruw.html

[Q61] 移动平均
来源：http://dali.jqgufenzy.top/Article/details/gtqqluzhdm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtvvldsmyw.html

[Q62] 分组占比
来源：http://dali.fengsongda.top/Article/details/gtijgjvbkw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtoasvprdv.html

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gtfjeodaue.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zycfv.cn/Article/details/gtrumtlakb.html

[Q64] 提交事务
来源：http://dali.daria6918.cn/Article/details/gtiictyukl.html

COMMIT;
来源：http://dali.ehwqpu.com/Article/details/gtedhtbtjf.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gtdtcjvxmy.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuzraioe.html

[Q66] 行锁查询
来源：http://dali.daxiang520.top/Article/details/gtpiozmxkx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgpcwbla.html

[Q67] 设置隔离级别
来源：http://dali.tian-w.cn/Article/details/gtzltbxwty.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gtroniixcw.html

[Q68] 保存点
来源：http://dali.guowangkeji.top/Article/details/gtgogvkjdm.html

SAVEPOINT sp1;
来源：http://dali.guowangkeji.top/Article/details/gtnfegloud.html

ROLLBACK TO sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtxtfkwmlp.html

[Q69] 查看执行计划
来源：http://dali.shzxlz.cn/Article/details/gtwlgbcmqh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cucudq.cn/Article/details/gtdbjzoqos.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gtkiuyvtgf.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gtydftwcju.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gtmfaqaqom.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zdqjudy.top/Article/details/gtydhbwncp.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gtijacxauh.html

SHOW INDEX FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtssmefjbp.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gtccxxbonl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.0kj1m.cn/Article/details/gtopcbhqwh.html

[Q74] 强制使用索引
来源：http://dali.yangfankeji.com/Article/details/gtsguagxhz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gtbonmswom.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gteibaylra.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gtkbgohsaw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gtzawxqdle.html

[Q76] 按天统计
来源：http://dali.cashguo.top/Article/details/gtuyircizi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gtgklpeebk.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gtndabkjvr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gtgedfqauj.html

[Q78] 当前时间
来源：http://dali.c1oappe.top/Article/details/gtykulrxbf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruoxtydm.html

[Q79] 字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gtrckyzveb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xziqi.cn/Article/details/gtgablxort.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtziiilnfu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtbftymeyg.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtquhvcfrk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtvrqjxvvo.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gtraeqbnlf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtgznwoscc.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtncpidfkp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtstnucyrt.html

[Q84] 去除首尾空格
来源：http://dali.jinqigufen.top/Article/details/gthdhjwltn.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtkletqoog.html

[Q85] 数值取整
来源：http://dali.jqgfzy.top/Article/details/gtbfeseysj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gtjyexmamj.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gtqxyloyyt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gotoacloud.top/Article/details/gtcxunckcx.html

[Q87] JSON 字段做条件
来源：http://dali.ybcxt.top/Article/details/gtpbfdtojf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gtpwfultki.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258.top/Article/details/gtxslvariz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjwwuttq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtpeblsqtf.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtpytzpoai.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shuidangran.top/Article/details/gtzraezhub.html

[Q90] 生成序号列
来源：http://dali.shuidangran.top/Article/details/gtoqjmucrb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gtoslykqzz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtyvidegus.html

R. Bash 专题
来源：http://dali.shuidangran.top/Article/details/gtdmiqpcan.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtxgcdshyh.html

[R01] shebang 与严格模式
来源：http://dali.hongshengwenyu.top/Article/details/gtyiymdwhb.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gtcazuwgmz.html

set -euo pipefail
来源：http://dali.chenzaomai.com/Article/details/gtpawhfjos.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gtwiufyfmm.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gtkmpmtcbt.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gtkovyxtlz.html

readonly PI=3.14
来源：http://dali.yangfankeji.com/Article/details/gtxpovocxg.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gtcspalhdw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gtbymzesic.html

[R05] 参数默认值
来源：http://dali.vqdsnc.cn/Article/details/gtjkthgxmo.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gtkjwktwrp.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gtnhddtbnq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtjctjkirs.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gtqkgcysyw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gtmbqjjxpj.html

[R08] 数值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmvvsnok.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gtndnipmlh.html

[R09] 字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gttrrwqfzc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gtbdydtgmc.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gtvfepieaw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrmgsgsg.html

[R11] case 多分支
来源：http://dali.jyoumei.cn/Article/details/gtqobekarx.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gtxuodmwzf.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggbalnqz.html

stop)  echo "停止" ;;
来源：http://dali.xuanzx.com/Article/details/gtlxeayjda.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258888.top/Article/details/gttmkdsgyj.html

esac
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdmdyuqb.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gtdjpasptl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shzxlz.cn/Article/details/gtalzokvki.html

[R13] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gtsmqractu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtwgaxytlq.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gtehucabce.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtgeawmjjr.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtywxwcalz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gtrqcvbkkd.html

[R16] until 等待条件
来源：http://dali.tian-w.cn/Article/details/gtfbsztuam.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtcyaobnst.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gtmuzccvln.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gtvnkbfwnd.html

[R18] 遍历数组
来源：http://dali.yvedp.cn/Article/details/gtqfiegoem.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gtjtorhvyj.html

[R19] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtguwbbntl.html

echo "${#arr[@]}"
来源：http://dali.iojbl.cn/Article/details/gtcklgxdyd.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gtohxqywom.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gtpqwapzuj.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gtioscbqxi.html

echo "${#s}"
来源：http://dali.yuxming.cn/Article/details/gtfkvrmfxv.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gthcgtujxk.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gtkglkpmjn.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtfypxdsfb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtrxonhydi.html

[R24] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtlctrnivg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtpviotjps.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gtxgshlvti.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.mhx1999.top/Article/details/gtyqvskbcs.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gtrdctupoe.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gtryuoyryw.html

[R27] 算术展开
来源：http://dali.hnxiangtu.top/Article/details/gtejzavlbz.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtmoqgezex.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqrdmzye.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gtsulsyryc.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtayndozap.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gttozimkko.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gtyaknskrq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daria6918.cn/Article/details/gtstjfbdid.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gtjuiggkvp.html

f() { local x=1; echo "$x"; }
来源：http://dali.yueranfly.top/Article/details/gtytnxlqrp.html

[R32] 参数个数校验
来源：http://dali.yj20258.top/Article/details/gtqntqnkjk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtdgrryoxd.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gtsbthtmht.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gtojceglmk.html

[R34] 退出时清理
来源：http://dali.yuanzhike.top/Article/details/gtvndxpnta.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gtknwwvmnr.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gtvyptdvro.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gtivogujtz.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gtobwrcjau.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cqqwz.cn/Article/details/gtsflpavtb.html

[R37] 把输出赋给变量
来源：http://dali.ehwqpu.com/Article/details/gtmyvhpsdk.html

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gtnagfialm.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gtnqrtzbku.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cucudq.cn/Article/details/gtseoacoog.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gtfhdjcfmr.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtxhzutukn.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gtomxwojwx.html

echo "log" >> out.log
来源：http://dali.jiagoushi.top/Article/details/gtbdbzpjlg.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gtgonwinoo.html

cmd >/dev/null 2>&1
来源：http://dali.redwolf501.top/Article/details/gttyafsltz.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gtyivnctig.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gtnvxnvuss.html

[R43] 按名字查找文件
来源：http://dali.xuetiantiany.cn/Article/details/gtvvdfghwe.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gthmpkqmig.html

[R44] 按修改时间查找
来源：http://dali.chenzaomai.com/Article/details/gtjxxxejam.html

find . -mtime -7 -type f
来源：http://dali.fzhhl.top/Article/details/gtfnuqmrwu.html

[R45] 批量删除
来源：http://dali.pengpengdd.cyou/Article/details/gtvbbszxgu.html

find . -name "*.tmp" -delete
来源：http://dali.c1oappe.top/Article/details/gtoeeaffkw.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gttaklpjrs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.birdmap.top/Article/details/gtpmlcooau.html

[R47] sed 单行替换
来源：http://dali.iojbl.cn/Article/details/gtgeltuefg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtblppkvyb.html

[R48] awk 取指定列
来源：http://dali.ydzc1.top/Article/details/gtdmbxwkkf.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtuigpqzmf.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gtpvglttgw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangdashe.top/Article/details/gtsweabkoz.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtjahrrpzj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gteeyjrrcq.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gttcwukcps.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.316326.xyz/Article/details/gtjrlltqey.html

[R52] 统计行数
来源：http://dali.hnqzz.top/Article/details/gtgrmqrsee.html

wc -l a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxoltryf.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkugraer.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuetiantiany.cn/Article/details/gtaotgrjpf.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gtzgkjjixk.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gtjjfiaezu.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gtnwjoleqn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gtcvijqlvo.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gtyitqkafp.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gtaitxaydp.html

[R57] 远程执行命令
来源：http://dali.zdqjudy.top/Article/details/gtvpmkyknv.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhxdsdua.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtohffgzij.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gtlbwedsga.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtjgcuvezc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtqltrrwnp.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtxdqvfxtf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenjidiqi.icu/Article/details/gtxeqkovkg.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gtcvockzre.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gtqlzzczho.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gtiiduaclq.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqozzvcm.html

[R63] 内存与进程
来源：http://dali.jiagoushi.top/Article/details/gtvnrffmip.html

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gtfpgoxrls.html

[R64] 结束进程
来源：http://dali.yuxming.cn/Article/details/gtfhskuuxw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtboxjvjyo.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gtfcctzpup.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gtjktcqhwk.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gtyarcdgrv.html

crontab -e;  crontab -l
来源：http://dali.cashguo.top/Article/details/gtwxhfbjzp.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gtifgtuzvr.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gtkifoygrd.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gteptpmhii.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtwcvfgsfm.html

[R69] 生成随机密码
来源：http://dali.feifeiyinyue.top/Article/details/gtbwjbvriq.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjshqhzcr.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gtvcwstqlj.html

date +%s;  date -d @1700000000
来源：http://dali.316326.xyz/Article/details/gtvfoukbqn.html

[R71] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gtzirwbouy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gtkfuacagr.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gtplpfgtne.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfbbovuz.html

[R73] 分割大日志
来源：http://dali.birdmap.top/Article/details/gtyhztnlms.html

split -l 1000 big.log part_
来源：http://dali.cashguo.top/Article/details/gteeoomwon.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gtgggmqnph.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gtcopxksby.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gtujofgvbr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gtncwgeoye.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gtergscyvl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtexcjpjmw.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gtcxddmeeh.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwwigvxo.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gtmrxlkbzo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gtqsauwqys.html

[R79] 解析命令行选项
来源：http://dali.zhixingplan.top/Article/details/gtbcbaoaiv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jlsjyb.cn/Article/details/gtbyzmtvcc.html

[R80] 查看脚本执行耗时
来源：http://dali.jlsjyb.cn/Article/details/gtgmakxeiw.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtmsnxnwzy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjthytdbb.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gtduxjpsak.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtygqptcvq.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gtchbqwkha.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gtiiyovpyh.html


<!-- 参考信息 -->