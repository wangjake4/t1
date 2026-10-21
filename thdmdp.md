代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gtbsneuicw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gtvdqsvkab.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxinkj.top/Article/details/gtwlqjlvnc.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtasvtfkcy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gtjobjmdbt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gtimousgrt.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gtxiwwdltu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnrgcxwc.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gtbjsaavqk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jyoumei.cn/Article/details/gtnxzzlkrl.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gtomxggtyk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtozsschvz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorzythrs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtxcjnpmen.html

[Q47] 与平均值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhuhpdht.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gtbdpzmgor.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gtdaokleem.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hywenlv.cn/Article/details/gtjpjpsgop.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gtrentqbgp.html

[Q49] 更新单行
来源：http://dali.smart0.xyz/Article/details/gtmfgkecfd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtzareojsu.html

[Q50] 批量更新
来源：http://dali.tanke756.top/Article/details/gtloqnssyf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.meibo888.top/Article/details/gtqlehhner.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gtszsnorca.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gtbrteqyee.html

[Q52] 删除指定行
来源：http://dali.guannengcc.top/Article/details/gtdzjskjtx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtgzbloqje.html

[Q53] 按条件删除
来源：http://dali.bjfxy.top/Article/details/gtvqouljyp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtyrvtokqs.html

[Q54] 清空表
来源：http://dali.zhiwuduotai.top/Article/details/gtzrqdzfzp.html

TRUNCATE TABLE logs;
来源：http://dali.hnqzz.top/Article/details/gtsvmphkuk.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gtuaebpklb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtnvpqpjzp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gtwalcsceb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtvlzwxcwo.html

[Q57] 行号
来源：http://dali.sweek.top/Article/details/gtzekzxlkl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtktoofgff.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gtzjpxdpwd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtjjndgetz.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gtuevapjyi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtyvyiufnn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gtfrxixzan.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gtlakbwjnw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tanke756.top/Article/details/gtkzfkwham.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gtkvgznxqq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtjswpfibg.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gtxwrupsiq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtmpfnenix.html

[Q63] 开启事务
来源：http://dali.gogol.net.cn/Article/details/gtdvhnnqrs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fengsongda.top/Article/details/gtnfprxnsy.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gtanvnmgjl.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtrjzredsc.html

[Q65] 回滚事务
来源：http://dali.xuanzx.com/Article/details/gtbhqfomtr.html

ROLLBACK;
来源：http://dali.quarkkingdee.top/Article/details/gtfukmtieq.html

[Q66] 行锁查询
来源：http://dali.aibaodan.cn/Article/details/gtedkhyuhs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gtgidsgwhd.html

[Q67] 设置隔离级别
来源：http://dali.shangyingyoupin.top/Article/details/gtywsuuiwa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.svipenyu.cn/Article/details/gtqjhkeuuh.html

[Q68] 保存点
来源：http://dali.zdqjudy.top/Article/details/gttfzqyndw.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gtppggsgwd.html

ROLLBACK TO sp1;
来源：http://dali.yangfankeji.com/Article/details/gtqetywvjt.html

[Q69] 查看执行计划
来源：http://dali.guowangkeji.top/Article/details/gtbyltucok.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gtzuvibdcr.html

[Q70] 更新统计信息
来源：http://dali.haohaochexian.top/Article/details/gtsqyyzbdr.html

ANALYZE TABLE users;
来源：http://dali.nanxuanxn.top/Article/details/gtooygaykl.html

[Q71] 查看建表语句
来源：http://dali.andypj.xyz/Article/details/gtmfpgjwrc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gtaregkehm.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gtteqwhcns.html

SHOW INDEX FROM users;
来源：http://dali.cucudq.cn/Article/details/gtqwmuqmfr.html

[Q73] 查看表状态
来源：http://dali.gogol.net.cn/Article/details/gtwwputcwl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gtzmhctdxz.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtdmhbqpoo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gtmfdaivnj.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtxbenahea.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.meibo888.top/Article/details/gtszvdsege.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gtiqjzljiw.html

