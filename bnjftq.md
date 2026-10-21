代发 wailian999

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gtmdsxaywa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtxvedpzyk.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gtvshxquqy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258.top/Article/details/gtbrvgrycz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtmuflguna.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cdnleiting.top/Article/details/gtsijunaze.html

[Q39] 自连接（查上下级）
来源：http://dali.jianghu66.top/Article/details/gtodwlpznr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.kuanghao11.cn/Article/details/gtkquduukv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gtaapgiknq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aibaodan.cn/Article/details/gtccegydoy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gotoacloud.top/Article/details/gtqpqkulnf.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gtwlfuwheu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hfpthk.cn/Article/details/gtcuzgrska.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigufen.top/Article/details/gtscljndkq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxuanxn.top/Article/details/gtkcqsihjj.html

[Q42] 连接条件附加过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtirwwqmmm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gtgfhujogy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zycfv.cn/Article/details/gtmrqttwyf.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gtmolailsy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ivvv.top/Article/details/gtfuakqnfv.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gthsohyhns.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.svipenyu.cn/Article/details/gtmqmqzvor.html

[Q45] EXISTS 判断存在
来源：http://dali.nwbrower.top/Article/details/gtzxwsrpjz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtxjvpgxrd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gtqvnqwvjl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtgsljxogu.html

[Q47] 与平均值比较
来源：http://dali.xziqi.cn/Article/details/gtrqavccwv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yonumen.top/Article/details/gtcrupedye.html

[Q48] CTE 公用表表达式
来源：http://dali.guowangkeji.top/Article/details/gtsuiujxcu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gtexrdpuqb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ivvv.top/Article/details/gthsdklrdp.html

[Q49] 更新单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpfhgvug.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gteyfuvpwj.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gtbsqimfaw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ybcxt.top/Article/details/gtwssdktcq.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gtcjjrwcve.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jianghu66.top/Article/details/gttzgpyyxe.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gtultjzcsy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtlmxxwvqk.html

[Q53] 按条件删除
来源：http://dali.fengsongda.top/Article/details/gtzpkpxvuc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtsxenmxnh.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gtxmypptaw.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gttvjmeggj.html

[Q55] 排名（并列占位）
来源：http://dali.jqgufenzy.top/Article/details/gtxrhozrpk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtbbvdflza.html

[Q56] 密集排名（并列不占位）
来源：http://dali.haohaochexian.top/Article/details/gtnsyuemkc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbktltvn.html

[Q57] 行号
来源：http://dali.aibaodan.cn/Article/details/gtwzrpyzyc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtvqqwxbrq.html

[Q58] 累计求和
来源：http://dali.zhongyouzk.top/Article/details/gtvedukiwc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtunavcnip.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtiomypilo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtrrfleykf.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnxiangtu.top/Article/details/gtlyxbuixu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhoulong.xyz/Article/details/gtqeudmeyw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtlavtqlpo.html

[Q61] 移动平均
来源：http://dali.hfpthk.cn/Article/details/gtciusezja.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtgfooqqib.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gtfgdjbrgm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtoacballw.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gtlzhisnik.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gtlmkifgpk.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gtvwpcxolm.html

COMMIT;
来源：http://dali.chenlongwang.top/Article/details/gtyxrcakpc.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gtklbovttu.html

ROLLBACK;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndtayxru.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gtftjlxdvk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.mhx1999.top/Article/details/gtgwdcugvi.html

[Q67] 设置隔离级别
来源：http://dali.svipenyu.cn/Article/details/gtkhjhngtr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sufxvd.cn/Article/details/gtfuxmkksk.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gtnvrfvbqc.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtqpaxnwsj.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gtjsnljoas.html

[Q69] 查看执行计划
来源：http://dali.zhoulong.xyz/Article/details/gtjvykfxbz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfggbcbp.html

[Q70] 更新统计信息
来源：http://dali.snrcjt.cn/Article/details/gtnkaoympx.html

ANALYZE TABLE users;
来源：http://dali.9152youxi.cn/Article/details/gtzppbxnny.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gtvsmzqopu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gaohongyu789.top/Article/details/gttojqnwrh.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gtocjoxrtz.html

SHOW INDEX FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtnkfwizld.html

[Q73] 查看表状态
来源：http://dali.feifeiyinyue.top/Article/details/gtxzxkoebm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gtbwowknis.html

[Q74] 强制使用索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamjcrmuk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gtdtffmpft.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gttixwrvqr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gtbuwoztot.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gtklhfcurp.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gtcblgkeyt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gtzlsgxelg.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gtjtvrgwma.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gtbmefwsrw.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtzxoghtub.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtxoslyedu.html

[Q79] 字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtckbpqmwl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shuidangran.top/Article/details/gtbfngwdwl.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gtgtsuiako.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gtmvfyokpn.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzgqqxoz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ybcxt.top/Article/details/gtfzylcfpf.html

[Q82] 字符长度与字节长度
来源：http://dali.zycfv.cn/Article/details/gtcxkxafyo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtqaqejvtq.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtrbdidnvx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtuhwxreng.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gthddwmdcw.html

