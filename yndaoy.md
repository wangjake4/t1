代发 wailian999

[Q36] 左连接
来源：http://dali.havefunace.top/Article/details/gtludagwrg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtidzdiugy.html

[Q37] 右连接
来源：http://dali.gotoacloud.top/Article/details/gtekgqqdlz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sysykeji.top/Article/details/gtvxrstlgg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fzhhl.top/Article/details/gtgmnmcifn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.mhx1999.top/Article/details/gtznqtwcpw.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gtkwsdtkhh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gtknxruker.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gtekqigqbq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gtgnqnblrh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.quarkkingdee.top/Article/details/gtiougrvhu.html

[Q41] 多表连接
来源：http://dali.yj20258888.top/Article/details/gtgiacjfuk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gtmyayjfdp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggabjwrr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gtiqhpotmx.html

[Q42] 连接条件附加过滤
来源：http://dali.yongpay.top/Article/details/gtjpgzxmcx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyciwfvop.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gtxulsajtz.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtegwbstil.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gtthvyczjw.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gtcxvtufan.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jianghu66.top/Article/details/gthglyqatx.html

[Q45] EXISTS 判断存在
来源：http://dali.jlsjyb.cn/Article/details/gthlakhljl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtzdowcqiw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxuanxn.top/Article/details/gtpjiekdhu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtpeazzfje.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gtavqaopvk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gttettrisz.html

[Q48] CTE 公用表表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtebsqpoxr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgufenzy.top/Article/details/gtoeqcxaqh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtjcsbpbvw.html

[Q49] 更新单行
来源：http://dali.jinghuilouyu.cn/Article/details/gtvalealpn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtuvexvfne.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gtdfpmxidr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gtovzbxbaz.html

[Q51] 用子查询更新
来源：http://dali.daria6918.cn/Article/details/gtzreahviq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gtjykwhjae.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gtinihtlee.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtatyuaauk.html

[Q53] 按条件删除
来源：http://dali.sxryk.cn/Article/details/gtqdnotivf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtpecifmbl.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gtvgggbhjc.html

TRUNCATE TABLE logs;
来源：http://dali.zhongyouzk.top/Article/details/gtbwayhneg.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gtefyzqnoc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gttconlsew.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxinkj.top/Article/details/gtbggdcydt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gttdbcpqzg.html

[Q57] 行号
来源：http://dali.iojbl.cn/Article/details/gtbpijhled.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtmjylbmsi.html

[Q58] 累计求和
来源：http://dali.gogol.net.cn/Article/details/gteobyfbue.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtdulusigl.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gtucsxwwbl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtgbsdgyel.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gtcckqynbk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gtvtemqhgv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gthmbnyjgb.html

[Q61] 移动平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqhdukoc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtvnehkdli.html

[Q62] 分组占比
来源：http://dali.mhx1999.top/Article/details/gtbsqltvuk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgalyjqwu.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gtqlrxdhvv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gtcopffndl.html

[Q64] 提交事务
来源：http://dali.dashuyun.cn/Article/details/gtpjikpcva.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gtimcrxvte.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gtoseqwmlm.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gtoeeotlkn.html

[Q66] 行锁查询
来源：http://dali.jqgfzy.top/Article/details/gtiqwwuhvp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgxotexx.html

[Q67] 设置隔离级别
来源：http://dali.pengpengdd.cyou/Article/details/gtmxnmbzsu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gtxmyblpcs.html

[Q68] 保存点
来源：http://dali.zycfv.cn/Article/details/gtcgenqxha.html

SAVEPOINT sp1;
来源：http://dali.cucudq.cn/Article/details/gtutxwckbg.html

ROLLBACK TO sp1;
来源：http://dali.gotoacloud.top/Article/details/gteaxyizvr.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gtmuthoqxh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenjidiqi.icu/Article/details/gtqjrvfosx.html

[Q70] 更新统计信息
来源：http://dali.guowangkeji.top/Article/details/gtrkdufdfs.html

ANALYZE TABLE users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazumtjwv.html

[Q71] 查看建表语句
来源：http://dali.feifeiyinyue.top/Article/details/gtoefdqekp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hfpthk.cn/Article/details/gtowhhxzoo.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gtlhfggkpg.html

SHOW INDEX FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtlzlendvr.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gtsnsuupep.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gteobhnjlg.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gtyyvgeqrf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guannengcc.top/Article/details/gtvmwzcsgp.html

[Q75] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtznmcmixl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.meibo888.top/Article/details/gtasktuddp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.feifeiyinyue.top/Article/details/gtrzlacvbk.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gtygelohpn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.vqdsnc.cn/Article/details/gtiwtjblwk.html

[Q77] 时间加减
来源：http://dali.hnqzz.top/Article/details/gtrmdgdbcz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhengqikj.top/Article/details/gthkifrnfz.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gthdisjaqm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gtwvyjrxtw.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gtrblucxuy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shuidangran.top/Article/details/gtrpkbcidr.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gtuotqahwz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtetdrkmjk.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtobwazfvn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gtowwevrth.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gtrvobyiww.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtzefmkzcs.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtolfxgcsi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtezkzkzsh.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gtxcrcecxo.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtyjdfwpyb.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gtcqlbstbv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yangfankeji.com/Article/details/gtrcdyaech.html

