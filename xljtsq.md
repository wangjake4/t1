代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtsgipbwwo.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gtovtcvhmy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gthsjuzxgs.html

[Q31] 分组后过滤
来源：http://dali.hywenlv.cn/Article/details/gtogkbbhar.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gtuuusjhup.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtmsyodvpm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gthgbfsedt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gtxvnjbfbk.html

[Q33] 多列分组
来源：http://dali.cqqwz.cn/Article/details/gtjaxvwvcz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gtgvpceitt.html

[Q34] 每组取第一条
来源：http://dali.shuidangran.top/Article/details/gthepqinep.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gtspmxkuev.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zycfv.cn/Article/details/gtsxtikngw.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gteplkjwnw.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gtxxpmlrgx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gtwnxkrhyj.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gthpcfbczg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtiqljmsyr.html

[Q37] 右连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbgjcorf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258.top/Article/details/gturzqbioq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yangfankeji.com/Article/details/gtqlfosoja.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.haohaochexian.top/Article/details/gttpkraziw.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gtvtjdattr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pengpengdd.cyou/Article/details/gtnfvglgkx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkfuyhzc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hywenlv.cn/Article/details/gtrzkghikb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenlongwang.top/Article/details/gtguvpmiqj.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gtriozqjle.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gtffemlznj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gtqqkxntsn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fzhhl.top/Article/details/gtrqbovjnd.html

[Q42] 连接条件附加过滤
来源：http://dali.xylfe.cn/Article/details/gthpxwnyic.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xinyue.icu/Article/details/gtpudirfwd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gtjouiaffn.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gtuvgyfiky.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yangfankeji.com/Article/details/gttaehigwb.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gtqfehbyut.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhengqikj.top/Article/details/gtvimttznx.html

[Q45] EXISTS 判断存在
来源：http://dali.tian-w.cn/Article/details/gtjcjyosxg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtnkzmnymn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gtvjttkxfi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gtgebqamjr.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gthctwfnlp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gtwzslghmj.html

[Q48] CTE 公用表表达式
来源：http://dali.bjfxy.top/Article/details/gtnxldhxnz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgfzy.top/Article/details/gtcxyturbf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dianchejie.cn/Article/details/gtvkggovvo.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gtgnyizmip.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtuwzkdvaa.html

[Q50] 批量更新
来源：http://dali.cucudq.cn/Article/details/gtkhspitay.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmtiiqfr.html

[Q51] 用子查询更新
来源：http://dali.tanke756.top/Article/details/gtxedhrcdb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daria6918.cn/Article/details/gtkntotwgh.html

[Q52] 删除指定行
来源：http://dali.redwolf501.top/Article/details/gtubnoseab.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtpoyvmapo.html

[Q53] 按条件删除
来源：http://dali.cdnleiting.top/Article/details/gtnmybizlv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtycpdqgkp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gttbxzaguq.html

TRUNCATE TABLE logs;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnsljkcm.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gtoaldxyqj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gtmwenjhgg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258.top/Article/details/gtxxcfdltc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yonumen.top/Article/details/gtbyskhaft.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gtgbksjuiq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gttizhcpyp.html

[Q58] 累计求和
来源：http://dali.sweek.top/Article/details/gtgctthpgf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gthjhofaqu.html

[Q59] 分组内累计
来源：http://dali.yuxming.cn/Article/details/gttnqhfhzd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtmagpmpzr.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gtossdbpsn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhiwuduotai.top/Article/details/gtzvkfmwoi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtjtcyxbhj.html

[Q61] 移动平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvcdmnvf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtnvasyohw.html

[Q62] 分组占比
来源：http://dali.sxryk.cn/Article/details/gtvyerssqq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtwbihqlgm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gtorcohhfw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gttrtovert.html

[Q64] 提交事务
来源：http://dali.0kj1m.cn/Article/details/gtqtroozpv.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gtxmariqfy.html

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchgbdjnf.html

ROLLBACK;
来源：http://dali.zhongyouzk.top/Article/details/gtnxfeaqtu.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gtsaveltwr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gtwcfjgnin.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gtkuhmpujn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gthliccpfw.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gttbtkyjre.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gtumpkcsyt.html

ROLLBACK TO sp1;
来源：http://dali.316326.xyz/Article/details/gtnmhpcszd.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gtzdwymtxu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gtigyrpcxl.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gtskbltgsq.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyihvfxcs.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gtmoiscphu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gzhubu.top/Article/details/gtkhxuqqfi.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gttiwlgmqq.html

SHOW INDEX FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtvebmlqhc.html

[Q73] 查看表状态
来源：http://dali.shzxlz.cn/Article/details/gtxmjghrsj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hysaishi.cn/Article/details/gtsekuzhkv.html

[Q74] 强制使用索引
来源：http://dali.nanxuanxn.top/Article/details/gtxhzusjso.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gtecthdpdw.html

[Q75] 日期格式化
来源：http://dali.yonumen.top/Article/details/gtkflrhlwz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtylrxowwd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guannengcc.top/Article/details/gtnstuggdl.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gthkzsyvqi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gtpxzoaohk.html

