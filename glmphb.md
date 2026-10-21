代发 wailian999

[Q33] 多列分组
来源：http://dali.hnqzz.top/Article/details/gteyxsqwrq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gtnvtgbfgg.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gtbtlvhxjg.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gtlnvvrwvo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.vqdsnc.cn/Article/details/gtgnaciouf.html

) t WHERE rn = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavqnnhij.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gttnfsolit.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtyvwtntbk.html

[Q36] 左连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbhrtyew.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtgkyrwrmo.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gtzpryqyyi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gtjotbfxvy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hongshengwenyu.top/Article/details/gtoyosgxqk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gaohongyu789.top/Article/details/gtwxnszvgz.html

[Q39] 自连接（查上下级）
来源：http://dali.ydzc1.top/Article/details/gtkldjsvni.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.vqdsnc.cn/Article/details/gtyfbiknnx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gtnmsmtohh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zycfv.cn/Article/details/gtjaomxxzy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwcaxnck.html

[Q41] 多表连接
来源：http://dali.jiagoushi.top/Article/details/gtavvsnhui.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gtyacrxqka.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlnnknzo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gtavszvtjo.html

[Q42] 连接条件附加过滤
来源：http://dali.cucudq.cn/Article/details/gtuiqykxma.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gtytfhewyr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tianlin.xyz/Article/details/gtqolaoqiz.html

[Q43] 标量子查询
来源：http://dali.yj202588.top/Article/details/gtfbxtajhc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gthvbpxwpy.html

[Q44] IN 子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhcczmgb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zycfv.cn/Article/details/gtbenmhhjv.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gtpofynrdx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtpwkieutu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuanzx.com/Article/details/gtzgiazirp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtqfatpeod.html

[Q47] 与平均值比较
来源：http://dali.gotoacloud.top/Article/details/gtfmpagbsu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.andypj.xyz/Article/details/gtteanwfli.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtoakjxmby.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gtomdjrduq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gtxnmlaywt.html

[Q49] 更新单行
来源：http://dali.mhx1999.top/Article/details/gtofmmdtjm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtkseeixkf.html

[Q50] 批量更新
来源：http://dali.nanxinkj.top/Article/details/gtxvnhvhgg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.svipenyu.cn/Article/details/gtwpswfuvu.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gtkqgiuazo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gtxlcgtkis.html

[Q52] 删除指定行
来源：http://dali.sweek.top/Article/details/gtlhjrrysp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtshgeteah.html

[Q53] 按条件删除
来源：http://dali.fengsongda.top/Article/details/gtwcrarqfd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.andypj.xyz/Article/details/gttfzzxzms.html

[Q54] 清空表
来源：http://dali.jinqigufen.top/Article/details/gtymjxdoiy.html

TRUNCATE TABLE logs;
来源：http://dali.zhengqikj.top/Article/details/gtbhgzlrhn.html

[Q55] 排名（并列占位）
来源：http://dali.haohaochexian.top/Article/details/gtpgxiqotm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtgsxbjtuw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gtqkwqjrzv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtspdvhtua.html

[Q57] 行号
来源：http://dali.cashguo.top/Article/details/gtvvunhxmz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.meibo888.top/Article/details/gtxhwhgadh.html

[Q58] 累计求和
来源：http://dali.xylfe.cn/Article/details/gtqzvinzkv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtbztmfzvf.html

[Q59] 分组内累计
来源：http://dali.yuxming.cn/Article/details/gtksbsapti.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtiswrzudl.html

[Q60] 取上一行 / 下一行
来源：http://dali.pycfn.com/Article/details/gtcovxjknf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tanke756.top/Article/details/gtincmdsnt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtfzsrwcga.html

[Q61] 移动平均
来源：http://dali.aibaodan.cn/Article/details/gtrjsidpdq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtcgkmrika.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gtdgymhkju.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtrzfliomp.html

[Q63] 开启事务
来源：http://dali.yonumen.top/Article/details/gtdffjxowc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gtfhnemwso.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrqpndut.html

