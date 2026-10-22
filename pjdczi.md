代发 wailian999

[Q36] 左连接
来源：http://dali.gzhubu.top/Article/details/gt2vpduolwa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gt2tkcgcnwa.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdqsuqna.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jyoumei.cn/Article/details/gt2uaqpyamn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gt2hyxkjwkf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shzxlz.cn/Article/details/gt2ijnlzvyo.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gt2kenkwbfb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigfzy.top/Article/details/gt2dxjgbhav.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tian-w.cn/Article/details/gt2iirpzvmr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ydzc1.top/Article/details/gt2qskxitqb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnqzz.top/Article/details/gt2ahqeyyud.html

[Q41] 多表连接
来源：http://dali.tianlin.xyz/Article/details/gt2mqmpssjc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gt2cjwgsivo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmjrlixd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2qvjohvin.html

[Q42] 连接条件附加过滤
来源：http://dali.hammf.cn/Article/details/gt2nxzgfmze.html

SELECT u.name, o.amount FROM users u
来源：http://dali.quarkkingdee.top/Article/details/gt2kzflganf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gt2nlnyqthi.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gt2jjlimkie.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhengqikj.top/Article/details/gt2enbrggxd.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gt2lgtnhhjb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuanzx.com/Article/details/gt2wtyefjtl.html

[Q45] EXISTS 判断存在
来源：http://dali.jyoumei.cn/Article/details/gt2ojfddkxj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gt2srtjlidj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hammf.cn/Article/details/gt2vyjdusez.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gt2vgtqhzko.html

[Q47] 与平均值比较
来源：http://dali.tanke756.top/Article/details/gt2axsfzrfl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jyoumei.cn/Article/details/gt2ipkmhfnm.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2pllytuqi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenlongwang.top/Article/details/gt2vqdbgdao.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xisryney.html

[Q49] 更新单行
来源：http://dali.hnqzz.top/Article/details/gt2eiwfvqdx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gt2lxbcaflu.html

[Q50] 批量更新
来源：http://dali.quarkkingdee.top/Article/details/gt2agqlizin.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shzxlz.cn/Article/details/gt2hiaacbzf.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gt2vmtbwehn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omsqjhxw.html

[Q52] 删除指定行
来源：http://dali.redwolf501.top/Article/details/gt2wyotztxd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2qhzzaejm.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gt2afwdoelz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmglwlr.html

[Q54] 清空表
来源：http://dali.pengpengdd.cyou/Article/details/gt2ookfbhkv.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gt2bqlsiloe.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gt2erorpkwj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gt2hrarewhp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qyfbjpax.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gt2abxnbskf.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gt2rzaqjspo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2avszvjpb.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnsdhprt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2ligrnfgs.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lorgrvpd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2yugevafy.html

[Q60] 取上一行 / 下一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eoqqvtoo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.316326.xyz/Article/details/gt2blwmfkdr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2rxhigged.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gt2unikcouc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2kkuklbvl.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gt2ufyoarat.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yscejept.html

[Q63] 开启事务
来源：http://dali.yuanzhike.top/Article/details/gt2ssyiplzh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gt2dmihwpqb.html

[Q64] 提交事务
来源：http://dali.xziqi.cn/Article/details/gt2ekrydflz.html

COMMIT;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmjmsfpk.html

[Q65] 回滚事务
来源：http://dali.hnxiangtu.top/Article/details/gt2ieyzkfys.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gt2dntgeaxg.html

[Q66] 行锁查询
来源：http://dali.jianghu66.top/Article/details/gt2qizxjpas.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgpmkcag.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjspdkdp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.andypj.xyz/Article/details/gt2blesjoxy.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gt2xktapisw.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gt2jqylaobv.html

ROLLBACK TO sp1;
来源：http://dali.guowangkeji.top/Article/details/gt2axpglien.html

[Q69] 查看执行计划
来源：http://dali.xuetiantiany.cn/Article/details/gt2nubwdmxa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gt2fzgfrtsj.html