SELECT TRIM(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtnuppmohj.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gthgfwtqsz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenjidiqi.icu/Article/details/gthpeuhkio.html

[Q86] 读取 JSON 字段
来源：http://dali.birdmap.top/Article/details/gtagctbbbo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zycfv.cn/Article/details/gtlhkersvp.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gtkwzbracp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.redwolf501.top/Article/details/gtfgxawsth.html

[Q88] 行转列（条件聚合）
来源：http://dali.birdmap.top/Article/details/gtqtnbnnfv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cqqwz.cn/Article/details/gtgegiuexy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.316326.xyz/Article/details/gtmiwqjeaa.html

[Q89] 判断表是否存在
来源：http://dali.fzhhl.top/Article/details/gtshpbaomc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzswcjiu.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gttzyszzyf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hammf.cn/Article/details/gtadmigxoa.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdjsrkes.html

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gtaphiaszi.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtkaelapux.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtzoudwbui.html

#!/usr/bin/env bash
来源：http://dali.redwolf501.top/Article/details/gticdfsenj.html

set -euo pipefail
来源：http://dali.haohaochexian.top/Article/details/gtqotyludh.html

[R02] 变量赋值与使用
来源：http://dali.ppjwa.cn/Article/details/gtwhoffzhq.html

name="Tom"; echo "$name"
来源：http://dali.bjfxy.top/Article/details/gtcivubupu.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gtkzzkcdps.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gtwrejuiiu.html

[R04] 位置参数
来源：http://dali.guowangkeji.top/Article/details/gtzzoryxmn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.birdmap.top/Article/details/gthduyoijq.html

[R05] 参数默认值
来源：http://dali.yongpay.top/Article/details/gtnkktprvo.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gtvbwtvcqo.html

[R06] 判断命令是否存在
来源：http://dali.sysykeji.top/Article/details/gtxzswrtbe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtbngqcbgy.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gtdvuyrnkh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtewfghifv.html

[R08] 数值比较
来源：http://dali.yuanzhike.top/Article/details/gtdvzaoyqt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gtkrtbwjdm.html

[R09] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gtjpozlhvi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gtlvjcnpef.html

[R10] 正则匹配
来源：http://dali.pycfn.com/Article/details/gtxinrqkew.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dashuyun.cn/Article/details/gtjjwratjh.html

[R11] case 多分支
来源：http://dali.shzxlz.cn/Article/details/gtafkkwdtr.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gtyhjcvwov.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gtrtoywjkl.html

stop)  echo "停止" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqayjxat.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gthbnjsyfc.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gtzvvgtvbp.html

[R12] for 遍历文件
来源：http://dali.zdqjudy.top/Article/details/gtoxdtbada.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gtvpbextyb.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gtcpmhsroh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtfrqpxpdg.html

[R14] C 风格 for
来源：http://dali.hysaishi.cn/Article/details/gtzwkhcrvq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtqpxctnlv.html

[R15] while 逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtliajzipl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuxming.cn/Article/details/gtcgggquly.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbynranz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtwizapaxi.html

[R17] 数组定义与取值
来源：http://dali.zhiwuduotai.top/Article/details/gtevtypvdb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guowangkeji.top/Article/details/gtrftobtiv.html

[R18] 遍历数组
来源：http://dali.jqgfzy.top/Article/details/gtuejfvhfs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gtzercnpdt.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtvqlmpjlv.html

echo "${#arr[@]}"
来源：http://dali.svipenyu.cn/Article/details/gtgowixslx.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gtaftfbrkt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gtyvhkvfam.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtlzepalpk.html

echo "${#s}"
来源：http://dali.zhiwuduotai.top/Article/details/gthbnawxyv.html

[R22] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtpbgoewpf.html

echo "${s:0:5}"
来源：http://dali.xziqi.cn/Article/details/gtpnkunsdo.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtfmlgjdxm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.snrcjt.cn/Article/details/gtjrjqjuyq.html

[R24] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtgpbvyzbm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gtsftodnqw.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gtfgiudfsy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfusbfduq.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtyqdohceg.html

now=$(date +%F); echo "$now"
来源：http://dali.xuetiantiany.cn/Article/details/gtxygietcg.html

[R27] 算术展开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwblsoue.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gtpoxnpazs.html

[R28] 浮点运算
来源：http://dali.meibo888.top/Article/details/gtnaxdodvl.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangshuangyany.cn/Article/details/gtoyhjosau.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtezfctslo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gtakvrkbzv.html

[R30] 函数返回状态码
来源：http://dali.ydzc1.top/Article/details/gtlyswgnpk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gtjusgpsdr.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gtimhvzdhk.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gtwaejgolu.html

[R32] 参数个数校验
来源：http://dali.jiagoushi.top/Article/details/gtobfxdfgg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gthwxjftfp.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gtpnzsmqfw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tian-w.cn/Article/details/gtrfylnmuj.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gtguakwtly.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtvdmpkvco.html