[Q86] 读取 JSON 字段
来源：http://dali.zhengqikj.top/Article/details/gtvzdwddii.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgufenzy.top/Article/details/gtqrflthua.html

[Q87] JSON 字段做条件
来源：http://dali.wangdashe.top/Article/details/gtvxfoylgl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhengqikj.top/Article/details/gtctgfawdr.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtatiitfum.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gtwftxpkjg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtpwfhrxlc.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gtrpmdpkqp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gtsznqmtwt.html

[Q90] 生成序号列
来源：http://dali.gzhubu.top/Article/details/gtxrkdazke.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gtkrwcsjak.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtkbhdwwwy.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gtiyjqgtfi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtigzbjrfy.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtecjyzvtk.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtnbjzdbfm.html

set -euo pipefail
来源：http://dali.haohaochexian.top/Article/details/gtjlgqpeay.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gtzuvfxjsz.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gttvvvryon.html

[R03] 只读变量
来源：http://dali.yongpay.top/Article/details/gtqqskpwdn.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gtoabituhc.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gtnuuteeia.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gtzghrhlvd.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gtqtawvrfp.html

name="${1:-default}"
来源：http://dali.hammf.cn/Article/details/gtgzdyygkv.html

[R06] 判断命令是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtzdyfqrhv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtfgtntdnp.html

[R07] if 判断文件
来源：http://dali.sufxvd.cn/Article/details/gtflqkggsh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtwaigujvg.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gtuhhfxkja.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtcioefhnl.html

[R09] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtrmabnabv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtobblybqp.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gtsbhholom.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtvjgtkoqg.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gtcbmrielw.html

case "$1" in
来源：http://dali.chenzaomai.com/Article/details/gthuizronm.html

start) echo "启动" ;;
来源：http://dali.xziqi.cn/Article/details/gttvjlyqvs.html

stop)  echo "停止" ;;
来源：http://dali.zycfv.cn/Article/details/gtxuemppja.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gthevjsygb.html

esac
来源：http://dali.hongshengwenyu.top/Article/details/gtpnvaqakn.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbexfnlyp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtwslaozat.html

[R13] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gtmysbtldm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtqxihrfqv.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpxkybcv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtkrorueny.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfafiiydc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gtvmvdiktn.html

[R16] until 等待条件
来源：http://dali.zhiwuduotai.top/Article/details/gtlvvjcsnf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtiodmfdjg.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gtvcyawekk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gtkkoujhnz.html

[R18] 遍历数组
来源：http://dali.iojbl.cn/Article/details/gtcpxwdzuz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gtosyzsrmx.html

[R19] 数组长度
来源：http://dali.xziqi.cn/Article/details/gtfsnkqfgz.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gtycnoexkh.html

[R20] 关联数组（字典）
来源：http://dali.yueranfly.top/Article/details/gtlllemkrs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gteoxhyudq.html

[R21] 字符串长度
来源：http://dali.fzhhl.top/Article/details/gtyhkiihwt.html

echo "${#s}"
来源：http://dali.chenjidiqi.icu/Article/details/gtflqiexoa.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtlpotycyg.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gtsumenecv.html

[R23] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtuneileya.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gtsevsklrq.html

[R24] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gtayctznlm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gttrdrbwrv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gtgnolznto.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenjidiqi.icu/Article/details/gtrqnpncrq.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtvxrmklqp.html

now=$(date +%F); echo "$now"
来源：http://dali.xylfe.cn/Article/details/gtbrvzqorq.html

[R27] 算术展开
来源：http://dali.sufxvd.cn/Article/details/gthkrgzdfl.html

