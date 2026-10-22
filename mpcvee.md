代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tanke756.top/Article/details/gt2jczvyrcv.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2cjgwcsfq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gt2jndpxgvj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxinkj.top/Article/details/gt2etcdmnox.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gt2nckdqshh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cashguo.top/Article/details/gt2gztcklnc.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gt2nsnutkxp.html

SELECT * FROM (
来源：http://dali.andypj.xyz/Article/details/gt2libkuydt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nwbrower.top/Article/details/gt2rxvvmxjo.html

) t WHERE rn = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2uorgtbpt.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gt2gpyracrp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gt2sduewwva.html

[Q36] 左连接
来源：http://dali.ybcxt.top/Article/details/gt2tbgwfjwu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gt2iwpdjiri.html

[Q37] 右连接
来源：http://dali.yonumen.top/Article/details/gt2mvjvgckc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gt2hmqivcyy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nfiwixup.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jyoumei.cn/Article/details/gt2ioozgdud.html

[Q39] 自连接（查上下级）
来源：http://dali.birdmap.top/Article/details/gt2ybgkdcjb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cheryme.top/Article/details/gt2nppiipri.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fengsongda.top/Article/details/gt2qmdjizhw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gt2zlbqrmsa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gt2rhsvsksw.html

[Q41] 多表连接
来源：http://dali.yanxiufei.cn/Article/details/gt2rqrdtwsf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shangyingyoupin.top/Article/details/gt2livwwkug.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2niizintt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yonumen.top/Article/details/gt2jmnaynhg.html

[Q42] 连接条件附加过滤
来源：http://dali.zdqjudy.top/Article/details/gt2iztmwmpi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuanzhike.top/Article/details/gt2lohpmigu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gt2rzdkdmph.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gt2qeloooof.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shzxlz.cn/Article/details/gt2xbzwdoos.html

[Q44] IN 子查询
来源：http://dali.bjfxy.top/Article/details/gt2orzerrcz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daria6918.cn/Article/details/gt2izgmozqq.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2txwvryhv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gt2rbsmshfz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2slrfteng.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tygjivsw.html

[Q47] 与平均值比较
来源：http://dali.xylfe.cn/Article/details/gt2zqvewlvq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ehwqpu.com/Article/details/gt2twenlqgd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tgtyiqdn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tian-w.cn/Article/details/gt2sddnmlao.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ydzc1.top/Article/details/gt2dcscxayu.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gt2lespzttw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2hyxxxwdu.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfrjllny.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jyoumei.cn/Article/details/gt2hbthrwbt.html

[Q51] 用子查询更新
来源：http://dali.zycfv.cn/Article/details/gt2nxaczymf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xziqi.cn/Article/details/gt2krrktvuj.html

[Q52] 删除指定行
来源：http://dali.fzhhl.top/Article/details/gt2frkzydfj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gt2ixlbavtb.html

[Q53] 按条件删除
来源：http://dali.nwbrower.top/Article/details/gt2eptsukxx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gt2wquzbjah.html

[Q54] 清空表
来源：http://dali.jlsjyb.cn/Article/details/gt2snvnyekg.html

TRUNCATE TABLE logs;
来源：http://dali.snrcjt.cn/Article/details/gt2pafhftqr.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gt2jzyiejtu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gt2fuidhzbt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dashuyun.cn/Article/details/gt2ptaabvpe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gt2lcncqjxp.html

[Q57] 行号
来源：http://dali.ppjwa.cn/Article/details/gt2okjwyqck.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2wicrfybf.html

[Q58] 累计求和
来源：http://dali.yvedp.cn/Article/details/gt2xqtptmer.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2umnuchqu.html

[Q59] 分组内累计
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwuhazro.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2mzvrpneg.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gt2uoqfnfuu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cdnleiting.top/Article/details/gt2cbnhabed.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2kslbxdda.html

[Q61] 移动平均
来源：http://dali.yongpay.top/Article/details/gt2uolvinqy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2tgiwpcso.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gt2irxmqlrx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2ktpuisak.html