[R35] 后台执行并等待
来源：http://dali.ivvv.top/Article/details/gtwxbqntyx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.bjfxy.top/Article/details/gtspfogyyb.html

[R36] 并发执行多个任务
来源：http://dali.gaohongyu789.top/Article/details/gtnjntfhto.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gtxaylkwlc.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gtspriogyf.html

files=$(ls -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttojhhdc.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtpgfgyx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gtleputgfx.html

[R39] 重定向标准输出与错误
来源：http://dali.xinyue.icu/Article/details/gtnnbxvdwf.html

cmd > out.log 2>&1
来源：http://dali.daria6918.cn/Article/details/gtiwuetxga.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gtbggubbai.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gtqvianakq.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gtixglyaqm.html

cmd >/dev/null 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwrmwpjy.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gtdqbtywwy.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gtrstoywfs.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gtprojeomw.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtjjsgjcmo.html

[R44] 按修改时间查找
来源：http://dali.kuanghao11.cn/Article/details/gtrzkegdze.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gtbnsvngoi.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gtwjqhstac.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gtzljzstma.html

[R46] 递归替换文件内容
来源：http://dali.jianghu66.top/Article/details/gtyhutdgym.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.birdmap.top/Article/details/gtrwgcihwt.html

[R47] sed 单行替换
来源：http://dali.316326.xyz/Article/details/gtbfldiojx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtbdikkwcs.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gtkqavjihp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtziaqbmuc.html

[R49] awk 带条件
来源：http://dali.yanxiufei.cn/Article/details/gtdhslvott.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gtftwqfuxv.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtihegbdam.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtrkrnpypg.html

[R51] 排序去重取前几
来源：http://dali.ivvv.top/Article/details/gtywwdidsu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gtowkcqdij.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gtxbbnuvyv.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gtdjyclhou.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gtnxutybdf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zdqjudy.top/Article/details/gtybpunwjj.html

[R54] 比较两个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtkrwqlnva.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gttywpeagn.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gtdkziodhc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fzhhl.top/Article/details/gtyywowjvj.html

[R56] 远程拷贝
来源：http://dali.nanxinkj.top/Article/details/gtulkiotyh.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gtgfawzpzk.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gtegbdumrd.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gtnhpdumks.html

[R58] 下载文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozxzocds.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gtgnjzjgiw.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtowtspgxt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gtvqrqpuxw.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtdoetirah.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gtqcfpfbdu.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gtwhltkhfk.html

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gtwmwbwvye.html

[R62] 找最占空间的文件
来源：http://dali.zdqjudy.top/Article/details/gtktglielc.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gtqhattboy.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszoyudso.html

free -h;  ps aux | grep nginx
来源：http://dali.meibo888.top/Article/details/gthpvhdvuu.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gtffwahcor.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gtewqpsbmk.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gtpenmdntz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdrxtmfc.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gtvgcxkehp.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gtokikhnpr.html

[R67] 生成随机十六进制串
来源：http://dali.redwolf501.top/Article/details/gtxjqfkulr.html

openssl rand -hex 16
来源：http://dali.shuidangran.top/Article/details/gttmssgeye.html

[R68] 计算文件校验值
来源：http://dali.cdnleiting.top/Article/details/gtjxipktck.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gtjtsuetkg.html

[R69] 生成随机密码
来源：http://dali.andypj.xyz/Article/details/gtrufabjfn.html

head -c 16 /dev/urandom | base64
来源：http://dali.yonumen.top/Article/details/gtruyvpdiz.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gthmcexjfg.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gtjknvoenn.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtfaxqvngi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gtawdkncdh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gteegddjep.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqhqmklq.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gthvtnktli.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtosscxcui.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcwmcuub.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tanke756.top/Article/details/gtryfqfmrh.html

[R75] 导出环境变量
来源：http://dali.yongpay.top/Article/details/gtomlqxahp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gthblurlku.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gtociwvzox.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gtkoufwxpk.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gtwapyvmuy.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gtaclhentx.html

[R78] 交互式菜单
来源：http://dali.cqqwz.cn/Article/details/gteeuyeruq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hammf.cn/Article/details/gtzmsfgcvv.html

[R79] 解析命令行选项
来源：http://dali.sxryk.cn/Article/details/gtcfvnqqig.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gtmvyuutrc.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gttuutsnid.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gtmuerpubx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthgcbnuis.html

S. C / C++ 专题
来源：http://dali.daria6918.cn/Article/details/gttkeehlkp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtkhtgebgk.html

[S01] C：Hello World
来源：http://dali.birdmap.top/Article/details/gtccjhgemj.html

#include <stdio.h>
来源：http://dali.meibo888.top/Article/details/gthnbhvukv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gtlqsabwqk.html

[S02] C：变量与格式化输出
来源：http://dali.hammf.cn/Article/details/gtvahnmftf.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gtwmsowiku.html

[S03] C：读入整数
来源：http://dali.yj20258.top/Article/details/gtvhtmlglv.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtogpxelrn.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtarfxurfu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gtcvscnlty.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtlvrypbtz.html


<!-- 参考信息 -->