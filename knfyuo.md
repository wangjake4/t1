代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gtlmgwubdn.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtavhohtbh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdgpevkf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yueranfly.top/Article/details/gtbegkcltj.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gtrnckxvtd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcijtwnzn.html

[Q34] 每组取第一条
来源：http://dali.wangshuangyany.cn/Article/details/gtywiabdhl.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkknlvavp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gtljcvecwm.html

) t WHERE rn = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvvknrxb.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtqvpslkkf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtebdatzww.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gtckstpxbn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtnvcswoao.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtlgmkgitq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yueranfly.top/Article/details/gtoeceiwnm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjbttzgu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gteyhqfzsu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhiwuduotai.top/Article/details/gtyjaoqaai.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gtojwjaevi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gtqyudtltc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gtaredntag.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gtaydrzxwo.html

[Q41] 多表连接
来源：http://dali.chenjidiqi.icu/Article/details/gtngfirvww.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwvnjaax.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtuqpzxddp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgufenzy.top/Article/details/gtzwngljab.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gtrergrqoo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgufenzy.top/Article/details/gthgmuhnjs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.meibo888.top/Article/details/gtkqfhhgjv.html

[Q43] 标量子查询
来源：http://dali.havefunace.top/Article/details/gtlrbktxgj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.smart0.xyz/Article/details/gtcxnvuled.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gtroqrdkhr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gtodqzopab.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gttkudtbxr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtasjgnbge.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuxming.cn/Article/details/gtaaguyqco.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gttrzhzncr.html

[Q47] 与平均值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtvtddefqf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gtgedshqen.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtgvakybyw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenzaomai.com/Article/details/gtsdijwuxv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gtzfjcbtxg.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gtbvnaxqhl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gtxefjobcw.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gtahjzxxud.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtcwcmclnt.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gtsdstodmg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sysykeji.top/Article/details/gtgbkyjcby.html

[Q52] 删除指定行
来源：http://dali.guannengcc.top/Article/details/gtalzjndkm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtnmhnizxy.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gtumyrrcsa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sysykeji.top/Article/details/gtyephxvre.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gttqtvrqfy.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gtfjjsjpeq.html

[Q55] 排名（并列占位）
来源：http://dali.vqdsnc.cn/Article/details/gtvicvzlve.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ydzc1.top/Article/details/gthtpmqolq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilurwmmt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtyimubtzd.html

[Q57] 行号
来源：http://dali.chenlongwang.top/Article/details/gtbimokkzu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtqmxmobix.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gthcxwkrol.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtomrlwfgu.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gtrermgbxa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cheryme.top/Article/details/gttabndlph.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gttcdjatzo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangshuangyany.cn/Article/details/gtasmqlndg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtrxpjkiwu.html

[Q61] 移动平均
来源：http://dali.gzhubu.top/Article/details/gtlcguvvbk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtkuesiarx.html

[Q62] 分组占比
来源：http://dali.0kj1m.cn/Article/details/gtggwgpojs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtapbzougq.html

[Q63] 开启事务
来源：http://dali.svipenyu.cn/Article/details/gtdlogwxex.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gtokstpysy.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gtdpegvfke.html

COMMIT;
来源：http://dali.daxiang520.top/Article/details/gtmxbsvjye.html

[Q65] 回滚事务
来源：http://dali.jyoumei.cn/Article/details/gtzdpuqcrw.html

ROLLBACK;
来源：http://dali.wangshuangyany.cn/Article/details/gtwqbulewk.html

[Q66] 行锁查询
来源：http://dali.svipenyu.cn/Article/details/gtseslicjz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gtljcqymgp.html

[Q67] 设置隔离级别
来源：http://dali.aibaodan.cn/Article/details/gteqwgwkwm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangdashe.top/Article/details/gtdaekbdtp.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gtbgtobbzb.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gtmhpkvfsf.html

ROLLBACK TO sp1;
来源：http://dali.meibo888.top/Article/details/gtvqubwpxd.html

[Q69] 查看执行计划
来源：http://dali.aibaodan.cn/Article/details/gtfcdbnyuh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdrsjmoy.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtotnnvvgj.html

ANALYZE TABLE users;
来源：http://dali.zhoulong.xyz/Article/details/gtfiqwakvi.html

[Q71] 查看建表语句
来源：http://dali.haohaochexian.top/Article/details/gtqsemhliy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jianghu66.top/Article/details/gtdysbhxzd.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gtfwtznyzg.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtqkrzhett.html

[Q73] 查看表状态
来源：http://dali.hongshengwenyu.top/Article/details/gtbnzulyzn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gttkuzynvm.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gtlcxrfdrl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gtwvurxdsl.html

[Q75] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gtmhgavvcn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtbaqkiqey.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbzmjdml.html

[Q76] 按天统计
来源：http://dali.chenzaomai.com/Article/details/gtwhiasfpa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gtowjkqmkg.html

