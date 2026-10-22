代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gtxqpxvrho.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gtmulyptvo.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gtuvnizzrl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shzxlz.cn/Article/details/gtjowhxqnb.html

[Q44] IN 子查询
来源：http://dali.wangdashe.top/Article/details/gtgmhyhzht.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gtyksjxoke.html

[Q45] EXISTS 判断存在
来源：http://dali.tian-w.cn/Article/details/gtexcjxmfh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gthazapmfw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gogol.net.cn/Article/details/gttcckgcle.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gtbjmsshxa.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gtubzqqlny.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gtnsxikfmg.html

[Q48] CTE 公用表表达式
来源：http://dali.vqdsnc.cn/Article/details/gtggpkfgzt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gtirhceaid.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gtughmgobp.html

[Q49] 更新单行
来源：http://dali.gaohongyu789.top/Article/details/gtearbmvxr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtrucnhpwt.html

[Q50] 批量更新
来源：http://dali.shuidangran.top/Article/details/gtznaddydd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xylfe.cn/Article/details/gtpzcmkwgs.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gtwowhjjmo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgfzy.top/Article/details/gtaiqqnmmx.html

[Q52] 删除指定行
来源：http://dali.chenzaomai.com/Article/details/gtmfrihmpv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtipsaakpk.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gttwjhznzz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gtmvrgmums.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfiekoomo.html

TRUNCATE TABLE logs;
来源：http://dali.daxiang520.top/Article/details/gtzhajvtfu.html

[Q55] 排名（并列占位）
来源：http://dali.daria6918.cn/Article/details/gtqveinfyu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtjrujlzsx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiujpmghc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtksfpzzkm.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gtocyspmbu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtfwswkhbx.html

[Q58] 累计求和
来源：http://dali.nanxinkj.top/Article/details/gtygscbdiw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtvnporkgp.html

[Q59] 分组内累计
来源：http://dali.0kj1m.cn/Article/details/gtzrnefbed.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtxfnbbxba.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gtxmhmncdl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gtoqpogvez.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtnzgnzmco.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gtdvligaxc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtymbqmmup.html

[Q62] 分组占比
来源：http://dali.ppjwa.cn/Article/details/gtbzaghtnq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtueldftad.html

[Q63] 开启事务
来源：http://dali.zdqjudy.top/Article/details/gtjbkqhhel.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aibaodan.cn/Article/details/gtkyekbkzs.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gtyjjmpejc.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gtmuhhaymy.html

[Q65] 回滚事务
来源：http://dali.yuanzhike.top/Article/details/gtxgwweybh.html

ROLLBACK;
来源：http://dali.gogol.net.cn/Article/details/gtxakklcyu.html

[Q66] 行锁查询
来源：http://dali.dianchejie.cn/Article/details/gtazqinmzd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hongshengwenyu.top/Article/details/gtsnycxgss.html

[Q67] 设置隔离级别
来源：http://dali.hnxiangtu.top/Article/details/gtjbvtdxgg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gtsyiczstw.html

[Q68] 保存点
来源：http://dali.aizwys.cn/Article/details/gtiobbcayt.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gteldyyvxh.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gtxfywucdn.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gtekxjbpzk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gtxccjfchh.html

[Q70] 更新统计信息
来源：http://dali.pengpengdd.cyou/Article/details/gtlvlfnjwb.html

ANALYZE TABLE users;
来源：http://dali.sweek.top/Article/details/gtbhlaaesi.html

[Q71] 查看建表语句
来源：http://dali.gotoacloud.top/Article/details/gttlcdewqq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gtqrdpsaxq.html

[Q72] 查看索引
来源：http://dali.xziqi.cn/Article/details/gtnnlzotxv.html

SHOW INDEX FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtndltlztg.html

[Q73] 查看表状态
来源：http://dali.316326.xyz/Article/details/gtaesylrrs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtesrsycxf.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gtgxblyvhi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ydzc1.top/Article/details/gtfepkpant.html

[Q75] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtrjncpcsh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtvgcvgjqr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuetiantiany.cn/Article/details/gtlvqxqhxc.html

[Q76] 按天统计
来源：http://dali.nwbrower.top/Article/details/gtqujbdvbu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gttxzhffhg.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtbanhkmif.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangtech.top/Article/details/gtdndzydil.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gtagrfbmxp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gtmvshqjex.html

[Q79] 字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtfkzaajrc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gtbtstjxaj.html

[Q80] 字符串截取
来源：http://dali.yuxming.cn/Article/details/gtigitugef.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtmwyfwhgv.html

[Q81] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gthxailvfh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gtyhfaglby.html

[Q82] 字符长度与字节长度
来源：http://dali.0kj1m.cn/Article/details/gtfzmnombr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtpcetpoog.html

[Q83] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gthfqykaez.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gttpyathff.html

[Q84] 去除首尾空格
来源：http://dali.yuanzhike.top/Article/details/gtnuxxnidv.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtfdahfkho.html

[Q85] 数值取整
来源：http://dali.tanke756.top/Article/details/gtadlxzcmr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkmezjlt.html