[Q76] 按天统计
来源：http://dali.pycfn.com/Article/details/gtzgenjryy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gttvkvgtjz.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gtvwkbcpav.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yongpay.top/Article/details/gthqiqtpwp.html

[Q78] 当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gthexwagpb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbaehqcdp.html

[Q79] 字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gtojeimlkq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gtarhoxboe.html

[Q80] 字符串截取
来源：http://dali.zhengqikj.top/Article/details/gtjsgpdqcl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtiayttxxe.html

[Q81] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtfhpzqhhk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtqtnvkblf.html

[Q82] 字符长度与字节长度
来源：http://dali.snrcjt.cn/Article/details/gtkgocypwh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gturmyngsn.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtjjccbrjk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtfjsiinbo.html

[Q84] 去除首尾空格
来源：http://dali.jlsjyb.cn/Article/details/gtceokiqqj.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtpokyygwp.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gtktcwjkdx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hywenlv.cn/Article/details/gtdkywirtl.html

[Q86] 读取 JSON 字段
来源：http://dali.cdnleiting.top/Article/details/gtqbsjbmgs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gtmlpukbvb.html

[Q87] JSON 字段做条件
来源：http://dali.yvedp.cn/Article/details/gtthbyhjrd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gtsrlhjyys.html

[Q88] 行转列（条件聚合）
来源：http://dali.hammf.cn/Article/details/gtipmzxgbv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhiwuduotai.top/Article/details/gtgiuechav.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gtyvvucqof.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gtdosmmdjg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtkyaurlip.html

[Q90] 生成序号列
来源：http://dali.gotoacloud.top/Article/details/gtsyozwlqq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yonumen.top/Article/details/gtrjtdzgus.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtyxuihugg.html

R. Bash 专题
来源：http://dali.guowangkeji.top/Article/details/gtcvnwgtgl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpxnnmjwc.html

[R01] shebang 与严格模式
来源：http://dali.jiagoushi.top/Article/details/gtmzfxbcgy.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gtgvrkvcuv.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gtmaewzfqt.html

[R02] 变量赋值与使用
来源：http://dali.xziqi.cn/Article/details/gtcgtbbjmo.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gtgpryovfv.html

[R03] 只读变量
来源：http://dali.guannengcc.top/Article/details/gtqqojtpoh.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gtdmmkhydz.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gthbgbvlwe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangshuangyany.cn/Article/details/gtfowgpzae.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gtgvwtklrr.html

name="${1:-default}"
来源：http://dali.hnxiangtu.top/Article/details/gtwubceqnd.html

[R06] 判断命令是否存在
来源：http://dali.dianchejie.cn/Article/details/gtsxbgcdwi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtppejcnup.html

[R07] if 判断文件
来源：http://dali.meibo888.top/Article/details/gtipuulnox.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yangfankeji.com/Article/details/gtgiggnsfq.html

[R08] 数值比较
来源：http://dali.dianchejie.cn/Article/details/gtsyqoolww.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gtdqnockmu.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtbeysllli.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gtolknmzxl.html

[R10] 正则匹配
来源：http://dali.zhongyouzk.top/Article/details/gtuwdibalj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxinkj.top/Article/details/gtskuacnoj.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gtwmtkrkrd.html

case "$1" in
来源：http://dali.sweek.top/Article/details/gtwpdyzhkt.html

start) echo "启动" ;;
来源：http://dali.cashguo.top/Article/details/gtodjviatu.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtxppldwbi.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtzxwvgeue.html

esac
来源：http://dali.aizwys.cn/Article/details/gtgbvquiwz.html

[R12] for 遍历文件
来源：http://dali.mhx1999.top/Article/details/gtnywwdswn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gtkxtujhgj.html

[R13] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gtczdydgve.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gtylvgzxzq.html