COMMIT;
来源：http://dali.guannengcc.top/Article/details/gtqsavlnjm.html

[Q65] 回滚事务
来源：http://dali.hnxiangtu.top/Article/details/gtzueehkvq.html

ROLLBACK;
来源：http://dali.xziqi.cn/Article/details/gtezsaosbh.html

[Q66] 行锁查询
来源：http://dali.dashuyun.cn/Article/details/gtjlyctbfs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gtasscszdj.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gtivtykubw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhoulong.xyz/Article/details/gtuqppbghj.html

[Q68] 保存点
来源：http://dali.ydzc1.top/Article/details/gtrtesleni.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gtjqnteqlg.html

ROLLBACK TO sp1;
来源：http://dali.fzhhl.top/Article/details/gtbiijnoek.html

[Q69] 查看执行计划
来源：http://dali.pycfn.com/Article/details/gtgtshehhv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gtjeifqlww.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gtfnvmxmei.html

ANALYZE TABLE users;
来源：http://dali.wangshuangyany.cn/Article/details/gtwkqbcfrb.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gtyhchjamg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gtoovfrrzj.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gthyqqqzyf.html

SHOW INDEX FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtgsssvufl.html

[Q73] 查看表状态
来源：http://dali.fzhhl.top/Article/details/gtucudyrui.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hfpthk.cn/Article/details/gtgpglzruw.html

[Q74] 强制使用索引
来源：http://dali.cqqwz.cn/Article/details/gtdidswrih.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gtusgzglar.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtmhetkwbr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajuhgzer.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuanzhike.top/Article/details/gtsabrhpxl.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gtkmyzrlfz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtettsagfs.html

[Q77] 时间加减
来源：http://dali.hywenlv.cn/Article/details/gtbwrzdehy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinghuilouyu.cn/Article/details/gtntvsiskd.html

[Q78] 当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtmrinzbbo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhoulong.xyz/Article/details/gtmtwasshe.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtpcfuvtel.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gtayqtmiqr.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtunvdwlrn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gtkskkqmmz.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtmwdqfxbu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.316326.xyz/Article/details/gtiuxdcsuf.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gtigmrmkgg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtozxzhfnu.html

[Q83] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtjqkkyizp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtqccuxmur.html

[Q84] 去除首尾空格
来源：http://dali.jqgufenzy.top/Article/details/gtqyqghkxb.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtdcyamuej.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gtzevuqsds.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.birdmap.top/Article/details/gtijhtafbr.html

[Q86] 读取 JSON 字段
来源：http://dali.shzxlz.cn/Article/details/gttgfgbwpj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gogol.net.cn/Article/details/gtvtoistpi.html

[Q87] JSON 字段做条件
来源：http://dali.dianchejie.cn/Article/details/gtccashigi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yangfankeji.com/Article/details/gtnawlkbeg.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxygtlmi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ybcxt.top/Article/details/gtmdooddak.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtawwdnjlw.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gtheryimbg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gtznrokurm.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gtzkawmwir.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.smart0.xyz/Article/details/gtmxuoepyu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttmjwcdir.html

R. Bash 专题
来源：http://dali.nanxinkj.top/Article/details/gtzczhvrrm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxvldtvnl.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gtixixlrof.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gtdrqxuktl.html

set -euo pipefail
来源：http://dali.zycfv.cn/Article/details/gtewwiuqnw.html

[R02] 变量赋值与使用
来源：http://dali.jlsjyb.cn/Article/details/gtlsrselsn.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gtmgrazeyx.html

[R03] 只读变量
来源：http://dali.zhiwuduotai.top/Article/details/gtltfwuhdm.html

readonly PI=3.14
来源：http://dali.chenzaomai.com/Article/details/gtbdvugcye.html

[R04] 位置参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnakaouio.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gtcafoimlk.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gtjqlhivsf.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gtwtrodhat.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gtmkfallgp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gtukczngek.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gtxwpebndh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtxbxtjvrq.html

[R08] 数值比较
来源：http://dali.zdqjudy.top/Article/details/gtrdyojwvg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtdvszepuw.html