[Q86] 读取 JSON 字段
来源：http://dali.yueranfly.top/Article/details/gtxrdihpkh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jiagoushi.top/Article/details/gtzgpoflsc.html

[Q87] JSON 字段做条件
来源：http://dali.c1oappe.top/Article/details/gtpbrhxevy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhoulong.xyz/Article/details/gtjoxvirhx.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gtatjucowr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.havefunace.top/Article/details/gtfdgpnjyh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gttuflasmf.html

[Q89] 判断表是否存在
来源：http://dali.aizwys.cn/Article/details/gttwvhrwkf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gtocjsxtwf.html

[Q90] 生成序号列
来源：http://dali.yongpay.top/Article/details/gtldqbdtpu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttedpelbd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqalpgpcd.html

R. Bash 专题
来源：http://dali.hfpthk.cn/Article/details/gtagxpatyx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtdpqgqwze.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtfomppccz.html

#!/usr/bin/env bash
来源：http://dali.tianlin.xyz/Article/details/gtkzqrtgpr.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gtjaduwvfl.html

[R02] 变量赋值与使用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvtbpzey.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gtuqrjzqgg.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gtolxqzuhf.html

readonly PI=3.14
来源：http://dali.tianlin.xyz/Article/details/gtfuurukrk.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gtemumqyjd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cqqwz.cn/Article/details/gtthhhxwnt.html

[R05] 参数默认值
来源：http://dali.fzhhl.top/Article/details/gtgoaabeph.html

name="${1:-default}"
来源：http://dali.dashuyun.cn/Article/details/gtsaytkuqz.html

[R06] 判断命令是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtsgqmoxgi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsdejoau.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gtljtczhes.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gtrjqueaco.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gtvxywxnww.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gtwncndosa.html

[R09] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gtsdakewjd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtkgcsdbab.html

[R10] 正则匹配
来源：http://dali.c1oappe.top/Article/details/gtyekqaawe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbeweniw.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gtfizisazw.html

case "$1" in
来源：http://dali.ivvv.top/Article/details/gtgvedmfgo.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfxpscbw.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtdhvpwgdh.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gtifsapwrx.html

esac
来源：http://dali.xylfe.cn/Article/details/gthriayblu.html

[R12] for 遍历文件
来源：http://dali.dianchejie.cn/Article/details/gtdozsylon.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtxvmpzmhk.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gtbhubdmrf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtlluelscw.html

[R14] C 风格 for
来源：http://dali.cdnleiting.top/Article/details/gthoxvouvz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gteiirrukh.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gttnyyvulo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangdashe.top/Article/details/gtwfoyepgx.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gtzczpgwgz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtzgdfzbfc.html

[R17] 数组定义与取值
来源：http://dali.yj20258.top/Article/details/gtiptaacql.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwdhsobi.html

[R18] 遍历数组
来源：http://dali.sysykeji.top/Article/details/gtyqkhpgrk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjkpcmte.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtjkzqamqf.html

echo "${#arr[@]}"
来源：http://dali.cqqwz.cn/Article/details/gtjmcdvlzl.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gtftznrifd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gtyjgskevr.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gthzldqide.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gtzvmjqauh.html

[R22] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gtogfacret.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcpqqlwh.html

[R23] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtzshgxyjw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtjtmlhivq.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtxfxqtqby.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gtekgrlqou.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtevdytjlc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gtwmsomeit.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gttqmqktpo.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gtgqdeyzbx.html

[R27] 算术展开
来源：http://dali.snrcjt.cn/Article/details/gtrrrkbhvn.html