[R14] C 风格 for
来源：http://dali.smart0.xyz/Article/details/gtpexioder.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtqixsevsc.html

[R15] while 逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtijfsbyiy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gttyvuamrf.html

[R16] until 等待条件
来源：http://dali.zhongyouzk.top/Article/details/gtffxzsgkb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gtrklkpsuq.html

[R17] 数组定义与取值
来源：http://dali.yangfankeji.com/Article/details/gtfvczwzms.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ppjwa.cn/Article/details/gtfxcbdhzz.html

[R18] 遍历数组
来源：http://dali.jianghu66.top/Article/details/gtcivtlmcx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fzhhl.top/Article/details/gtqrizbpxv.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtpuutgulg.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtjfqkecwq.html

[R20] 关联数组（字典）
来源：http://dali.ppjwa.cn/Article/details/gtynipbald.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gtbavrujdm.html

[R21] 字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtblhvfcsl.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gtfecpkndt.html

[R22] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtkmkojbzj.html

echo "${s:0:5}"
来源：http://dali.jlsjyb.cn/Article/details/gtaeicpdip.html

[R23] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtejooyixn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujgozqau.html

[R24] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuboxyule.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gtkcpbxxda.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gtnwncbvkd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gtdihndarz.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtycyscmrr.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gtpcqtghrf.html

[R27] 算术展开
来源：http://dali.yangfankeji.com/Article/details/gtydpqojaw.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtukiwjpie.html

[R28] 浮点运算
来源：http://dali.tian-w.cn/Article/details/gtrmuddysc.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gtapoazvpb.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtivawxmar.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gtxmmyawez.html

[R30] 函数返回状态码
来源：http://dali.dashuyun.cn/Article/details/gtmcoiuxpc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.andypj.xyz/Article/details/gtbikpyddb.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gtmneoiwog.html

f() { local x=1; echo "$x"; }
来源：http://dali.jlsjyb.cn/Article/details/gtetiesjpc.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gtalzvbpqj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gtsancqbzk.html

[R33] 捕获错误并提示行号
来源：http://dali.ppjwa.cn/Article/details/gtsdqeopdm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gtzwtyltiz.html

[R34] 退出时清理
来源：http://dali.svipenyu.cn/Article/details/gtngujmgyx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gttqfsoknc.html

[R35] 后台执行并等待
来源：http://dali.hysaishi.cn/Article/details/gtyimnvndo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gtphaareic.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gtcyltferx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtzqkkkozs.html

[R37] 把输出赋给变量
来源：http://dali.chenzaomai.com/Article/details/gteqfgaxst.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gtxicnxyio.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gtmprjkemp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xinyue.icu/Article/details/gtpsvlqidr.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gthsbppzdl.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtigutjicw.html

[R40] 追加写日志
来源：http://dali.smart0.xyz/Article/details/gtafwmdent.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gtovuhxswo.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gtbjeiewwy.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gtbjmxbygy.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gttlinujjt.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gtfpubefgm.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosslzvuk.html

find . -name "*.log" -type f
来源：http://dali.haohaochexian.top/Article/details/gtxyyfknlx.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gtbtzmnbfc.html

find . -mtime -7 -type f
来源：http://dali.kuanghao11.cn/Article/details/gtygnxntdt.html

[R45] 批量删除
来源：http://dali.316326.xyz/Article/details/gtqxqhevht.html

find . -name "*.tmp" -delete
来源：http://dali.tanke756.top/Article/details/gtepmijglf.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gtuwtcqvdr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yanxiufei.cn/Article/details/gttsvwhtei.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gttnxuztyl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtkoiugtjc.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtaumbbbrj.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtxfqyoiqn.html

[R49] awk 带条件
来源：http://dali.redwolf501.top/Article/details/gtflatwxpu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gttopjglrj.html

[R50] awk 求和
来源：http://dali.redwolf501.top/Article/details/gtbixyrclc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtlcgziqvz.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqguznho.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gtlkniqfgp.html