[Q77] 时间加减
来源：http://dali.guannengcc.top/Article/details/gtgjukggqr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtritdkgre.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gtesmanlzv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gtkxsconud.html

[Q79] 字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gttfzlowdr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxinkj.top/Article/details/gtfstinukt.html

[Q80] 字符串截取
来源：http://dali.hnxiangtu.top/Article/details/gtdtqanumw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj202588.top/Article/details/gtnxqoohws.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtckqzhtmz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtlkvawkbx.html

[Q82] 字符长度与字节长度
来源：http://dali.chenjidiqi.icu/Article/details/gtqgyknxqh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtqpzaayvi.html

[Q83] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gtzrcjrlaw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtnlpcxfij.html

[Q84] 去除首尾空格
来源：http://dali.fzhhl.top/Article/details/gtksnndqwf.html

SELECT TRIM(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtvshcmlya.html

[Q85] 数值取整
来源：http://dali.hnqzz.top/Article/details/gtusdjajsb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pengpengdd.cyou/Article/details/gtohcvrqyt.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigfzy.top/Article/details/gtfwzsrdtc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.mhx1999.top/Article/details/gttctxudgs.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gtxdfjtyto.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dashuyun.cn/Article/details/gtdrvlsfkx.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gtphdmyhvk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtnrsmamdh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtmkluwjxv.html

[Q89] 判断表是否存在
来源：http://dali.9152youxi.cn/Article/details/gtnaxwispv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gtisbbnmrn.html

[Q90] 生成序号列
来源：http://dali.jlsjyb.cn/Article/details/gtpiyodgxx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhoulong.xyz/Article/details/gtvoawgrhe.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtuewyhybb.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gtpkpawdpq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtssplhuti.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gtmrrohsoj.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gtezvqpucr.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gtuaiozjzq.html

[R02] 变量赋值与使用
来源：http://dali.xinyue.icu/Article/details/gtoacigkoa.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtruyugrnq.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gtdsisloeb.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gtxspwfcwf.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gtonxaydba.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gtofiicgha.html

[R05] 参数默认值
来源：http://dali.ehwqpu.com/Article/details/gthofmgrym.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gtemkycvtl.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gtyuadmkde.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gtvrwuwcgf.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gtgvqxddlb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuxming.cn/Article/details/gtxzikdemw.html

[R08] 数值比较
来源：http://dali.xuanzx.com/Article/details/gtobklaymo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtoccbjtpi.html

[R09] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gtwcethqfm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gthsxxmklf.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gtgqcgbtnk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tanke756.top/Article/details/gtrtcodots.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gtvdoepwvu.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtnuveenlp.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxypuzufl.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gtklpwijmd.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gtjuiogncd.html

esac
来源：http://dali.cqqwz.cn/Article/details/gtdbfwxrgd.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gtzmqxjjic.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xinyue.icu/Article/details/gtztbvyjqk.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gthurkmykk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtrboaushr.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gtofqtrvgk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtbdehzslw.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtoufdnpbb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gttopmgbab.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gtafezjmkp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gticaujwqx.html

[R17] 数组定义与取值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnptstbh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtdlcbyrfs.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gtahukattj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gtkebytfye.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtryfdmnxj.html

echo "${#arr[@]}"
来源：http://dali.shuidangran.top/Article/details/gtoiegexsl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gtgfqhyywe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yueranfly.top/Article/details/gtlczkqlki.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gthuaztvme.html

echo "${#s}"
来源：http://dali.zhoulong.xyz/Article/details/gtcidvbajw.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtomykwhrc.html

echo "${s:0:5}"
来源：http://dali.redwolf501.top/Article/details/gtrcfimggr.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtbpvqjkcg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gtpggrojfe.html

[R24] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtwapdihvu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.birdmap.top/Article/details/gtehoeynuv.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gtenpfjrdg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gtsjbkzgyg.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gtipcbvqpn.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gtmiqhlquq.html

[R27] 算术展开
来源：http://dali.hnxiangtu.top/Article/details/gtaynoscex.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtjzqawycv.html

[R28] 浮点运算
来源：http://dali.hongshengwenyu.top/Article/details/gtyblrglqq.html

echo "scale=2; 10/3" | bc
来源：http://dali.gaohongyu789.top/Article/details/gtkmsiveri.html

[R29] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtfhrjcfsv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenlongwang.top/Article/details/gteejuhnes.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gtjknhghdt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cdnleiting.top/Article/details/gtjylnjhvm.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gteoyxizgx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtamjsdehg.html

[R32] 参数个数校验
来源：http://dali.wangdashe.top/Article/details/gtlspugsuy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gtaiysbwmi.html

[R33] 捕获错误并提示行号
来源：http://dali.zycfv.cn/Article/details/gtarbtfrcp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.9152youxi.cn/Article/details/gtkquumfje.html

[R34] 退出时清理
来源：http://dali.xinyue.icu/Article/details/gtknonezvj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gteyqruwjw.html

[R35] 后台执行并等待
来源：http://dali.tanke756.top/Article/details/gtlyrzkiyz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guannengcc.top/Article/details/gtspfuokxo.html

[R36] 并发执行多个任务
来源：http://dali.yongpay.top/Article/details/gtcxbvjxme.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuetiantiany.cn/Article/details/gtzblmbmjg.html

[R37] 把输出赋给变量
来源：http://dali.meibo888.top/Article/details/gtfrlplvkp.html

files=$(ls -1)
来源：http://dali.dianchejie.cn/Article/details/gtktpknyfr.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gtuxuwnxhk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gtedkzjitj.html

[R39] 重定向标准输出与错误
来源：http://dali.chenzaomai.com/Article/details/gtwlvlnpbn.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifnowzfo.html

[R40] 追加写日志
来源：http://dali.ybcxt.top/Article/details/gtcxybrrgp.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gtdjimasdq.html

[R41] 丢弃输出
来源：http://dali.gogol.net.cn/Article/details/gtpynnvwlo.html

cmd >/dev/null 2>&1
来源：http://dali.yuanzhike.top/Article/details/gtwuhunszh.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gtbcxpnbqx.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtsmuzrejf.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gtglmcoxni.html

find . -name "*.log" -type f
来源：http://dali.havefunace.top/Article/details/gtxnffxxad.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gttricevpg.html

find . -mtime -7 -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtcwgyvtjv.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gtjfiakkgx.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gtnnsdlvmb.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gtpppzfomg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuanzx.com/Article/details/gtnauzwtbn.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtromnolnw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daxiang520.top/Article/details/gtkvinckhh.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gtwfutfkzq.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtdbeajhmy.html

[R49] awk 带条件
来源：http://dali.hnxiangtu.top/Article/details/gtlgzwkcia.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gtbuzophbi.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gtgmobguhb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtvjsfvstt.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gtewpaylwx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvolqxok.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqryhllv.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtnwkmcael.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gtjicztcic.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtictnfcdu.html

[R54] 比较两个文件
来源：http://dali.sweek.top/Article/details/gtlxshbgsf.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gtlljrbied.html

[R55] 压缩与解压
来源：http://dali.redwolf501.top/Article/details/gtwgqnwshq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gtafqdhpqz.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gtvcdntnfa.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtjvmqupih.html

[R57] 远程执行命令
来源：http://dali.dashuyun.cn/Article/details/gtnasafvga.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gtnbgqpdmt.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiwxqfut.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gtfsnyqeey.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtzvhmwjlh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.redwolf501.top/Article/details/gthjgymgdy.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtglfluoar.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gtgnpvwxqu.html

[R61] 磁盘占用
来源：http://dali.yanxiufei.cn/Article/details/gtcnubmxsp.html

df -h;  du -sh *
来源：http://dali.mhx1999.top/Article/details/gtutxlzmkj.html

[R62] 找最占空间的文件
来源：http://dali.aibaodan.cn/Article/details/gtbemepgqg.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gtfwpeodit.html

[R63] 内存与进程
来源：http://dali.yj202588.top/Article/details/gtganhvosi.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbozarlg.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gtatldhirm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gthfhrmbha.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gtuubwldfe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuanzhike.top/Article/details/gtiixgffxx.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gtrrveqwnj.html

crontab -e;  crontab -l
来源：http://dali.ppjwa.cn/Article/details/gtdpinzoqn.html

[R67] 生成随机十六进制串
来源：http://dali.ehwqpu.com/Article/details/gtbqkrpwyd.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gtgmussznq.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gtmovrcxpp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ybcxt.top/Article/details/gtljrnstuc.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gtjppcwmxu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zdqjudy.top/Article/details/gtahikjsli.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gtqqjoiqac.html

date +%s;  date -d @1700000000
来源：http://dali.xuanzx.com/Article/details/gtpqvdpyrr.html

[R71] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gtmkegrwfq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhongyouzk.top/Article/details/gtmzadkqvk.html

[R72] 等待端口就绪
来源：http://dali.bjfxy.top/Article/details/gtfbvuwanb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtucgqrrzi.html

[R73] 分割大日志
来源：http://dali.fengsongda.top/Article/details/gtcwznwhcl.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gtjoucpnvl.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gtieephoqw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jyoumei.cn/Article/details/gtsvnaiqdv.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gtcbwwbdcs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cqqwz.cn/Article/details/gtqyauqmwv.html

[R76] 使用临时文件
来源：http://dali.nanxuanxn.top/Article/details/gtmjhfwehm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtirkltgah.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gtaghdiwef.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gtzgkhjuis.html

[R78] 交互式菜单
来源：http://dali.guowangkeji.top/Article/details/gtbootkmsn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gtxwrbousu.html

[R79] 解析命令行选项
来源：http://dali.jinqigufen.top/Article/details/gtjwkbpacj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jyoumei.cn/Article/details/gtzbukiect.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gtwugcriln.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gtkirfyjog.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gttfgzuihu.html


<!-- 参考信息 -->