[Q63] 开启事务
来源：http://dali.zhoulong.xyz/Article/details/gt2gkdmofez.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258888.top/Article/details/gt2zkukdrsq.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gt2zdtpopam.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gt2iqdmlfof.html

[Q65] 回滚事务
来源：http://dali.yongpay.top/Article/details/gt2hbdkwgdn.html

ROLLBACK;
来源：http://dali.tanke756.top/Article/details/gt2ajqxzevd.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gt2hajnwomz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbpzvmts.html

[Q67] 设置隔离级别
来源：http://dali.aibaodan.cn/Article/details/gt2yxesmhmg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gogol.net.cn/Article/details/gt2tgslztpr.html

[Q68] 保存点
来源：http://dali.xuetiantiany.cn/Article/details/gt2mczkdtem.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gt2bnjjgljb.html

ROLLBACK TO sp1;
来源：http://dali.redwolf501.top/Article/details/gt2ghonscpc.html

[Q69] 查看执行计划
来源：http://dali.jqgufenzy.top/Article/details/gt2wwrlxukl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gt2ulawyjyg.html

[Q70] 更新统计信息
来源：http://dali.tianlin.xyz/Article/details/gt2abtvkrid.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gt2pfbpqwkx.html

[Q71] 查看建表语句
来源：http://dali.yonumen.top/Article/details/gt2cofcjxwx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hfpthk.cn/Article/details/gt2djfbbmzf.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixhmismu.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gt2cajnrpuo.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gt2erbtniiq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gt2npoacrfn.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gt2nxkrrltu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daria6918.cn/Article/details/gt2tbrpfdkd.html

[Q75] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gt2shmekxln.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2pvonngnj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yueranfly.top/Article/details/gt2yhbhdwsu.html

[Q76] 按天统计
来源：http://dali.nanxuanxn.top/Article/details/gt2ifhxtkcx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fzhhl.top/Article/details/gt2xcyjxclk.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gt2hoevnjfj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guowangkeji.top/Article/details/gt2gnsuputk.html

[Q78] 当前时间
来源：http://dali.shzxlz.cn/Article/details/gt2xicouxjv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gt2suiporsk.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gt2chlubhyj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gt2nrvvusjr.html

[Q80] 字符串截取
来源：http://dali.daria6918.cn/Article/details/gt2cnzzulxv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2khputxdi.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gt2fiyswbrr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2blqmpiue.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gt2ptctiubo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2hrugomzz.html

[Q83] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gt2lovddkdf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2yhjbhyur.html

[Q84] 去除首尾空格
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpmyupkf.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2rtrahqnd.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gt2rypvghlm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gt2moihkshz.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gt2shxhpbvj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gt2ceifxvqs.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzuojshs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzkfpnep.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gt2bvnosukf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.316326.xyz/Article/details/gt2coztoqbd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2upxpxbjs.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2yctpcvji.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gt2rciwwdpd.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gt2pudfkxts.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gt2xvztjefu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ltjwzhwv.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gt2iryevjgw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnlfdelw.html

[R01] shebang 与严格模式
来源：http://dali.c1oappe.top/Article/details/gt2sbkclnnv.html

#!/usr/bin/env bash
来源：http://dali.daria6918.cn/Article/details/gt2fyojkwik.html

set -euo pipefail
来源：http://dali.havefunace.top/Article/details/gt2zubahlza.html

[R02] 变量赋值与使用
来源：http://dali.redwolf501.top/Article/details/gt2aqxwpmtg.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gt2ktikxode.html

[R03] 只读变量
来源：http://dali.ehwqpu.com/Article/details/gt2xjpqquzj.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gt2tfmelssc.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmtozusu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gt2tafdgqhb.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gt2rlspcufv.html

name="${1:-default}"
来源：http://dali.tanke756.top/Article/details/gt2vlkmuuim.html

[R06] 判断命令是否存在
来源：http://dali.smart0.xyz/Article/details/gt2uszjwmgn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bchbosuy.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhajbfvn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2obnysclh.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gt2jqtmvnvc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gt2uquzdxev.html