[R52] 统计行数
来源：http://dali.cashguo.top/Article/details/gtoiqxpzgo.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gttqlygetp.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gttzlskiwy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gtrzendqsg.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gtgokduohz.html

diff a.txt b.txt
来源：http://dali.tanke756.top/Article/details/gteexzythe.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gtqkuqdoeo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gtlosxnkgl.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gtnylcojeg.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gtqafcduxd.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtuvijuein.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gtldpamtpw.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gtvtrsphfu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dashuyun.cn/Article/details/gtxstovoqw.html

[R59] 发 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtizepjrmx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gtdzghpalb.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtzrfqqckm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenzaomai.com/Article/details/gtmszatljj.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gtvmdhcdfr.html

df -h;  du -sh *
来源：http://dali.c1oappe.top/Article/details/gtpluqddov.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gtayjrizcr.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gtutxiyvlp.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gtatyguydh.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gtjyjpwqrw.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gtbonxusir.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daria6918.cn/Article/details/gtbpsdkhba.html

[R65] 查看端口占用
来源：http://dali.hnxiangtu.top/Article/details/gtgwxuneps.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gtjbhvlefc.html

[R66] 定时任务
来源：http://dali.yj202588.top/Article/details/gtoyfjjjbk.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gtpsjjavxs.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gtrmnccsql.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gtwlnnaoav.html

[R68] 计算文件校验值
来源：http://dali.birdmap.top/Article/details/gtqyzrndgv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gotoacloud.top/Article/details/gtxqjdnvgg.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gtnxfcurkg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqudhyuul.html

[R70] 时间戳与互转
来源：http://dali.jqgfzy.top/Article/details/gtmojecxxf.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gtzzwnizzu.html

[R71] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtuncjikce.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gtuvolsdec.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gtnxxcaiky.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtcboxodqd.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gtxmjkmqrf.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtpypmzqmd.html

[R74] 批量重命名
来源：http://dali.hfpthk.cn/Article/details/gtbxeayfog.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gtrkufqerk.html

[R75] 导出环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtguqupssl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gtskngxphv.html

[R76] 使用临时文件
来源：http://dali.snrcjt.cn/Article/details/gtrnhnobjc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtnbapwfcf.html

[R77] 读取用户输入
来源：http://dali.hnxiangtu.top/Article/details/gtrlihfawl.html

read -rp "请输入: " ans
来源：http://dali.hysaishi.cn/Article/details/gtgbizddqf.html

[R78] 交互式菜单
来源：http://dali.cqqwz.cn/Article/details/gtposmmyzd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gtdhevmafj.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gtwxoebdvr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gtkgyzjlon.html

[R80] 查看脚本执行耗时
来源：http://dali.jlsjyb.cn/Article/details/gtshulvsgt.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gtvlxxvrnw.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtywlxvrge.html

S. C / C++ 专题
来源：http://dali.iojbl.cn/Article/details/gtdufzlosz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlbcsowsq.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gttfbcqzvh.html

#include <stdio.h>
来源：http://dali.9152youxi.cn/Article/details/gtulxzugkp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ydzc1.top/Article/details/gtnebuwslb.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gtdwkyqkxa.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gtfluyorwd.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gtzemkcwip.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gtwehcfxdx.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gtcufgjwwb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xylfe.cn/Article/details/gtiovoplrz.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtuebveiak.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gtwosundtk.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gtxqcwxefz.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gtflylxcuo.html

[S07] C：数组遍历求和
来源：http://dali.nanxinkj.top/Article/details/gtkonyuvbk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gtvcasrggo.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkykvwey.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gteipfgjli.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gtgpxvztrw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shzxlz.cn/Article/details/gtnmrqlmrr.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gtszbgklgj.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gtcvzgazoe.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtfcmzezrn.html


<!-- 参考信息 -->