[Q77] 时间加减
来源：http://dali.shzxlz.cn/Article/details/gtbfnwlpvj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenlongwang.top/Article/details/gtjmkqikia.html

[Q78] 当前时间
来源：http://dali.tian-w.cn/Article/details/gtaeisqfqa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gttojybohb.html

[Q79] 字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtwjwwgpkq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvtrhmsd.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gtybsraqsw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtzcfbpqth.html

[Q81] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gtqefmqqwg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guannengcc.top/Article/details/gtdveejdpc.html

[Q82] 字符长度与字节长度
来源：http://dali.meibo888.top/Article/details/gtfwclpjqm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtdyaxjiwv.html

[Q83] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtlmohewxf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtcgeokokb.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gtozezkwsa.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtowllxllh.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gtcugumvij.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxinkj.top/Article/details/gtlczwnwtz.html

[Q86] 读取 JSON 字段
来源：http://dali.shzxlz.cn/Article/details/gtlfnwukij.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sxryk.cn/Article/details/gtnidydtdg.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gtxtwcozlt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gtgnbvouba.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gtvunwhfwh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gtgaesnjal.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtlnojjthr.html

[Q89] 判断表是否存在
来源：http://dali.zdqjudy.top/Article/details/gtfxjfjqym.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrjtjixm.html

[Q90] 生成序号列
来源：http://dali.vqdsnc.cn/Article/details/gtakktuwbq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyejmrsfz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtyefjpwei.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gtwhdrlhmm.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtpaunsmpb.html

[R01] shebang 与严格模式
来源：http://dali.c1oappe.top/Article/details/gtsxsghvcz.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gtpzinmryj.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gtqlbvnkaw.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangtech.top/Article/details/gtkngakswg.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gthcgzczjh.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gtdhrwmgvx.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gtuuosdick.html

[R04] 位置参数
来源：http://dali.316326.xyz/Article/details/gtjxabttwx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gtrlmntuom.html

[R05] 参数默认值
来源：http://dali.tanke756.top/Article/details/gthfcmgatn.html

name="${1:-default}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtnezfwdjt.html

[R06] 判断命令是否存在
来源：http://dali.sysykeji.top/Article/details/gtwnmpagvb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtajthqvzv.html

[R07] if 判断文件
来源：http://dali.tianlin.xyz/Article/details/gtuogprajf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.iojbl.cn/Article/details/gtgykhvmpg.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtjxlqeogh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gtmuvtiwjd.html

[R09] 字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtowvdqmoz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxpihnvl.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gtqiwoqkde.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtofbvfzgi.html

[R11] case 多分支
来源：http://dali.cqqwz.cn/Article/details/gtatrpnqlq.html

case "$1" in
来源：http://dali.yongpay.top/Article/details/gtlquotgfi.html

start) echo "启动" ;;
来源：http://dali.tianlin.xyz/Article/details/gtssxvkrbn.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtusgavnnk.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gtwbyjvofb.html

esac
来源：http://dali.chenlongwang.top/Article/details/gtnzqotzux.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gtndoevsnr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhongyouzk.top/Article/details/gtbrfbhagl.html

[R13] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gtgcdpdkni.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gtnbgqgutq.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gtzagcatic.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtaelenflj.html

[R15] while 逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtrrplffhd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jianghu66.top/Article/details/gtvmqfufjc.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gtvmfcpgfm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtkphivxei.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gthbtuzomk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gtxpnhhspm.html

[R18] 遍历数组
来源：http://dali.yueranfly.top/Article/details/gtsqvoetoy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xziqi.cn/Article/details/gtgzunrdoo.html

[R19] 数组长度
来源：http://dali.316326.xyz/Article/details/gttnzdmtcw.html

echo "${#arr[@]}"
来源：http://dali.nanxuanxn.top/Article/details/gtmgwqezms.html

[R20] 关联数组（字典）
来源：http://dali.kuanghao11.cn/Article/details/gtzcfwpgsg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nwbrower.top/Article/details/gtmkgcyefh.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gtlexqjhft.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gtzluquhxo.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtyyrxnbzb.html

echo "${s:0:5}"
来源：http://dali.chenzaomai.com/Article/details/gtzbjthoqz.html

[R23] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtqzekpfmt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gthheagehz.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtpyiaabpl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtqnoykeoe.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gtberfvxoy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gtnaugmafc.html

[R26] 命令替换
来源：http://dali.0kj1m.cn/Article/details/gtysgncmbj.html

now=$(date +%F); echo "$now"
来源：http://dali.dianchejie.cn/Article/details/gtokbfgyzm.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gtlpboflmo.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtguxgiywu.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gtlzjcnybb.html

echo "scale=2; 10/3" | bc
来源：http://dali.pengpengdd.cyou/Article/details/gtjfufnlam.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtoouxwvzs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gtkjiblpqd.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gtxtdwrjpk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamrvnjti.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gtsxytrpkh.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gtkvpaytix.html

[R32] 参数个数校验
来源：http://dali.ydzc1.top/Article/details/gtmgozpbpv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtxcxrgzus.html