[R09] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gt2hthtzvwc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2snkwfsey.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gt2heuxmlfe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2sbifggaw.html

[R11] case 多分支
来源：http://dali.hongshengwenyu.top/Article/details/gt2zetnygla.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzqyvpcj.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2zovasonv.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gt2dsrugxhs.html

*)     echo "未知命令" ;;
来源：http://dali.xinyue.icu/Article/details/gt2zgfvzolr.html

esac
来源：http://dali.jianghu66.top/Article/details/gt2cxhqvuse.html

[R12] for 遍历文件
来源：http://dali.yueranfly.top/Article/details/gt2vhueeszn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gt2rcrrzuxg.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gt2nqiyfqbw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2jblseagv.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gt2yhafkzlx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gt2mmxlvubq.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2zifclbyy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2ldfjlwec.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqcfdvtl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2nbxgirlo.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gt2jvrhfrxo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zycfv.cn/Article/details/gt2zchlvsbv.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gt2xjtjslxa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gt2bdudsrmc.html

[R19] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gt2lfykizty.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gt2ufpxhyya.html

[R20] 关联数组（字典）
来源：http://dali.chenjidiqi.icu/Article/details/gt2fcnpdixn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfkonwr.html

[R21] 字符串长度
来源：http://dali.jiagoushi.top/Article/details/gt2fucphixn.html

echo "${#s}"
来源：http://dali.yuxming.cn/Article/details/gt2ltfjszxp.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gt2dibwrzar.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gt2liggykap.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmnjdxr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mpwepbko.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2zxvobbzn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yanxiufei.cn/Article/details/gt2tfcbdjsb.html

[R25] 去后缀 / 去前缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvzuxztt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gt2wnepjcru.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2huqekkuv.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gt2olcnxncr.html

[R27] 算术展开
来源：http://dali.pengpengdd.cyou/Article/details/gt2peewyjfn.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gt2ldorsvpv.html

[R28] 浮点运算
来源：http://dali.yanxiufei.cn/Article/details/gt2ueevzfkv.html

echo "scale=2; 10/3" | bc
来源：http://dali.316326.xyz/Article/details/gt2hfhjccfn.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gt2fzmipgrf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gt2rkydroix.html

[R30] 函数返回状态码
来源：http://dali.yvedp.cn/Article/details/gt2fjenuwbi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yongpay.top/Article/details/gt2bkavclag.html

[R31] 局部变量
来源：http://dali.jinqigfzy.top/Article/details/gt2pxruserp.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gt2twwuwrzs.html

[R32] 参数个数校验
来源：http://dali.yangfankeji.com/Article/details/gt2nfhntzjt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wszhinle.html

[R33] 捕获错误并提示行号
来源：http://dali.sysykeji.top/Article/details/gt2wsbbrfbc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aflekdwt.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gt2othinqrx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gt2dqrlqrcf.html

[R35] 后台执行并等待
来源：http://dali.hnxiangtu.top/Article/details/gt2rlbjrdse.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gt2yolmrday.html

[R36] 并发执行多个任务
来源：http://dali.daxiang520.top/Article/details/gt2bnzwjiem.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gt2jyrgfdbr.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gt2fxxmrfdd.html