[Q70] 更新统计信息
来源：http://dali.yuxming.cn/Article/details/gt2uteqrpjv.html

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gt2mmyfcskl.html

[Q71] 查看建表语句
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjbianwy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sysykeji.top/Article/details/gt2xgqpilyf.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gt2lgtgwfys.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2jbmlofue.html

[Q73] 查看表状态
来源：http://dali.hongshengwenyu.top/Article/details/gt2osumntgf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gt2ausqcwpr.html

[Q74] 强制使用索引
来源：http://dali.jinqigfzy.top/Article/details/gt2nbketgbh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pengpengdd.cyou/Article/details/gt2mezttzpg.html

[Q75] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gt2hhssdamj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2ugrixohi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cashguo.top/Article/details/gt2bdyqcqtp.html

[Q76] 按天统计
来源：http://dali.xziqi.cn/Article/details/gt2yqtjihws.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gt2nozvrtyo.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gt2rklomzwa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwirkbzs.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2jzbmlxgk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhrvqzqr.html

[Q79] 字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gt2irkhwtzf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.mhx1999.top/Article/details/gt2qdcriniv.html

[Q80] 字符串截取
来源：http://dali.316326.xyz/Article/details/gt2xrsydrht.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2qpliaqdc.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gt2lvfbrpnr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2zkligcag.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2msqilccr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2yuciulbl.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gt2bjsmqubx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2eosvgrze.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gt2ebwqvyts.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2wxowwjnv.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rcoeyhfe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhengqikj.top/Article/details/gt2ngkkowhm.html

[Q86] 读取 JSON 字段
来源：http://dali.xuanzx.com/Article/details/gt2enmpyqst.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gt2hkdadxwn.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lneycigb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gt2bpyyjoqu.html

[Q88] 行转列（条件聚合）
来源：http://dali.yanxiufei.cn/Article/details/gt2yhxwfxgv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gt2lkxumdbz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gt2hhetsjfx.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2anqcmicc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pycfn.com/Article/details/gt2bisscjqr.html

[Q90] 生成序号列
来源：http://dali.haohaochexian.top/Article/details/gt2vbwldnuk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.birdmap.top/Article/details/gt2othmufje.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2vtslqqjy.html

R. Bash 专题
来源：http://dali.nanxinkj.top/Article/details/gt2qzuqfsoh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2uenejmty.html

[R01] shebang 与严格模式
来源：http://dali.hfpthk.cn/Article/details/gt2usphfrkt.html

#!/usr/bin/env bash
来源：http://dali.chenlongwang.top/Article/details/gt2hyvceeuj.html

set -euo pipefail
来源：http://dali.c1oappe.top/Article/details/gt2gtfhnyxh.html

[R02] 变量赋值与使用
来源：http://dali.yj202588.top/Article/details/gt2rrhqvuwo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kotyeyjr.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsdgfyjs.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gt2mwzvxmnh.html

[R04] 位置参数
来源：http://dali.yongpay.top/Article/details/gt2ogtibuht.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uupmsuyj.html

[R05] 参数默认值
来源：http://dali.yongpay.top/Article/details/gt2zkzginko.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gt2aqrbtvvr.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gt2euwasccx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gt2wrnmwhgk.html

[R07] if 判断文件
来源：http://dali.chenlongwang.top/Article/details/gt2qsihlmmj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2zbuymkqc.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gt2ykgezplf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.havefunace.top/Article/details/gt2aizjvalc.html

[R09] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2gawsvckr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2yoxbuzzh.html

[R10] 正则匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2qsuvejbj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gt2ubgcvhqa.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gt2ctkxhrsq.html

case "$1" in
来源：http://dali.fengsongda.top/Article/details/gt2jcdjjrgv.html

start) echo "启动" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2hmjxtrrp.html

stop)  echo "停止" ;;
来源：http://dali.zhongyouzk.top/Article/details/gt2pnawaoyc.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258888.top/Article/details/gt2hqxiumgn.html