[R09] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gthpeetnnl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtqlpyxmle.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gtvqqnafxb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hysaishi.cn/Article/details/gtmiuzawan.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gtsealdsaz.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvbpnezu.html

start) echo "启动" ;;
来源：http://dali.jiagoushi.top/Article/details/gttldftbfp.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gtrendsmvo.html

*)     echo "未知命令" ;;
来源：http://dali.9152youxi.cn/Article/details/gtxzribvkw.html

esac
来源：http://dali.dianchejie.cn/Article/details/gtyltuaosg.html

[R12] for 遍历文件
来源：http://dali.snrcjt.cn/Article/details/gtbdecnuve.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yonumen.top/Article/details/gtuaxkojas.html

[R13] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gtecenywxv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtkpmffxpc.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gtgnyszgtp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gtyeqkxxvj.html

[R15] while 逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfvrrwci.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuanzhike.top/Article/details/gtejcmjftp.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gtofcdrvcb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gthxalwqts.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gtglrsgmkr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.kuanghao11.cn/Article/details/gtgmajbkgq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gtorayncya.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gtmjlxcwad.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtxnxghzxo.html

echo "${#arr[@]}"
来源：http://dali.zhixingplan.top/Article/details/gtddcxsocm.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gtaijqpmce.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gtcsjqjvvw.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgufkunli.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gtoooapyjw.html

[R22] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gtlprlgovw.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gtejblyurj.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gteustfwgc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cqqwz.cn/Article/details/gtnzyacwtu.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtpnmrcfgx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yonumen.top/Article/details/gtbtbvccty.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhengqikj.top/Article/details/gtsdskyjzm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgfzy.top/Article/details/gtbhqhvoox.html

[R26] 命令替换
来源：http://dali.svipenyu.cn/Article/details/gtqsnwngfs.html

now=$(date +%F); echo "$now"
来源：http://dali.xziqi.cn/Article/details/gtcodafmdq.html

[R27] 算术展开
来源：http://dali.mhx1999.top/Article/details/gtzbdsrkuc.html

echo $((1 + 2 * 3))
来源：http://dali.316326.xyz/Article/details/gtfzpororf.html

[R28] 浮点运算
来源：http://dali.havefunace.top/Article/details/gtifpfqsff.html

echo "scale=2; 10/3" | bc
来源：http://dali.shangyingyoupin.top/Article/details/gtdsvsbnia.html

[R29] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtfdfladxm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.snrcjt.cn/Article/details/gtsfjtcijq.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gticxkplrs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhixingplan.top/Article/details/gtzqdabnoi.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtuzvbvuzd.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gtspzymuqv.html

[R32] 参数个数校验
来源：http://dali.zhoulong.xyz/Article/details/gtmxulzcti.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gtvirdyomk.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gtydwqbdpl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gtcwgbowev.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gteihxysty.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtlqhctnho.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gtciqukvmz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzhqclbs.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gtqgpiyson.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhixingplan.top/Article/details/gtbiuiiipb.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gtaqltqgqg.html

files=$(ls -1)
来源：http://dali.guannengcc.top/Article/details/gtuwwphdex.html

[R38] 管道串联
来源：http://dali.sxryk.cn/Article/details/gtnlqzzihc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gtshsdjvfz.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gtgxuxqmed.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gtscwznzhy.html

[R40] 追加写日志
来源：http://dali.yj20258.top/Article/details/gtisifwajt.html

echo "log" >> out.log
来源：http://dali.zdqjudy.top/Article/details/gtxgmxumpb.html

[R41] 丢弃输出
来源：http://dali.yj202588.top/Article/details/gtkndoxudl.html

cmd >/dev/null 2>&1
来源：http://dali.daria6918.cn/Article/details/gtrobnywqm.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gtrbiuqpia.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtyxbzvgag.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gtwbarxexo.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gtjeorjuaa.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gtamodojyu.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gtknkvdrge.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gtwyuzbwug.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gtptonuzzf.html

[R46] 递归替换文件内容
来源：http://dali.jianghu66.top/Article/details/gtktqrsiva.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hongshengwenyu.top/Article/details/gtxbzsxhvb.html