files=$(ls -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2gvukagyy.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gt2sqffytzt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gt2wuagmpka.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gt2haedsqru.html

cmd > out.log 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nnjuqcou.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gt2fpjezhdt.html

echo "log" >> out.log
来源：http://dali.bjfxy.top/Article/details/gt2zuofdxzx.html

[R41] 丢弃输出
来源：http://dali.aizwys.cn/Article/details/gt2znrfbzkg.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gt2tbdbadwu.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gt2twpelnzy.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gt2sduyqqto.html

[R43] 按名字查找文件
来源：http://dali.sweek.top/Article/details/gt2rzwplvvb.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gt2dgrwgqnn.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmoaokic.html

find . -mtime -7 -type f
来源：http://dali.xuanzx.com/Article/details/gt2cohibrjh.html

[R45] 批量删除
来源：http://dali.fzhhl.top/Article/details/gt2lepnagai.html

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gt2jbultief.html

[R46] 递归替换文件内容
来源：http://dali.zhiwuduotai.top/Article/details/gt2vggyamxe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gt2ftqypxui.html

[R47] sed 单行替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qyeyuhrd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2btjpzglz.html

[R48] awk 取指定列
来源：http://dali.daxiang520.top/Article/details/gt2icuikvnx.html

awk '{print $1, $3}' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2xtioiwax.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2riankhhd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gt2hqusorkq.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gt2cyqayuli.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2htibzlft.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gt2hrbtjltz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xylfe.cn/Article/details/gt2badkhdax.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gt2qgcovjgo.html

wc -l a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2zhqkdnck.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gt2pxnoyxdy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gt2pixycaet.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnewmefq.html

diff a.txt b.txt
来源：http://dali.316326.xyz/Article/details/gt2dhwjmwef.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gt2ncgvrume.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gt2aqirxgul.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gt2ffkcumns.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qeomzxbb.html

[R57] 远程执行命令
来源：http://dali.cqqwz.cn/Article/details/gt2egcbclhn.html

ssh user@host 'uptime'
来源：http://dali.dashuyun.cn/Article/details/gt2gwuxvyxz.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gt2nydgpikh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.vqdsnc.cn/Article/details/gt2wtsqlokd.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gt2qwsqtfkm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gt2naaxrfju.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gt2raoxazvq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gt2pdsgkvzx.html

[R61] 磁盘占用
来源：http://dali.zhongyouzk.top/Article/details/gt2fwczshea.html

df -h;  du -sh *
来源：http://dali.chenlongwang.top/Article/details/gt2jvffaqau.html

[R62] 找最占空间的文件
来源：http://dali.tian-w.cn/Article/details/gt2rrkoxulz.html

du -ah . | sort -rh | head -10
来源：http://dali.meibo888.top/Article/details/gt2swaszrib.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pnlhwylt.html

free -h;  ps aux | grep nginx
来源：http://dali.vqdsnc.cn/Article/details/gt2aatimgha.html

[R64] 结束进程
来源：http://dali.guowangkeji.top/Article/details/gt2gytxjipi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gt2eyzijenc.html

[R65] 查看端口占用
来源：http://dali.aizwys.cn/Article/details/gt2jezlgdge.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gt2sgymkxoz.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gt2uqsmfcqz.html

crontab -e;  crontab -l
来源：http://dali.zycfv.cn/Article/details/gt2aqfhepvy.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gt2teojlvwr.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gt2liatgomw.html

[R68] 计算文件校验值
来源：http://dali.bjfxy.top/Article/details/gt2xdotusho.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2ipclmgtm.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gt2qvkmvkld.html

head -c 16 /dev/urandom | base64
来源：http://dali.gaohongyu789.top/Article/details/gt2nmfbkgrp.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gt2ulhsbiot.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gt2dhhsrzio.html

[R71] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2gbrfhqmx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gt2ijqdjsnq.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tnxuwadb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gt2mclfqzsa.html

[R73] 分割大日志
来源：http://dali.jyoumei.cn/Article/details/gt2hafwzaya.html

split -l 1000 big.log part_
来源：http://dali.cqqwz.cn/Article/details/gt2rsuisbfq.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gt2iiknydvn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gt2vqvrwpqb.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gt2gobsubml.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gt2skqiallu.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gt2rczjvpck.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gt2xzovpfpv.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gt2ndqsnhih.html

read -rp "请输入: " ans
来源：http://dali.aibaodan.cn/Article/details/gt2zgaqhbor.html

[R78] 交互式菜单
来源：http://dali.c1oappe.top/Article/details/gt2wfksqzew.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gt2qimeivlm.html

[R79] 解析命令行选项
来源：http://dali.hammf.cn/Article/details/gt2ujbjdhsu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxbjkgax.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gt2cxruwmqi.html

time ./run.sh
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2opywfood.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2tqcaoiyl.html


<!-- 参考信息 -->