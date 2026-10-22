代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gtqtfesaxv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guowangkeji.top/Article/details/gtlqgikxla.html

[Q39] 自连接（查上下级）
来源：http://dali.jianghu66.top/Article/details/gtfajuwflz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sufxvd.cn/Article/details/gttrwsiwbt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.c1oappe.top/Article/details/gtnavmpzio.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gtosqzfuea.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gtkqzityuu.html

[Q41] 多表连接
来源：http://dali.quarkkingdee.top/Article/details/gtwhfotyhk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fzhhl.top/Article/details/gtfjyzonyw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtpolvstyn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhoulong.xyz/Article/details/gtwmpbzfgk.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gtasvhqvde.html

SELECT u.name, o.amount FROM users u
来源：http://dali.vqdsnc.cn/Article/details/gtqzzslkbl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtvlkpwnvf.html

[Q43] 标量子查询
来源：http://dali.shzxlz.cn/Article/details/gtqldcmofm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gtvbxjnoim.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gtcpfhfogt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gtkclmzidi.html

[Q45] EXISTS 判断存在
来源：http://dali.tanke756.top/Article/details/gtkxbqvxdz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gtvgzlpxxf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daxiang520.top/Article/details/gthuxdfpvd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtvybnpqdi.html

[Q47] 与平均值比较
来源：http://dali.jyoumei.cn/Article/details/gttiimjntd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtkjgpmbuq.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gtzrnqhbqy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nwbrower.top/Article/details/gtpejkapyd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cashguo.top/Article/details/gtkittrxvw.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gtcclipfdj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gttzzdhgcs.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gtgiabgleg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtgmpslvoe.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gtzjpfncme.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gtkvojxtrc.html

[Q52] 删除指定行
来源：http://dali.ivvv.top/Article/details/gtkmirkemu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gtfrmdqqtg.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gthgavckfa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtitalrvsa.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gtvzzfvcqq.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gtratxwyqi.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gtdhhynsey.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gtzisjtdoq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gteexmkghe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtgzcsfrjy.html

[Q57] 行号
来源：http://dali.gotoacloud.top/Article/details/gtgtbzwynw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtjiwmaniv.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gtainwdsdn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtjgacunej.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gtsekqhxze.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtsvmymzvo.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gtthvzyxrk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shangyingyoupin.top/Article/details/gtonijcfli.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtjftfazgq.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gthprfsbbv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtlkvokhag.html

[Q62] 分组占比
来源：http://dali.yj202588.top/Article/details/gtvubzlezn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtauhjujhr.html

[Q63] 开启事务
来源：http://dali.yuanzhike.top/Article/details/gtkwbshgan.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yangfankeji.com/Article/details/gtebvskoja.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gtoavondod.html

COMMIT;
来源：http://dali.quarkkingdee.top/Article/details/gtopsukhxn.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gtmdptahlf.html

ROLLBACK;
来源：http://dali.xinyue.icu/Article/details/gtznyqyvig.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gtdfhzvxtr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258888.top/Article/details/gtfspgmvuv.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gtgunsfmas.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258888.top/Article/details/gtjuhqkscl.html

[Q68] 保存点
来源：http://dali.zhoulong.xyz/Article/details/gtuyhtkahu.html

SAVEPOINT sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gtbdexvufw.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gtmliyqehe.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpbhckxt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gttbpvpfqe.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtibysbdzh.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gtfuaoicge.html

[Q71] 查看建表语句
来源：http://dali.yueranfly.top/Article/details/gtdtfesare.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yueranfly.top/Article/details/gtzevmmukp.html

[Q72] 查看索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrntsgnen.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gtxlujklqy.html

[Q73] 查看表状态
来源：http://dali.pengpengdd.cyou/Article/details/gtvqzowxco.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.birdmap.top/Article/details/gtdaxooobb.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtaffqfztv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gtuebhwwny.html

[Q75] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gttkvqqhsj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtpyhwtvio.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gtghryuhjy.html