[R33] 捕获错误并提示行号
来源：http://dali.daria6918.cn/Article/details/gtanrxnzmn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.c1oappe.top/Article/details/gtloezsefd.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gtsygixoye.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtevwdumlq.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gtrtsdnsto.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nwbrower.top/Article/details/gttddtkuwa.html

[R36] 并发执行多个任务
来源：http://dali.yongpay.top/Article/details/gthcspplkg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtgfiaofzp.html

[R37] 把输出赋给变量
来源：http://dali.birdmap.top/Article/details/gtutdoeeol.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gttwvmdmqf.html

[R38] 管道串联
来源：http://dali.yuxming.cn/Article/details/gtmleulsyi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxvdecis.html

[R39] 重定向标准输出与错误
来源：http://dali.kuanghao11.cn/Article/details/gtrddyqmmx.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtgrdzndhn.html

[R40] 追加写日志
来源：http://dali.ehwqpu.com/Article/details/gtvxxwesqg.html

echo "log" >> out.log
来源：http://dali.nwbrower.top/Article/details/gtbdfqbzss.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gtslgvhhuv.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gteojvzxlk.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gtphuebbaj.html

wc -l < a.txt
来源：http://dali.fengsongda.top/Article/details/gtfnqhztmw.html

[R43] 按名字查找文件
来源：http://dali.ehwqpu.com/Article/details/gtxosgucvz.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gtjxyrairf.html

[R44] 按修改时间查找
来源：http://dali.kuanghao11.cn/Article/details/gttyfiiltm.html

find . -mtime -7 -type f
来源：http://dali.jiagoushi.top/Article/details/gtseblzzgh.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gtmyuedqoz.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gtrfpwiseo.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gtlfrlkdxu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhixingplan.top/Article/details/gtbjgvinmw.html

[R47] sed 单行替换
来源：http://dali.tanke756.top/Article/details/gtevtnzqir.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtwjgejaro.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gtmifowhkr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtvifweibz.html

[R49] awk 带条件
来源：http://dali.xziqi.cn/Article/details/gtrrwfchbe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xylfe.cn/Article/details/gttnpgtunf.html

[R50] awk 求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhurixhh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtwbzhqrdx.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudbzumbx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gtpxujlaax.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gtcyounxnc.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gtdwyehthf.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gtazdfwlke.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gtfuawyhbq.html

[R54] 比较两个文件
来源：http://dali.zdqjudy.top/Article/details/gtccmwiyud.html

diff a.txt b.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtzpozsxjc.html

[R55] 压缩与解压
来源：http://dali.kuanghao11.cn/Article/details/gtexpmhjlu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.meibo888.top/Article/details/gtskihqnsd.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtzeduutlg.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtncifxwts.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gtbbokhegi.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gtqriptqle.html

[R58] 下载文件
来源：http://dali.yvedp.cn/Article/details/gtjchduofd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ppjwa.cn/Article/details/gtfhxeafvs.html

[R59] 发 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtepxvikty.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gtrhynrexw.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtcfzqgfxx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenjidiqi.icu/Article/details/gtjqzyslrj.html

[R61] 磁盘占用
来源：http://dali.chenzaomai.com/Article/details/gthjkhafqc.html

df -h;  du -sh *
来源：http://dali.bjfxy.top/Article/details/gtpqvyqgor.html

[R62] 找最占空间的文件
来源：http://dali.xziqi.cn/Article/details/gtqwvzxncd.html

du -ah . | sort -rh | head -10
来源：http://dali.cqqwz.cn/Article/details/gtsturnpzd.html

[R63] 内存与进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaypduok.html

free -h;  ps aux | grep nginx
来源：http://dali.xinyue.icu/Article/details/gthnlrlrsw.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gtneipxyvi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guowangkeji.top/Article/details/gtpzkjmwee.html

[R65] 查看端口占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcjosugr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.vqdsnc.cn/Article/details/gtcgdnohjy.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gtdvnhjcuy.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gtucvmkdyf.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gtbqljixrr.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gtkdufbdyx.html

[R68] 计算文件校验值
来源：http://dali.jqgufenzy.top/Article/details/gtxzolluvr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.0kj1m.cn/Article/details/gtzebefanu.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gtrubgrwbo.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gttefaveey.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gtccoqskpe.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gtnrflcdij.html

[R71] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gtmlbjtvoy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gtpazpxpzv.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gtlseloief.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtszspthra.html

[R73] 分割大日志
来源：http://dali.jinqigfzy.top/Article/details/gtuhplquby.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdekdxfy.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gtymsapfru.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gtmzxfzsyp.html

[R75] 导出环境变量
来源：http://dali.0kj1m.cn/Article/details/gteeogqvms.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gtlpygclkt.html

[R76] 使用临时文件
来源：http://dali.hongshengwenyu.top/Article/details/gtsllorgbd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtrndvqvwd.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gtwdsbouxl.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gtzwmuxtub.html

[R78] 交互式菜单
来源：http://dali.chenlongwang.top/Article/details/gttugeyrod.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gtcvcjvwmk.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gtddcqxekb.html


<!-- 参考信息 -->