echo $((1 + 2 * 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxsustaw.html

[R28] 浮点运算
来源：http://dali.havefunace.top/Article/details/gtshwhonuw.html

echo "scale=2; 10/3" | bc
来源：http://dali.daria6918.cn/Article/details/gtafdrxtel.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gtnwyckctu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gtoqqlzifo.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtjnfnwwfr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daria6918.cn/Article/details/gtvtpnjqsb.html

[R31] 局部变量
来源：http://dali.wangdashe.top/Article/details/gthbxwqsjj.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgufenzy.top/Article/details/gtxlqdhrnd.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gtiblynidm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtihydwbii.html

[R33] 捕获错误并提示行号
来源：http://dali.dashuyun.cn/Article/details/gtsttcoevd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigufen.top/Article/details/gtmszxmpmt.html

[R34] 退出时清理
来源：http://dali.yuxming.cn/Article/details/gtycxkgpqf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtvadesibw.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gtciahosry.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fengsongda.top/Article/details/gtnvxtrzky.html

[R36] 并发执行多个任务
来源：http://dali.fengsongda.top/Article/details/gtwqxzjjta.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gtrnqyndfa.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gtyccaiupl.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtsgezgalm.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gtipxdpbii.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tanke756.top/Article/details/gthibssxfb.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gtkhpjtlxk.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtcxtjmbfb.html

[R40] 追加写日志
来源：http://dali.zhiwuduotai.top/Article/details/gtjagjqwhf.html

echo "log" >> out.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnoxdkil.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gtsqjbghdx.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gthmhejsiw.html

[R42] 输入重定向
来源：http://dali.hongshengwenyu.top/Article/details/gtjykujexk.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gtpktjnwmt.html

[R43] 按名字查找文件
来源：http://dali.hywenlv.cn/Article/details/gtcsmszhxx.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gtopnrtwxm.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gtwpasmypl.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gtdhlvbmqf.html

[R45] 批量删除
来源：http://dali.feifeiyinyue.top/Article/details/gtodnhpvxt.html

find . -name "*.tmp" -delete
来源：http://dali.xuanzx.com/Article/details/gtjurdqhyd.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gtmfqmhgym.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sxryk.cn/Article/details/gtzazvxozv.html

[R47] sed 单行替换
来源：http://dali.yangfankeji.com/Article/details/gtgdxytgyu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gtrpkiuyqw.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gtmbdpingk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtxtmqbzsl.html

[R49] awk 带条件
来源：http://dali.yvedp.cn/Article/details/gtnsorkkot.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gttrydwhrc.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gtyhshszqq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtwajyxlyl.html

[R51] 排序去重取前几
来源：http://dali.zhoulong.xyz/Article/details/gtuaitqkej.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gtiodxludu.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gtezadwynr.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gtcdsqkfxl.html

[R53] 查看文件头与实时尾
来源：http://dali.mhx1999.top/Article/details/gtaxptywzp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gtrwgaowsk.html

[R54] 比较两个文件
来源：http://dali.gogol.net.cn/Article/details/gtsjrwcisi.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gtlgasbnjw.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtgqfvvrpz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.birdmap.top/Article/details/gtcrbkihev.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gtfrgjjsmo.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gtxebsswyp.html

[R57] 远程执行命令
来源：http://dali.zhengqikj.top/Article/details/gtnmiouoeo.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gtxgpwqjgh.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gtrsuxugpr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfhthliw.html

[R59] 发 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtalsjyqai.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xylfe.cn/Article/details/gtxqraxqlz.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtfbdqmqdh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gtordezebv.html

[R61] 磁盘占用
来源：http://dali.aizwys.cn/Article/details/gtmqusplzm.html

df -h;  du -sh *
来源：http://dali.mhx1999.top/Article/details/gtfhywowod.html

[R62] 找最占空间的文件
来源：http://dali.chenjidiqi.icu/Article/details/gteikjxiil.html

du -ah . | sort -rh | head -10
来源：http://dali.yueranfly.top/Article/details/gthkvmestu.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gtafpectyq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gthquktryl.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gtgnefynkz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.quarkkingdee.top/Article/details/gtunylmhvs.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgebovnv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmqnkbrc.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gtaifcfyyy.html

crontab -e;  crontab -l
来源：http://dali.cucudq.cn/Article/details/gtoembasto.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gtivknrsme.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gtnacmlyfa.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gttwqagswl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtrmbwaqve.html

[R69] 生成随机密码
来源：http://dali.aizwys.cn/Article/details/gtuwiijzpm.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenzaomai.com/Article/details/gttyubdono.html

[R70] 时间戳与互转
来源：http://dali.yanxiufei.cn/Article/details/gtoikuwirx.html

date +%s;  date -d @1700000000
来源：http://dali.shuidangran.top/Article/details/gtpetasocs.html

[R71] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtmmkqbudq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxinkj.top/Article/details/gtfpogtmmy.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtnrdprlwo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzwqbkmz.html

[R73] 分割大日志
来源：http://dali.tianlin.xyz/Article/details/gtvqbopsuw.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjoxwubg.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryznjfbr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hfpthk.cn/Article/details/gtdecaernb.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtonbfsvsg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gtojzxccrz.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gtzigznpwg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gtwngdtndy.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gtwdrvrgbu.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gtrxczvpqo.html

[R78] 交互式菜单
来源：http://dali.zhoulong.xyz/Article/details/gtytegifdl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gtpabycsuz.html

[R79] 解析命令行选项
来源：http://dali.meibo888.top/Article/details/gtekwlukvm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnxiangtu.top/Article/details/gtlhttvuzh.html

[R80] 查看脚本执行耗时
来源：http://dali.guannengcc.top/Article/details/gtgaevuoqj.html

time ./run.sh
来源：http://dali.316326.xyz/Article/details/gtdxhzchnj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtoazrcifm.html

S. C / C++ 专题
来源：http://dali.hnqzz.top/Article/details/gtgksusvqw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtlcylecuv.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtzknidipt.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gtlwcibuwi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gtiroxjmwb.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtkxkrwrxw.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gtufvbxlnh.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gtdkcruyxb.html

int x; scanf("%d", &x);
来源：http://dali.svipenyu.cn/Article/details/gtkayywarv.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gtpevxrbwn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtlkopassb.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gtzdxqxwnl.html


<!-- 参考信息 -->