[Q76] 按天统计
来源：http://dali.chenjidiqi.icu/Article/details/gtaypixoaj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gtzxycqvjq.html

[Q77] 时间加减
来源：http://dali.ybcxt.top/Article/details/gtmzkjguwr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cheryme.top/Article/details/gtwutkeymx.html

[Q78] 当前时间
来源：http://dali.sysykeji.top/Article/details/gtgnlmwwud.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gtuqvenyht.html

[Q79] 字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtbwiwgezf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258.top/Article/details/gtfdzfgyjp.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gtapycqrfu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtcqufgkdc.html

[Q81] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtukwvvjkh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtrrpvccin.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gtgjyekdbg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gthbvlzssn.html

[Q83] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtuxgbjtgh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtswrmughp.html

[Q84] 去除首尾空格
来源：http://dali.havefunace.top/Article/details/gtkyxgmiwr.html

SELECT TRIM(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunepmzhx.html

[Q85] 数值取整
来源：http://dali.xuetiantiany.cn/Article/details/gtrvbjqndv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gtiuvulbog.html

[Q86] 读取 JSON 字段
来源：http://dali.ppjwa.cn/Article/details/gtthjfjujp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctkqurtn.html

[Q87] JSON 字段做条件
来源：http://dali.zhiwuduotai.top/Article/details/gtlpnzrstr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gtjhuwunux.html

[Q88] 行转列（条件聚合）
来源：http://dali.hammf.cn/Article/details/gttdufoony.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gttyoanybl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtzrgrpaks.html

[Q89] 判断表是否存在
来源：http://dali.yuxming.cn/Article/details/gtazrkjtlq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhengqikj.top/Article/details/gtlxkkgzdo.html

[Q90] 生成序号列
来源：http://dali.xylfe.cn/Article/details/gtwjfyrwjw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gtqmwxseyb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtlblumcjx.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gthydooxhn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtaiiyvtun.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gttiqnpspz.html

#!/usr/bin/env bash
来源：http://dali.0kj1m.cn/Article/details/gtsfmcrzeb.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gthjlxcdjn.html

[R02] 变量赋值与使用
来源：http://dali.xinyue.icu/Article/details/gtsijwzoau.html

name="Tom"; echo "$name"
来源：http://dali.sufxvd.cn/Article/details/gthxesvisu.html

[R03] 只读变量
来源：http://dali.gogol.net.cn/Article/details/gtmthezqky.html

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gteapydhal.html

[R04] 位置参数
来源：http://dali.iojbl.cn/Article/details/gtsogfzqdu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gteqsztmek.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gtcgqnyfob.html

name="${1:-default}"
来源：http://dali.cucudq.cn/Article/details/gtpshlepwo.html

[R06] 判断命令是否存在
来源：http://dali.xylfe.cn/Article/details/gtaiwjumrz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtdfxokrth.html

[R07] if 判断文件
来源：http://dali.sufxvd.cn/Article/details/gtirybjivf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxbrckca.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gthnknnbdy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ydzc1.top/Article/details/gtwvkakvqj.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gtfsomspar.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgkexwas.html

[R10] 正则匹配
来源：http://dali.zhoulong.xyz/Article/details/gtjrhcxzbb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gtjdylebze.html

[R11] case 多分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrxhklic.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gtxdfbxdky.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gtuvckmymj.html

stop)  echo "停止" ;;
来源：http://dali.meibo888.top/Article/details/gteeulgcrp.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtzfmdnlkt.html

esac
来源：http://dali.pengpengdd.cyou/Article/details/gtmkllmzrv.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gtuvokghcz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yonumen.top/Article/details/gtwfcipfyx.html

[R13] for 计数循环
来源：http://dali.ehwqpu.com/Article/details/gtuglgvbmg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtqbnrbhyz.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gtdjfpigts.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtbzddqqrm.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtzmipihoe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwelhvkrx.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gtvkxoumxb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtzsxugwxd.html

