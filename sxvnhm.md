代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yvedp.cn/Article/details/gtegrbegut.html

[Q22] 排序
来源：http://dali.jinqigufen.top/Article/details/gtakvxtdhq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gtsjdsztaa.html

[Q23] 分页
来源：http://dali.xuanzx.com/Article/details/gtjordltke.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shangyingyoupin.top/Article/details/gtjeevmsie.html

[Q24] 去重
来源：http://dali.shuidangran.top/Article/details/gtxnkvclne.html

SELECT DISTINCT city FROM users;
来源：http://dali.iojbl.cn/Article/details/gtqoilauua.html

[Q25] 只取前 N 条
来源：http://dali.kuanghao11.cn/Article/details/gtbuifzont.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dianchejie.cn/Article/details/gttgzvrqkm.html

[Q26] 计数
来源：http://dali.ydzc1.top/Article/details/gtmcztqvur.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtjebbkplo.html

[Q27] 条件计数
来源：http://dali.nanxuanxn.top/Article/details/gtuwpxcnxd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.iojbl.cn/Article/details/gtmalusezi.html

[Q28] 求和与平均
来源：http://dali.cheryme.top/Article/details/gtnkdtlhfr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtpusbuesk.html

[Q29] 最大最小值
来源：http://dali.yj20258.top/Article/details/gtnuxivxxs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtxmwuioyw.html

[Q30] 分组统计
来源：http://dali.sxryk.cn/Article/details/gtencunqko.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gttnznflzm.html

[Q31] 分组后过滤
来源：http://dali.ehwqpu.com/Article/details/gteufzdcxq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakhiwrnp.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdnucyug.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gttbsaqcyd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gtloizvogx.html

[Q33] 多列分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtfivxcadz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvfklztd.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gtftotkoux.html

