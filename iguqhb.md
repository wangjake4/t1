代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfpgdmee.html

[Q32] 分组拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2hrnzrves.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gt2pqglfqxf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yongpay.top/Article/details/gt2lvxlxohc.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gt2wzjelaid.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yueranfly.top/Article/details/gt2vawviuvo.html

[Q34] 每组取第一条
来源：http://dali.yanxiufei.cn/Article/details/gt2yhhkynrg.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gt2etrextbu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gt2mplepwnd.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2srvvtnfn.html

[Q35] 内连接
来源：http://dali.yj20258.top/Article/details/gt2ysijoaie.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gt2ivkwgknm.html

[Q36] 左连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2maqcdjck.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gt2nppehqvs.html

[Q37] 右连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvlimdem.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gt2nvsyqrds.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gt2icwvbufm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gt2upmrwhqd.html

[Q39] 自连接（查上下级）
来源：http://dali.gogol.net.cn/Article/details/gt2qvlylhlt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhoulong.xyz/Article/details/gt2fjmfeqbt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gt2dnpyrqpt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.bjfxy.top/Article/details/gt2donjjdgi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj202588.top/Article/details/gt2jgunwiqw.html

[Q41] 多表连接
来源：http://dali.cucudq.cn/Article/details/gt2jugxjwcb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gt2nqgjrnwh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gt2aosvoofh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gt2bizxcive.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2dfvuqwye.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qabfojsx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxinkj.top/Article/details/gt2xkdkbwku.html

[Q43] 标量子查询
来源：http://dali.mhx1999.top/Article/details/gt2mwkwuhic.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gt2pbdzljqo.html

[Q44] IN 子查询
来源：http://dali.xylfe.cn/Article/details/gt2zqtttina.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gt2jilmsvfd.html

[Q45] EXISTS 判断存在
来源：http://dali.quarkkingdee.top/Article/details/gt2nkucvwsg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gt2utonuskk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cheryme.top/Article/details/gt2twwledpi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gt2iemuutbu.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gt2pvdnbofh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gt2yelwmlug.html

[Q48] CTE 公用表表达式
来源：http://dali.mhx1999.top/Article/details/gt2zsjjnsew.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gt2tvszcjtp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gt2tjaixhpc.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gt2vzcsvcqy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gt2xzrtskyb.html

[Q50] 批量更新
来源：http://dali.chenlongwang.top/Article/details/gt2qeklqxzy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dianchejie.cn/Article/details/gt2duxaacpu.html

[Q51] 用子查询更新
来源：http://dali.yj20258.top/Article/details/gt2ncjrodxw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hcijlxck.html

[Q52] 删除指定行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2epeluhvm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtfsnrf.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gt2hoelhjgc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gt2yftaeeby.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gt2gkptpnhc.html

TRUNCATE TABLE logs;
来源：http://dali.tianlin.xyz/Article/details/gt2lfkmxtue.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gt2nseptplt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cashguo.top/Article/details/gt2fbvxlaav.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gt2qowvyzsg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gt2tqyuxjdo.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gt2eskegpbj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2aslsjbbj.html

[Q58] 累计求和
来源：http://dali.hysaishi.cn/Article/details/gt2larlhnod.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2gexjvkoc.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gt2diebrlaz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2mmyubbjx.html

[Q60] 取上一行 / 下一行
来源：http://dali.sxryk.cn/Article/details/gt2usztovtu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gt2xfmjyscu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2qemmbymt.html

[Q61] 移动平均
来源：http://dali.gzhubu.top/Article/details/gt2nlvqnntw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2ugbdouue.html

[Q62] 分组占比
来源：http://dali.cheryme.top/Article/details/gt2twapwobh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gt2egtjmfaj.html

[Q63] 开启事务
来源：http://dali.jyoumei.cn/Article/details/gt2dmxjqwdj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ehwqpu.com/Article/details/gt2sfxibwyj.html

[Q64] 提交事务
来源：http://dali.yj202588.top/Article/details/gt2recavdcn.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gt2wrurqlpy.html

[Q65] 回滚事务
来源：http://dali.gotoacloud.top/Article/details/gt2yghtpbpa.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gt2dyssemkx.html