[R17] 数组定义与取值
来源：http://dali.quarkkingdee.top/Article/details/gtqfmcwjbf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gtpoazrbfg.html

[R18] 遍历数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilhenuqe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gtbzbvobjm.html

[R19] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gtqqafsjpw.html

echo "${#arr[@]}"
来源：http://dali.quarkkingdee.top/Article/details/gtfkkpcbug.html

[R20] 关联数组（字典）
来源：http://dali.c1oappe.top/Article/details/gtxjxmneji.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gtfaymjoff.html

[R21] 字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gteldvdfsr.html

echo "${#s}"
来源：http://dali.xylfe.cn/Article/details/gtmxvlgsoq.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtlgjgcslf.html

echo "${s:0:5}"
来源：http://dali.wangshuangyany.cn/Article/details/gtqqtvhhxk.html

[R23] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtectlghsu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gtxppkrzoq.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtribmggwu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gtwbqyncjf.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtykqtokgk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gtftihckme.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gtatbemxjv.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gtefjvgxon.html

[R27] 算术展开
来源：http://dali.shanyushiyangkeji.top/Article/details/gttraghtdi.html

echo $((1 + 2 * 3))
来源：http://dali.sxryk.cn/Article/details/gtnbyvheae.html

[R28] 浮点运算
来源：http://dali.yangfankeji.com/Article/details/gtzcrqtbru.html

echo "scale=2; 10/3" | bc
来源：http://dali.kuanghao11.cn/Article/details/gtdwonohcl.html

[R29] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gtfqnqkovs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hfpthk.cn/Article/details/gtzoyodckk.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtsklnnmzd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gtcqxquzpc.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gtkyuomccv.html

f() { local x=1; echo "$x"; }
来源：http://dali.xziqi.cn/Article/details/gtpogmcsux.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gtiyrbognk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtbwmhuxet.html

[R33] 捕获错误并提示行号
来源：http://dali.zycfv.cn/Article/details/gtpjqvwfdh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gtfdiwsrxo.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gtlrhqmmdv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gtpkazyvai.html

[R35] 后台执行并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtboejrqhz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gtmiiozmxy.html

[R36] 并发执行多个任务
来源：http://dali.meibo888.top/Article/details/gtyygzkcpt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gtbboicjwr.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gtahagcwql.html

files=$(ls -1)
来源：http://dali.guannengcc.top/Article/details/gtkgzdteob.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gtfxlwydyk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj202588.top/Article/details/gtgbzkqdaj.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gtmkgthssc.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtvfyfnjes.html

[R40] 追加写日志
来源：http://dali.haohaochexian.top/Article/details/gtmjabvxqz.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gtfqvxylgj.html

[R41] 丢弃输出
来源：http://dali.hammf.cn/Article/details/gtufwxwfsk.html

cmd >/dev/null 2>&1
来源：http://dali.xziqi.cn/Article/details/gtsjhfcrlg.html

[R42] 输入重定向
来源：http://dali.kuanghao11.cn/Article/details/gtzwwcvgve.html

wc -l < a.txt
来源：http://dali.yueranfly.top/Article/details/gtwrlaosia.html

[R43] 按名字查找文件
来源：http://dali.xziqi.cn/Article/details/gtzwhxhofs.html

find . -name "*.log" -type f
来源：http://dali.smart0.xyz/Article/details/gtflnhpddb.html

[R44] 按修改时间查找
来源：http://dali.hfpthk.cn/Article/details/gtrkhpgrmx.html

find . -mtime -7 -type f
来源：http://dali.guowangkeji.top/Article/details/gtjdpiczgk.html

[R45] 批量删除
来源：http://dali.hnxiangtu.top/Article/details/gtywvfeqre.html

find . -name "*.tmp" -delete
来源：http://dali.jyoumei.cn/Article/details/gtvhjvdojq.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gtrpxtbbww.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gttdlacfes.html

[R47] sed 单行替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtahjmiaom.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtlsiziyeq.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gtfqzjfjlb.html