SELECT * FROM (
来源：http://dali.sysykeji.top/Article/details/gtcbdcgqyx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtzoltfesh.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gtlarypxbq.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gtgvmszdns.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtwuzifzgt.html

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gtewqrfzdn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyejunmyh.html

[Q37] 右连接
来源：http://dali.shzxlz.cn/Article/details/gtgojyuxrt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gtnhraasby.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuanzhike.top/Article/details/gtoqfzszdo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gtmhiiduwe.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gtampowhzn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daxiang520.top/Article/details/gtbtxqmgdv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gtrdpauduf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuxming.cn/Article/details/gtiapwrvkv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yvedp.cn/Article/details/gtbuwqwedh.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gtobibpdap.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gttdshybds.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xziqi.cn/Article/details/gthxbwfgeu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gtkgipzfzt.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtvrhzvrcn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jlsjyb.cn/Article/details/gtgajafphz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.quarkkingdee.top/Article/details/gtgzxgnaen.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gtqkjbxadm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gtshxpnrdc.html

[Q44] IN 子查询
来源：http://dali.redwolf501.top/Article/details/gtehjcrdvq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhixingplan.top/Article/details/gtzsznwsph.html

[Q45] EXISTS 判断存在
来源：http://dali.aizwys.cn/Article/details/gtdklmkqhc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtbnhqphey.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuxming.cn/Article/details/gtbqhtyjny.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gtidrgxegw.html

[Q47] 与平均值比较
来源：http://dali.vqdsnc.cn/Article/details/gtganusokx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gtixjfdhwc.html

[Q48] CTE 公用表表达式
来源：http://dali.gotoacloud.top/Article/details/gtzmzcmnab.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dianchejie.cn/Article/details/gtatqhnbub.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gtyqoazomu.html

[Q49] 更新单行
来源：http://dali.jqgfzy.top/Article/details/gtoojldsjj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gthlffskyg.html

[Q50] 批量更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsicicbe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtpbuzokew.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gtnwynwufm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gtgadjuikp.html

[Q52] 删除指定行
来源：http://dali.kuanghao11.cn/Article/details/gtfubpneqv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gtfclcwqeq.html

[Q53] 按条件删除
来源：http://dali.tian-w.cn/Article/details/gtsoeepuhv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcynmlmia.html

[Q54] 清空表
来源：http://dali.zhiwuduotai.top/Article/details/gtspnbkdnv.html

TRUNCATE TABLE logs;
来源：http://dali.sysykeji.top/Article/details/gtsuzucugd.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gtvsshvblu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtqskdvtaa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptgxgtef.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtcpwfwuoh.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gtrudazhqa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtzmnbxnbp.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gtbfjircat.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtnrpbncsu.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gtrsruxtmo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtnplbvwtn.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gtbxnkccgu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gtcszvwaru.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtjjgosmor.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gtxiixtnky.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtqwhydyuy.html

[Q62] 分组占比
来源：http://dali.zhengqikj.top/Article/details/gtjvxlddif.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtkvczutcj.html

[Q63] 开启事务
来源：http://dali.9152youxi.cn/Article/details/gtetnztmsh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aibaodan.cn/Article/details/gtwlmxahue.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gtvijsmfoo.html

COMMIT;
来源：http://dali.pycfn.com/Article/details/gtonixpxsy.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gtnmnzozfg.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gtgspiyzzp.html

[Q66] 行锁查询
来源：http://dali.gaohongyu789.top/Article/details/gtxcjvfcep.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gtprnjjpyl.html

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gtlgmnwdir.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgaopctzy.html

[Q68] 保存点
来源：http://dali.yonumen.top/Article/details/gttpjmdcyn.html

SAVEPOINT sp1;
来源：http://dali.sxryk.cn/Article/details/gthxrydhtb.html

ROLLBACK TO sp1;
来源：http://dali.haohaochexian.top/Article/details/gtbjljpcfb.html

[Q69] 查看执行计划
来源：http://dali.hammf.cn/Article/details/gtkufkmplb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.havefunace.top/Article/details/gturxkjqne.html

[Q70] 更新统计信息
来源：http://dali.pengpengdd.cyou/Article/details/gttymgbher.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gtsydfpvuo.html

[Q71] 查看建表语句
来源：http://dali.wangshuangyany.cn/Article/details/gtrgvlycai.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszxyiqwe.html

[Q72] 查看索引
来源：http://dali.daria6918.cn/Article/details/gtwkixhcpv.html

SHOW INDEX FROM users;
来源：http://dali.c1oappe.top/Article/details/gtqkcaqvay.html

[Q73] 查看表状态
来源：http://dali.xziqi.cn/Article/details/gtmwtjihpd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.bjfxy.top/Article/details/gtoicbkggq.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gtpmxpuzmo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hfpthk.cn/Article/details/gtskyqldru.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtohesedwu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fzhhl.top/Article/details/gttaktyetv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuanzx.com/Article/details/gtyikrynbs.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gthkkorxtp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guowangkeji.top/Article/details/gteqzmwstn.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gtrkhxsqqp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nwbrower.top/Article/details/gtfzamiwxv.html

[Q78] 当前时间
来源：http://dali.tian-w.cn/Article/details/gtplwjpjmt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gzhubu.top/Article/details/gtkgtapxfg.html

[Q79] 字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknhsmdso.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gtimaytfnk.html

[Q80] 字符串截取
来源：http://dali.daria6918.cn/Article/details/gtvfyyvlgb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gthcrgmqtu.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtcljiqedg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtcmyhzxxx.html

[Q82] 字符长度与字节长度
来源：http://dali.andypj.xyz/Article/details/gtcumgcafr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtozngarzt.html

[Q83] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtznrsnbsz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtpejbiegx.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gtknzkbttq.html

SELECT TRIM(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtguhkxqkc.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gtruswsbtv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hongshengwenyu.top/Article/details/gtvbnybdpt.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gtzjhdmogo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gogol.net.cn/Article/details/gthgcbmwsi.html

[Q87] JSON 字段做条件
来源：http://dali.xuanzx.com/Article/details/gtjhjjegcv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtyvjjywwj.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckguruic.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gtvdhaezos.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gtjjgpszlu.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gtwppreztq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlcgynkg.html

[Q90] 生成序号列
来源：http://dali.sweek.top/Article/details/gtbyyzexbh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhpujrly.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqktksylk.html

R. Bash 专题
来源：http://dali.shuidangran.top/Article/details/gtqetbilto.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gthqsuixtv.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gtniledtbo.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gtxnouekqg.html

set -euo pipefail
来源：http://dali.redwolf501.top/Article/details/gtsqhtntbt.html

[R02] 变量赋值与使用
来源：http://dali.fengsongda.top/Article/details/gtevgdydup.html

name="Tom"; echo "$name"
来源：http://dali.zhiwuduotai.top/Article/details/gtapzixxsu.html

[R03] 只读变量
来源：http://dali.vqdsnc.cn/Article/details/gtuxtihgcm.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gtojkilamj.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gtiqglosvj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj202588.top/Article/details/gtyvykdxck.html

[R05] 参数默认值
来源：http://dali.hongshengwenyu.top/Article/details/gtiserkuqv.html

name="${1:-default}"
来源：http://dali.quarkkingdee.top/Article/details/gtdzkpiwqd.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gthkhipidz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtffqznarz.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gtjsdryydo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gteexrnsbt.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gtgrewnrnk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gtdlncxnyj.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtetvozxoa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shuidangran.top/Article/details/gtkikvbtow.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gtpjcpgskp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtkcqtrccw.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gtcvipnobo.html

case "$1" in
来源：http://dali.guannengcc.top/Article/details/gtdtlnefgb.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gtzrfuwwbe.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gtccgjetbb.html

*)     echo "未知命令" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtkgczxwsu.html

esac
来源：http://dali.hywenlv.cn/Article/details/gtjmxbbdwb.html

[R12] for 遍历文件
来源：http://dali.hnxiangtu.top/Article/details/gtvmbcbvdz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gtoibmomov.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gttuwsmpws.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtuifbknfv.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gtgxtoztyu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtfglylkwf.html

[R15] while 逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtnklbbjsc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gtjdntdjmb.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gtcshpapzk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtctpgzfwg.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gtxlskhrwn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.havefunace.top/Article/details/gtokmmoydn.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gtlgkjahbb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gtvnaqrxjy.html

[R19] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtndccovdp.html

echo "${#arr[@]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtbpwgxqoo.html

[R20] 关联数组（字典）
来源：http://dali.redwolf501.top/Article/details/gtdhffgtmq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gtkwtqhmuf.html

[R21] 字符串长度
来源：http://dali.jiagoushi.top/Article/details/gtdybvuoig.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbsxcbye.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtouiooxdc.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gtbbvcyprl.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtikqyswzn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtqaxvrnbg.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtvcorxhtv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvtxelno.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtqsewxfak.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gtkfiktrbk.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtxhnkiisn.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gtgwrlyaeb.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gtnbzjdpet.html

echo $((1 + 2 * 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuqrbbbl.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gtoujcblow.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyomsmuy.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gtghtpiobv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyxqqxbv.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gthjtvokaz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gticxnatgy.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gtumqizbdk.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gtprorikxs.html

[R32] 参数个数校验
来源：http://dali.zhiwuduotai.top/Article/details/gtpdpvefag.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiaipslfw.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gtbrvarowh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gtuyxppvkg.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gtzeodxaue.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtpcjcykpf.html

[R35] 后台执行并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpmamsxx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gtdjekkchs.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gtkwggafsj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gtfgqnplpb.html

[R37] 把输出赋给变量
来源：http://dali.iojbl.cn/Article/details/gtemjopwvb.html

files=$(ls -1)
来源：http://dali.yj20258888.top/Article/details/gtyfyiapvf.html

[R38] 管道串联
来源：http://dali.mhx1999.top/Article/details/gtqvuryzla.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gttfjjcaxb.html

[R39] 重定向标准输出与错误
来源：http://dali.shzxlz.cn/Article/details/gtuttfowyc.html

cmd > out.log 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtmvthphmd.html

[R40] 追加写日志
来源：http://dali.fengsongda.top/Article/details/gtppgfwwol.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gtdjcvseph.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gtkfmxwhdr.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gtginmxucv.html

[R42] 输入重定向
来源：http://dali.bjfxy.top/Article/details/gtfkanaxvf.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbuzlchw.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gtwzqkvjgy.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gtedurltbj.html

[R44] 按修改时间查找
来源：http://dali.nanxinkj.top/Article/details/gtvntiksmt.html

find . -mtime -7 -type f
来源：http://dali.ehwqpu.com/Article/details/gtkckqsknk.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gtrwpravot.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gtclynoxer.html

[R46] 递归替换文件内容
来源：http://dali.xylfe.cn/Article/details/gtnojodahn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gtpbrlumye.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtudixugmp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gtlgrhkgyl.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gtvytngjcl.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtatpoaama.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gtptialrmd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gtgqgzcvyp.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gtkkdwjhwb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtmwavuhwk.html

[R51] 排序去重取前几
来源：http://dali.yvedp.cn/Article/details/gtendzybjf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj202588.top/Article/details/gtdcaxcnee.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gtwfeadxwf.html

wc -l a.txt
来源：http://dali.wangdashe.top/Article/details/gtqvezfepn.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxinkj.top/Article/details/gtjgxpjgsm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gtfwuhagmg.html

[R54] 比较两个文件
来源：http://dali.snrcjt.cn/Article/details/gtnpzlzolq.html

diff a.txt b.txt
来源：http://dali.jinqigfzy.top/Article/details/gtnfakusdc.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gtprdqdhtr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gtseofabjp.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuouvaenf.html

scp file user@host:/path/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunwosmjy.html

[R57] 远程执行命令
来源：http://dali.cashguo.top/Article/details/gtlyuczmao.html

ssh user@host 'uptime'
来源：http://dali.hnqzz.top/Article/details/gtqfnqnlgk.html

[R58] 下载文件
来源：http://dali.9152youxi.cn/Article/details/gtqjoflojv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shangyingyoupin.top/Article/details/gttdzlhnul.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtfjupokcj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gtnrapsbgx.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtbdgfhcgt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258888.top/Article/details/gtuohnklnj.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gtawokbuzq.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gtyoluqrza.html

[R62] 找最占空间的文件
来源：http://dali.wangshuangyany.cn/Article/details/gtoiexjxfw.html

du -ah . | sort -rh | head -10
来源：http://dali.andypj.xyz/Article/details/gtphslqokc.html

[R63] 内存与进程
来源：http://dali.yj20258.top/Article/details/gtrlzegnuh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gtrspmyccg.html

[R64] 结束进程
来源：http://dali.aizwys.cn/Article/details/gtmtetyskv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gtodssqasv.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gtatgfirzg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gtlpmvhyeu.html

[R66] 定时任务
来源：http://dali.sxryk.cn/Article/details/gtgjgoiagb.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gtaggfupxu.html

[R67] 生成随机十六进制串
来源：http://dali.jlsjyb.cn/Article/details/gtnggvcnyq.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gtumrwzsix.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkkujoyz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtpukxrobd.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gtsfbpvxox.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gtoxhhxtqf.html

[R70] 时间戳与互转
来源：http://dali.nanxuanxn.top/Article/details/gttjnoppkb.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gtosiwehks.html

[R71] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtwaudwwjz.html


<!-- 参考信息 -->