echo $((1 + 2 * 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtozqjppmb.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gtlvtomozy.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gtofoxbxkd.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtnnvavmlk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gtqmcmsfza.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gtrxfpmadj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gtbdcplndx.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gtauwhbupw.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnbawtscs.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gtzhktgyuz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtzmgprdmb.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gtwufmkqer.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yonumen.top/Article/details/gttxjsiaep.html

[R34] 退出时清理
来源：http://dali.zdqjudy.top/Article/details/gtdplehxwg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjawfdcbw.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gtitrlentu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hysaishi.cn/Article/details/gtdsoihvhw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gtimxopcvr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gtswlrktup.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gtsirdrwny.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gtxkymofmu.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gtcpaultms.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tianlin.xyz/Article/details/gtntymynhq.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtvyfxajzj.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaybfkrvg.html

[R40] 追加写日志
来源：http://dali.cucudq.cn/Article/details/gtgyelcvmp.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gtvcsekjhl.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkxnzbtm.html

cmd >/dev/null 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtlkmzetwe.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gtxvnmbsst.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gtbloegwyf.html

[R43] 按名字查找文件
来源：http://dali.hfpthk.cn/Article/details/gtwwvurcns.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gttcwzmhdu.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gtlwekmseh.html

find . -mtime -7 -type f
来源：http://dali.xuetiantiany.cn/Article/details/gtgecsffya.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnbkpwpt.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtqwxvnoaz.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gtuxkehbxr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gtpmalljam.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gtwgzmpqpl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtmwpsjgpe.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqnnmwze.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gtigbrkwho.html

[R49] awk 带条件
来源：http://dali.yanxiufei.cn/Article/details/gtluwvkwtm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.mhx1999.top/Article/details/gtqotvpqjp.html

[R50] awk 求和
来源：http://dali.cashguo.top/Article/details/gtaosnhfia.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtyfkdfgjc.html

[R51] 排序去重取前几
来源：http://dali.yongpay.top/Article/details/gtypdbaoof.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj202588.top/Article/details/gtgwhgjgdp.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gtiiapqgog.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gtcxvxfvgn.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gtibptlhit.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgufenzy.top/Article/details/gtstcuvsid.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gtxxymhtwz.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gtuwnioxef.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gtwhdxghcz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gthvtzoiyu.html

[R56] 远程拷贝
来源：http://dali.tian-w.cn/Article/details/gtnxklrwoz.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gtgznfiqvq.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gtmfefhmal.html

ssh user@host 'uptime'
来源：http://dali.hnqzz.top/Article/details/gtorvvvrer.html

[R58] 下载文件
来源：http://dali.sysykeji.top/Article/details/gtzeybkuhg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gtnsiliuns.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gtnulrpjes.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gtncotlhya.html

[R60] 只看 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gtfrorkqtt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtuklgjjgo.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gtnjiuyqwl.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gtqmnjaouu.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrpneudm.html

du -ah . | sort -rh | head -10
来源：http://dali.ydzc1.top/Article/details/gtbibcxdkr.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gttiqlnvho.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gtjhhtwofp.html

[R64] 结束进程
来源：http://dali.aizwys.cn/Article/details/gtrkngkgml.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daria6918.cn/Article/details/gtzvlgaqmq.html

[R65] 查看端口占用
来源：http://dali.zhoulong.xyz/Article/details/gtaldkmkzt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fengsongda.top/Article/details/gtcubvlmkg.html

[R66] 定时任务
来源：http://dali.jqgfzy.top/Article/details/gtmaaaimsr.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gtlrxqhbpu.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwsyreqb.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gtnetkkqnt.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gtynhhzsjf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ppjwa.cn/Article/details/gtijvaeial.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gtsgzazhuz.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gthoxpehod.html

[R70] 时间戳与互转
来源：http://dali.sysykeji.top/Article/details/gtcspkpzar.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gtbqwyqjlw.html

[R71] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtwpygjuqt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gtfjitxkxt.html

[R72] 等待端口就绪
来源：http://dali.nanxuanxn.top/Article/details/gtndnygmjr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtyxxssuga.html

[R73] 分割大日志
来源：http://dali.shangyingyoupin.top/Article/details/gtnsmscpxa.html

split -l 1000 big.log part_
来源：http://dali.jqgfzy.top/Article/details/gtlvfrhewb.html

[R74] 批量重命名
来源：http://dali.yonumen.top/Article/details/gtgznydsax.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pycfn.com/Article/details/gtykraepil.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gthnjngxvn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gtqfaywzgz.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gtjxzpbvjg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtqfgpqaaj.html

[R77] 读取用户输入
来源：http://dali.9152youxi.cn/Article/details/gterybywob.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtkpbpegvq.html

[R78] 交互式菜单
来源：http://dali.jqgufenzy.top/Article/details/gtlhvkulbx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gtkmrjmhvm.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gtmjovjvej.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gtwyiwgquo.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gtvkadrzxt.html

time ./run.sh
来源：http://dali.pengpengdd.cyou/Article/details/gtyhichsxv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlhbwlzyo.html

S. C / C++ 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzdugaqg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtuubtmrlh.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gtwvnmpsxx.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gtodfgtsdh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gtksdqbahb.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpehczcyu.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gtywiyafpa.html

[S03] C：读入整数
来源：http://dali.xylfe.cn/Article/details/gtibofblkt.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtmlutiuuj.html

[S04] C：字符串复制
来源：http://dali.ivvv.top/Article/details/gtvqhidkia.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gtdujqlzai.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gtxddchixf.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gtyopydhlb.html

[S06] C：字符串比较
来源：http://dali.gzhubu.top/Article/details/gtnxolfxld.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gtvmipohnf.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gtnqtyvkwd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangshuangyany.cn/Article/details/gtcspqwlrf.html

[S08] C：动态内存分配与释放
来源：http://dali.andypj.xyz/Article/details/gtdvpayvbd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhongyouzk.top/Article/details/gtnncfsdyy.html

[S09] C：结构体定义与初始化
来源：http://dali.hongshengwenyu.top/Article/details/gtjdoufzva.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gtunjljrlq.html

[S10] C：指针与解引用
来源：http://dali.fengsongda.top/Article/details/gtrxcgiffn.html

int *p = &a;  *p = 5;
来源：http://dali.kuanghao11.cn/Article/details/gtnowjnfuw.html

[S11] C：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtgphsrfog.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gtpopcpgks.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuanzhike.top/Article/details/gtmxmvakyo.html

fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtnxwbakjy.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtlsvuowuk.html


<!-- 参考信息 -->