[R47] sed 单行替换
来源：http://dali.guowangkeji.top/Article/details/gtacosvzvq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnskqwwkp.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gtphozdgjs.html

awk '{print $1, $3}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtudrzllyl.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtmpnbhznc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gtugbrliij.html

[R50] awk 求和
来源：http://dali.cucudq.cn/Article/details/gtykoqssly.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yonumen.top/Article/details/gtxiklxhhp.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gtluwkprgl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gtzajtolqp.html

[R52] 统计行数
来源：http://dali.xuanzx.com/Article/details/gtqkogewkp.html

wc -l a.txt
来源：http://dali.xylfe.cn/Article/details/gtfwycdups.html

[R53] 查看文件头与实时尾
来源：http://dali.andypj.xyz/Article/details/gtzynybfpr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xziqi.cn/Article/details/gtlvexulil.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gtvdtbcngv.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gtpucqrxck.html

[R55] 压缩与解压
来源：http://dali.yonumen.top/Article/details/gtusvliiwl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gtonygkbuv.html

[R56] 远程拷贝
来源：http://dali.xinyue.icu/Article/details/gturakjfwo.html

scp file user@host:/path/
来源：http://dali.jqgfzy.top/Article/details/gtmbkwhyut.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gtusojmhnz.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gtvrtzscke.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gtaiswuswu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zdqjudy.top/Article/details/gtvckvysme.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtjfblfmya.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jyoumei.cn/Article/details/gtuzovdymg.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtyzvzwvwh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yvedp.cn/Article/details/gtgrfppwbx.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtboscfldd.html

df -h;  du -sh *
来源：http://dali.mhx1999.top/Article/details/gtiikkjrct.html

[R62] 找最占空间的文件
来源：http://dali.chenlongwang.top/Article/details/gtpctwurpk.html

du -ah . | sort -rh | head -10
来源：http://dali.havefunace.top/Article/details/gthyadwrli.html

[R63] 内存与进程
来源：http://dali.gotoacloud.top/Article/details/gtjahoyhsm.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gterbzbwqc.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gtbadcxbhs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gtelumyjwo.html

[R65] 查看端口占用
来源：http://dali.tian-w.cn/Article/details/gtdoiqgjtl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gtdngmutne.html

[R66] 定时任务
来源：http://dali.dianchejie.cn/Article/details/gtclrhuihi.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gtcbrssmkz.html

[R67] 生成随机十六进制串
来源：http://dali.sxryk.cn/Article/details/gtplwpqois.html

openssl rand -hex 16
来源：http://dali.fengsongda.top/Article/details/gtnmiwqzea.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gtwmmjcmkz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtpperfvga.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gtidzrvcyc.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gtayqqjxgi.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gthzpcsnkr.html

date +%s;  date -d @1700000000
来源：http://dali.quarkkingdee.top/Article/details/gtmovtacdl.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtgnkwbpbq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tanke756.top/Article/details/gtkrtmgdck.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gthwkmumgq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtfkoycmtn.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gtlsxybvuf.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gtavanhbfd.html

[R74] 批量重命名
来源：http://dali.gotoacloud.top/Article/details/gtysqyiavd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.smart0.xyz/Article/details/gtktduiusk.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gtczzgntps.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gtxhuxafke.html

[R76] 使用临时文件
来源：http://dali.chenlongwang.top/Article/details/gtllyqibzq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gthcdressx.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gtjfgpjtbc.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gtfrcvftlk.html

[R78] 交互式菜单
来源：http://dali.daxiang520.top/Article/details/gtofqcvxcw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fengsongda.top/Article/details/gtnxgfddxn.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdayzmyh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gtdkpnorui.html

[R80] 查看脚本执行耗时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshghiwfd.html

time ./run.sh
来源：http://dali.yj20258888.top/Article/details/gtkhpbwotg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmtsqyxek.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gtsndkrqva.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtckavdbmh.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gthenydvtu.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gtstlrbohm.html


<!-- 参考信息 -->