esac
来源：http://dali.chenzaomai.com/Article/details/gt2pbhcfdmh.html

[R12] for 遍历文件
来源：http://dali.snrcjt.cn/Article/details/gt2bqzpvksr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yueranfly.top/Article/details/gt2ommmrxrw.html

[R13] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kortbxcu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gt2qqegeobr.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gt2wpztluzx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gt2jshffpef.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2kpaxqexl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pycfn.com/Article/details/gt2xubcfxpq.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gt2qhoovkil.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gt2shzeowtk.html

[R17] 数组定义与取值
来源：http://dali.mhx1999.top/Article/details/gt2mjylpria.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjrgdbut.html

[R18] 遍历数组
来源：http://dali.yueranfly.top/Article/details/gt2ewhlzfty.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gt2pwsdgpjj.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gt2cgdzwqzk.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2usjmkmpz.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gt2rqsrbygn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2quevrfcf.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gt2ynkmwkjg.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gt2orsgzduo.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gt2cgpeeusl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfrmxla.html

[R23] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gt2fqvuovbo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhoulong.xyz/Article/details/gt2tjtbujxe.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gt2thzjeelj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gt2elfqxekp.html

[R25] 去后缀 / 去前缀
来源：http://dali.havefunace.top/Article/details/gt2jiqykaon.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2zqnihhre.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gt2qtovskhv.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gt2lxvwcyxj.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gt2tytkomha.html

echo $((1 + 2 * 3))
来源：http://dali.hfpthk.cn/Article/details/gt2mbtruonn.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gt2xvqzqqxk.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gt2veuyjikq.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gt2cpoxwigv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gt2upndhixf.html

[R30] 函数返回状态码
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnyxudec.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258888.top/Article/details/gt2svutfbbb.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gt2vvtvainv.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gt2hqnelisr.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gt2fwxvncyc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gt2gcacufez.html

[R33] 捕获错误并提示行号
来源：http://dali.gotoacloud.top/Article/details/gt2vhicqgxu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.birdmap.top/Article/details/gt2wrvoldgg.html

[R34] 退出时清理
来源：http://dali.fzhhl.top/Article/details/gt2puukgnrp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gt2xecochuu.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gt2rgzdrxhz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gt2qoewiapz.html

[R36] 并发执行多个任务
来源：http://dali.dashuyun.cn/Article/details/gt2pzeqplca.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gt2jnotrriv.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gt2zmfjfpuo.html

files=$(ls -1)
来源：http://dali.cqqwz.cn/Article/details/gt2ezngxexg.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gt2nmmrnlnz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gt2ydelzdfr.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zehaegyj.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2nxuwmkwe.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gt2tteahmua.html

echo "log" >> out.log
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvuliblo.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gt2xbsjdsla.html

cmd >/dev/null 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gt2bvpeqjam.html

[R42] 输入重定向
来源：http://dali.gaohongyu789.top/Article/details/gt2asjqaret.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqaaflux.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gt2rhtlfdzh.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gt2hjjdeufe.html

[R44] 按修改时间查找
来源：http://dali.gogol.net.cn/Article/details/gt2wcvrcwsz.html

find . -mtime -7 -type f
来源：http://dali.mhx1999.top/Article/details/gt2hmmervre.html

[R45] 批量删除
来源：http://dali.jlsjyb.cn/Article/details/gt2dpugbyni.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eioambhk.html

[R46] 递归替换文件内容
来源：http://dali.jqgfzy.top/Article/details/gt2nmnujinj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gt2ouodqgba.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gt2wtikccaa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2pbaxsuex.html

[R48] awk 取指定列
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwcjegbl.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2xxcinobi.html

[R49] awk 带条件
来源：http://dali.xylfe.cn/Article/details/gt2rkshwvop.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gt2vjgyjnwj.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gt2pdzkxpqe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxrhfuzi.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gt2nciwquff.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tian-w.cn/Article/details/gt2dauurarb.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gt2yjaaqerm.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2vcbocpcw.html