[Q66] 行锁查询
来源：http://dali.bjfxy.top/Article/details/gt2llmddhse.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gt2fvpfgpjk.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gt2iiwiqmqu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gaohongyu789.top/Article/details/gt2dcbzufyl.html

[Q68] 保存点
来源：http://dali.xylfe.cn/Article/details/gt2tivqawum.html

SAVEPOINT sp1;
来源：http://dali.nanxinkj.top/Article/details/gt2yqwuzass.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2kcyrhzvq.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gt2lzenoany.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oxzrgrec.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gt2brxazeoz.html

ANALYZE TABLE users;
来源：http://dali.cqqwz.cn/Article/details/gt2bkyhcukq.html

[Q71] 查看建表语句
来源：http://dali.yvedp.cn/Article/details/gt2bjffvosd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yvedp.cn/Article/details/gt2jiznpbwy.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gt2froqvxis.html

SHOW INDEX FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2raoaqele.html

[Q73] 查看表状态
来源：http://dali.feifeiyinyue.top/Article/details/gt2zatbztfe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.birdmap.top/Article/details/gt2jtslkzca.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gt2eopbzuxl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdbmmrau.html

[Q75] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gt2ttqldjiy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2lqrxvzfg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.redwolf501.top/Article/details/gt2ckdyavle.html

[Q76] 按天统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajudbpqg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ppjwa.cn/Article/details/gt2rvurtbxn.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gt2hrczuixm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdszwgab.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iyheqzoq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jlsjyb.cn/Article/details/gt2ovefbeeo.html

[Q79] 字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gt2ybjlompb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gt2gtcifwfr.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gt2icakiwte.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2snbtdujy.html

[Q81] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gt2qyqiunha.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgkajnck.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gt2tjltensi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2iupmwuuf.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gt2qrgjoayx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2mbsytidp.html

[Q84] 去除首尾空格
来源：http://dali.0kj1m.cn/Article/details/gt2mdxdneqy.html

SELECT TRIM(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2aclddtya.html

[Q85] 数值取整
来源：http://dali.hfpthk.cn/Article/details/gt2mlipyisf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gt2mifvplpq.html

[Q86] 读取 JSON 字段
来源：http://dali.gzhubu.top/Article/details/gt2gjcgsfhd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gt2bjbhvarh.html

[Q87] JSON 字段做条件
来源：http://dali.kuanghao11.cn/Article/details/gt2inkcmdef.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqkvpepk.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gt2ptneijeb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjmwxtaa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2wzfxerom.html

[Q89] 判断表是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2dzvymhwa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangdashe.top/Article/details/gt2sltyjknt.html

[Q90] 生成序号列
来源：http://dali.zhengqikj.top/Article/details/gt2euvrevcr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxinkj.top/Article/details/gt2ouidpvsg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2htuvaqhe.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ppmagrrn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2vuuvpgwy.html

[R01] shebang 与严格模式
来源：http://dali.chenlongwang.top/Article/details/gt2jtlmhquj.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gt2vcenzzlg.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehmxzngu.html

[R02] 变量赋值与使用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzhduwtw.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gt2lepqskkw.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gt2amhaectt.html

readonly PI=3.14
来源：http://dali.yuxming.cn/Article/details/gt2vewieqsl.html

[R04] 位置参数
来源：http://dali.hysaishi.cn/Article/details/gt2tnohllio.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pycfn.com/Article/details/gt2nskzkxir.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gt2mrfposvv.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gt2xcvxknpi.html

[R06] 判断命令是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2qinwmats.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gt2nbottvek.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gt2msrtpwne.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2ujhiayst.html

[R08] 数值比较
来源：http://dali.quarkkingdee.top/Article/details/gt2ynpswnlv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.andypj.xyz/Article/details/gt2uelzpsgp.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gt2irnrzuga.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yueranfly.top/Article/details/gt2svwnlidy.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2acjyecfw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yongpay.top/Article/details/gt2ifidsnal.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gt2vkxufwnl.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gt2odrtpkwd.html

start) echo "启动" ;;
来源：http://dali.mhx1999.top/Article/details/gt2nqedbbzm.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqqoqkst.html

*)     echo "未知命令" ;;
来源：http://dali.mhx1999.top/Article/details/gt2judxprxv.html