awk '{print $1, $3}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtrjlbsvpj.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtitgfduaq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gtlyeenbyh.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gtzbtfjilx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtumajkfiq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gtkvmmgere.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gtgpthfaqa.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gtkbtvfkxk.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gtfelfhtmo.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gtwnyuerso.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnxiangtu.top/Article/details/gtoanddsti.html

[R54] 比较两个文件
来源：http://dali.yuxming.cn/Article/details/gtuiiozhth.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gtxcldtzol.html

[R55] 压缩与解压
来源：http://dali.chenjidiqi.icu/Article/details/gtowyycndh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gtunfnnegj.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gtxjybgouw.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gtdyhmjzzp.html

[R57] 远程执行命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkhkehxa.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gttvsmbilm.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gtztuypfqe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ybcxt.top/Article/details/gtzjkkpbxc.html

[R59] 发 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtwmmyufzr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gtbvjbvfsk.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsarpcqqm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhongyouzk.top/Article/details/gtfqpgduqb.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtsuqaekex.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gtlsjsjoul.html

[R62] 找最占空间的文件
来源：http://dali.andypj.xyz/Article/details/gtizxhiqcq.html

du -ah . | sort -rh | head -10
来源：http://dali.sysykeji.top/Article/details/gthmkggrwa.html

[R63] 内存与进程
来源：http://dali.0kj1m.cn/Article/details/gtqreogamu.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpmqovie.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gtlkcgnebg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cucudq.cn/Article/details/gtuznogdhd.html

[R65] 查看端口占用
来源：http://dali.havefunace.top/Article/details/gtzmcsypbl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gtrxekqhox.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gtfuppuxrs.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gthrhysxeb.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gtmrvfqrer.html

openssl rand -hex 16
来源：http://dali.jqgfzy.top/Article/details/gtdzbvzbqf.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtmiplozhk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtmhfbbxok.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gttedwjwtk.html

head -c 16 /dev/urandom | base64
来源：http://dali.yongpay.top/Article/details/gtixowfjtt.html

[R70] 时间戳与互转
来源：http://dali.wangdashe.top/Article/details/gthvhmhfdc.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gtiamzmgfi.html

[R71] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtqgzaeicx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gtqkgqppws.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gtxokmndva.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtctlbitde.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gttxvtbmwf.html

split -l 1000 big.log part_
来源：http://dali.yonumen.top/Article/details/gtcegeipjr.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gtaujsbedy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gthrxlsqma.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gttijowdfa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gtciwadlrt.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtnnjiljfs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtkaapadvu.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gtwhdazlrx.html

read -rp "请输入: " ans
来源：http://dali.yvedp.cn/Article/details/gtgawiolph.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gtlbgvqyxd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtjvzehixy.html

[R79] 解析命令行选项
来源：http://dali.iojbl.cn/Article/details/gtnxbdrroe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gtopiepklw.html

[R80] 查看脚本执行耗时
来源：http://dali.aibaodan.cn/Article/details/gtidbdvbhc.html

time ./run.sh
来源：http://dali.sysykeji.top/Article/details/gtrcdfgyrd.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtuvqmohev.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtrtkuijlg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtncgdmtnp.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtahvftjtn.html

#include <stdio.h>
来源：http://dali.birdmap.top/Article/details/gtvcgonekj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcdorljag.html

[S02] C：变量与格式化输出
来源：http://dali.tian-w.cn/Article/details/gteegpunvy.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gtnqvpusfp.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gtfiiwgrdj.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gtlrnmrocv.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gtwrpafhbt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gtkryilgkg.html

[S05] C：字符串长度
来源：http://dali.meibo888.top/Article/details/gthtvujusy.html

strlen(s)
来源：http://dali.xuanzx.com/Article/details/gtktwgrzjn.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gtahhiwzbp.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtacjredod.html

[S07] C：数组遍历求和
来源：http://dali.zhoulong.xyz/Article/details/gtawagyrkp.html


<!-- 参考信息 -->