[R53] 查看文件头与实时尾
来源：http://dali.yvedp.cn/Article/details/gt2qawcgeno.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.9152youxi.cn/Article/details/gt2sxupchot.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gt2jusevuad.html

diff a.txt b.txt
来源：http://dali.ybcxt.top/Article/details/gt2zzpkuqgd.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gt2rfylrqsa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cheryme.top/Article/details/gt2kzhttyro.html

[R56] 远程拷贝
来源：http://dali.shzxlz.cn/Article/details/gt2bryabedn.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gt2anxktbkm.html

[R57] 远程执行命令
来源：http://dali.cucudq.cn/Article/details/gt2cfwzecgq.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gt2ndqosyir.html

[R58] 下载文件
来源：http://dali.zhixingplan.top/Article/details/gt2ytoktdwt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gt2idaolwni.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gt2rianneud.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbcxvuga.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gt2vnxdwaqp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.redwolf501.top/Article/details/gt2yjznjagl.html

[R61] 磁盘占用
来源：http://dali.c1oappe.top/Article/details/gt2nejxdenj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2egpcymjl.html

[R62] 找最占空间的文件
来源：http://dali.ehwqpu.com/Article/details/gt2tglgbews.html

du -ah . | sort -rh | head -10
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpgnnlva.html

[R63] 内存与进程
来源：http://dali.kuanghao11.cn/Article/details/gt2bsffayuk.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gt2bswbdjyd.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gt2ttrjrjgv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gt2fobpoyqo.html

[R65] 查看端口占用
来源：http://dali.ydzc1.top/Article/details/gt2rxhrxcmi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gt2vtbgosei.html

[R66] 定时任务
来源：http://dali.yuxming.cn/Article/details/gt2gufmcouc.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gt2fpkdxopt.html

[R67] 生成随机十六进制串
来源：http://dali.shzxlz.cn/Article/details/gt2tumtnnlm.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gt2zbthvlab.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gt2rscwofkb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shuidangran.top/Article/details/gt2awbhrfqe.html

[R69] 生成随机密码
来源：http://dali.zhengqikj.top/Article/details/gt2ykhkzfcp.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gt2tizhkbjw.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gt2eksbculc.html

date +%s;  date -d @1700000000
来源：http://dali.zdqjudy.top/Article/details/gt2ethxuxfw.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhyzqcmk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urwempyu.html

[R72] 等待端口就绪
来源：http://dali.redwolf501.top/Article/details/gt2msornswf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gt2ttjqrcdr.html

[R73] 分割大日志
来源：http://dali.dianchejie.cn/Article/details/gt2ynklojsg.html

split -l 1000 big.log part_
来源：http://dali.jinqigfzy.top/Article/details/gt2ukexsbba.html

[R74] 批量重命名
来源：http://dali.andypj.xyz/Article/details/gt2gsnnkasa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cqqwz.cn/Article/details/gt2muflnsnw.html

[R75] 导出环境变量
来源：http://dali.0kj1m.cn/Article/details/gt2ankcoolq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gt2xiwardwa.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gt2pofkzyjf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2mvabaadf.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gt2jtqxqxet.html

read -rp "请输入: " ans
来源：http://dali.quarkkingdee.top/Article/details/gt2hcwuwyvx.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrczkwyj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gt2ceydpkey.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gt2mcmkaraq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.c1oappe.top/Article/details/gt2ajxhdqil.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gt2pghkhjkn.html

time ./run.sh
来源：http://dali.sysykeji.top/Article/details/gt2dtvbdlet.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2teyzwtqo.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpdljlcq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2qbnekqhc.html

[S01] C：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2bnslpqem.html

#include <stdio.h>
来源：http://dali.tian-w.cn/Article/details/gt2bfxcvuli.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ejvkfsdv.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gt2kqgrueqe.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brdfhxas.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gt2xifcvllv.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gt2mgxnfpwn.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gt2pcwrqfio.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2entwhjel.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gt2mzpoihtv.html


<!-- 参考信息 -->