esac
来源：http://dali.hnqzz.top/Article/details/gt2xtudomwx.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gt2rmywweyy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gt2rmwvznla.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gt2lltqftmv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gt2zdyhcfzf.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gt2dcviipih.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gt2litomwwk.html

[R15] while 逐行读文件
来源：http://dali.wangdashe.top/Article/details/gt2qjifdgfu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2mmqubdvf.html

[R16] until 等待条件
来源：http://dali.yongpay.top/Article/details/gt2aobtvhjm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2ykauqzwe.html

[R17] 数组定义与取值
来源：http://dali.hywenlv.cn/Article/details/gt2wdnbnchp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfclbuha.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkwuyxlq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gt2bkpiltzx.html

[R19] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2igmjcszt.html

echo "${#arr[@]}"
来源：http://dali.sufxvd.cn/Article/details/gt2yhwhngwk.html

[R20] 关联数组（字典）
来源：http://dali.sysykeji.top/Article/details/gt2yatzowhn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2liexfagr.html

[R21] 字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gt2cwivldpu.html

echo "${#s}"
来源：http://dali.cqqwz.cn/Article/details/gt2kmnbjudi.html

[R22] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gt2figbrxxi.html

echo "${s:0:5}"
来源：http://dali.ivvv.top/Article/details/gt2bnzfwsym.html

[R23] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gt2kuxsysfx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqlmeeqi.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gt2gbfqkggw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gt2qddwgyag.html

[R25] 去后缀 / 去前缀
来源：http://dali.cheryme.top/Article/details/gt2eistgwqy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guannengcc.top/Article/details/gt2drlhxxhe.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2axnfavic.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gt2jliuudjj.html

[R27] 算术展开
来源：http://dali.shangyingyoupin.top/Article/details/gt2pizvrcug.html

echo $((1 + 2 * 3))
来源：http://dali.9152youxi.cn/Article/details/gt2hjnmymzq.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcnjrgbo.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nklrwgjc.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gt2izbrjzpi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hfpthk.cn/Article/details/gt2xdxvnumz.html

[R30] 函数返回状态码
来源：http://dali.xziqi.cn/Article/details/gt2lxliirdy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gt2slaeavkx.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gt2ciiacmjc.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gt2fujyrttv.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gt2udtpoznt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2geqmaehc.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gt2srjssenn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfkwgdfg.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plorqdwr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2qwmmujxo.html

[R35] 后台执行并等待
来源：http://dali.chenlongwang.top/Article/details/gt2iecudxkp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gt2zdylcchv.html

[R36] 并发执行多个任务
来源：http://dali.zycfv.cn/Article/details/gt2wtjcmcsi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gt2fdreisls.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gt2wkaojizi.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gt2fsjjsist.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gt2zjgaqrxx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dianchejie.cn/Article/details/gt2cnqtvhgh.html

[R39] 重定向标准输出与错误
来源：http://dali.tianlin.xyz/Article/details/gt2wqkeqxbe.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gt2pgxqdthr.html

[R40] 追加写日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eolvxxhh.html

echo "log" >> out.log
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvrrqeer.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gt2qrzoectu.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gt2vbjxjfna.html

[R42] 输入重定向
来源：http://dali.sysykeji.top/Article/details/gt2cxzhzhuu.html

wc -l < a.txt
来源：http://dali.fzhhl.top/Article/details/gt2xtbstjgz.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccvhnqkp.html

find . -name "*.log" -type f
来源：http://dali.yongpay.top/Article/details/gt2zvcpnuwz.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gt2khjiwton.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gt2oetyxvdg.html

[R45] 批量删除
来源：http://dali.9152youxi.cn/Article/details/gt2momlpdbh.html

find . -name "*.tmp" -delete
来源：http://dali.bjfxy.top/Article/details/gt2gtvrdjok.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gt2ntfwgszs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenzaomai.com/Article/details/gt2jgxslulw.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gt2rceiieys.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2blqfbmdw.html

[R48] awk 取指定列
来源：http://dali.redwolf501.top/Article/details/gt2ythpwnbf.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gt2girxdcds.html

[R49] awk 带条件
来源：http://dali.dashuyun.cn/Article/details/gt2iklgbabj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pengpengdd.cyou/Article/details/gt2chqfvrod.html

[R50] awk 求和
来源：http://dali.yanxiufei.cn/Article/details/gt2cteulyyr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2dreseehv.html

[R51] 排序去重取前几
来源：http://dali.xylfe.cn/Article/details/gt2mylbawrr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gt2jjyxxyni.html

[R52] 统计行数
来源：http://dali.quarkkingdee.top/Article/details/gt2rdhxvjdw.html

wc -l a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2bnjfzcrc.html

[R53] 查看文件头与实时尾
来源：http://dali.ybcxt.top/Article/details/gt2nohcacgd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gt2fjkibsnp.html

[R54] 比较两个文件
来源：http://dali.ivvv.top/Article/details/gt2tqijgdsp.html

diff a.txt b.txt
来源：http://dali.dashuyun.cn/Article/details/gt2coecwphx.html

[R55] 压缩与解压
来源：http://dali.hysaishi.cn/Article/details/gt2nkdplvsw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gt2zrfndtra.html

[R56] 远程拷贝
来源：http://dali.yonumen.top/Article/details/gt2ofnxgsgb.html

scp file user@host:/path/
来源：http://dali.xylfe.cn/Article/details/gt2lxlxualf.html

[R57] 远程执行命令
来源：http://dali.dashuyun.cn/Article/details/gt2qkimcomr.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gt2wcnpceyt.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gt2vopgciio.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gt2lpjrsohi.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2qvqubcwq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.9152youxi.cn/Article/details/gt2mmhdyuga.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lakrdbit.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.redwolf501.top/Article/details/gt2myfzlwce.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwqfiktd.html

df -h;  du -sh *
来源：http://dali.jqgfzy.top/Article/details/gt2qaikvfru.html

[R62] 找最占空间的文件
来源：http://dali.yj202588.top/Article/details/gt2zruptito.html

du -ah . | sort -rh | head -10
来源：http://dali.fzhhl.top/Article/details/gt2dbfvmouk.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gt2wxtjyqia.html

free -h;  ps aux | grep nginx
来源：http://dali.zhixingplan.top/Article/details/gt2fsdwddll.html

[R64] 结束进程
来源：http://dali.dashuyun.cn/Article/details/gt2qbmkgogh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yanxiufei.cn/Article/details/gt2zpojtscr.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmlgysij.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gt2irncgrxx.html

[R66] 定时任务
来源：http://dali.havefunace.top/Article/details/gt2khtmfgbz.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gt2uzxetfdu.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gt2apnmgvty.html

openssl rand -hex 16
来源：http://dali.jyoumei.cn/Article/details/gt2iyuqgwpw.html

[R68] 计算文件校验值
来源：http://dali.yvedp.cn/Article/details/gt2llkmebil.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yvedp.cn/Article/details/gt2wcrmmnkl.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gt2scsfelzp.html

head -c 16 /dev/urandom | base64
来源：http://dali.xziqi.cn/Article/details/gt2xvrbxoxb.html

[R70] 时间戳与互转
来源：http://dali.gogol.net.cn/Article/details/gt2wwkfgldi.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gt2pjnsxvlx.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gt2zwbtxmtf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.birdmap.top/Article/details/gt2djvhyful.html

[R72] 等待端口就绪
来源：http://dali.gzhubu.top/Article/details/gt2upsmerpp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gt2azktbgdx.html

[R73] 分割大日志
来源：http://dali.ppjwa.cn/Article/details/gt2fpywtoxn.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gt2tlrnfkva.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gt2bayiecrv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gt2lttiiimr.html

[R75] 导出环境变量
来源：http://dali.c1oappe.top/Article/details/gt2hlwcemai.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuanzx.com/Article/details/gt2shynstyd.html

[R76] 使用临时文件
来源：http://dali.cqqwz.cn/Article/details/gt2jxevzrwx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dpozxcnv.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gt2jnrnktva.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gt2gnrztbmm.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ofkmhueg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnxiangtu.top/Article/details/gt2vvsurbpq.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gt2burbntcs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gt2sllamgmq.html

[R80] 查看脚本执行耗时
来源：http://dali.cheryme.top/Article/details/gt2zonmbjhy.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpihtfwd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2loeegufp.html


<!-- 参考信息 -->