代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gtptbrktfp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gtmzqdiwpk.html

[Q43] 标量子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtguzabcvp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.316326.xyz/Article/details/gtgsivmvph.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gtcdxcvjrr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gtzavbmggz.html

[Q45] EXISTS 判断存在
来源：http://dali.ybcxt.top/Article/details/gtkrbejnmw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticqhsvby.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gtfhxkrvwi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtojrvhqkb.html

[Q47] 与平均值比较
来源：http://dali.cucudq.cn/Article/details/gtliyqwjtn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.havefunace.top/Article/details/gtvchfiajm.html

[Q48] CTE 公用表表达式
来源：http://dali.yanxiufei.cn/Article/details/gtcmvyneol.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxuanxn.top/Article/details/gtiocbnhlk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gtqrbercur.html

[Q49] 更新单行
来源：http://dali.shzxlz.cn/Article/details/gtycknkxbv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gtnejklqvk.html

[Q50] 批量更新
来源：http://dali.sysykeji.top/Article/details/gthmhgtupd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtnyeqzvhj.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfvukiva.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgfzy.top/Article/details/gthtegdupz.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gthstohmyd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gthpfgxkbr.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gtftrdbbxz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtlleoanbh.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gtdbirrkqo.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gtsddxayce.html

[Q55] 排名（并列占位）
来源：http://dali.sufxvd.cn/Article/details/gtonzavgts.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtxkypdwnn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhixingplan.top/Article/details/gtnbzkibvo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtjygmyodp.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gterayqbnq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.birdmap.top/Article/details/gthsqikuvk.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gtnizlgqen.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtstfrgftd.html

[Q59] 分组内累计
来源：http://dali.c1oappe.top/Article/details/gtlitcjbrv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gteeenvkvg.html

[Q60] 取上一行 / 下一行
来源：http://dali.bjfxy.top/Article/details/gtprqpanbb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxinkj.top/Article/details/gtfafxjcpa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxqgsnpn.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gtgnxkhlnc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtziuxldzl.html

[Q62] 分组占比
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagcqpgvj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtnajfxoco.html

[Q63] 开启事务
来源：http://dali.hongshengwenyu.top/Article/details/gtwyvhxvps.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gtlykxillz.html

[Q64] 提交事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudridzgw.html

COMMIT;
来源：http://dali.0kj1m.cn/Article/details/gtdqusytxp.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gtvgopsifk.html

ROLLBACK;
来源：http://dali.yj20258.top/Article/details/gtcjzgkite.html

[Q66] 行锁查询
来源：http://dali.zycfv.cn/Article/details/gtsnhgxznl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.316326.xyz/Article/details/gtvidjbwfd.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gtqcergusd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gtzydrlgvd.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gtkvuinxuv.html

SAVEPOINT sp1;
来源：http://dali.dianchejie.cn/Article/details/gtavbgkanr.html

ROLLBACK TO sp1;
来源：http://dali.cucudq.cn/Article/details/gtaoinuicb.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gtxgitogdp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gtmjtxhaob.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaerqyjua.html

ANALYZE TABLE users;
来源：http://dali.meibo888.top/Article/details/gthktciojq.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gtmbrazsrd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangshuangyany.cn/Article/details/gtzxwnreec.html

[Q72] 查看索引
来源：http://dali.ivvv.top/Article/details/gtlkgbowad.html

SHOW INDEX FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtbwuvlzwi.html

[Q73] 查看表状态
来源：http://dali.chenjidiqi.icu/Article/details/gtwhgbfixy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jiagoushi.top/Article/details/gtmkxlavwf.html

[Q74] 强制使用索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxxsfdmu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gzhubu.top/Article/details/gtulkkzthx.html

[Q75] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtmecnytae.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtzoormoqk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.9152youxi.cn/Article/details/gtpaqakxgx.html

[Q76] 按天统计
来源：http://dali.vqdsnc.cn/Article/details/gtfoaxygsl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gtnfmgkuxs.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gtrakpajmb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gtzzseqbxk.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gtywdmfgbi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daxiang520.top/Article/details/gtcojjcskv.html

[Q79] 字符串拼接
来源：http://dali.meibo888.top/Article/details/gtkqdbhvoo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ybcxt.top/Article/details/gtyaicmbqt.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gtqkpnymdp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtfnxddcdz.html

[Q81] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtebhqyvfw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtislzines.html

[Q82] 字符长度与字节长度
来源：http://dali.zhengqikj.top/Article/details/gtascyvpnx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtzvyieifp.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtwrvbkbkp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtkkuseinp.html

[Q84] 去除首尾空格
来源：http://dali.xylfe.cn/Article/details/gtnyxiutkt.html

SELECT TRIM(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtxydekzyh.html

[Q85] 数值取整
来源：http://dali.jlsjyb.cn/Article/details/gtmxcbwqku.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gtbaglhlah.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgfzy.top/Article/details/gtcliduzpv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guowangkeji.top/Article/details/gtgqagmbpj.html

[Q87] JSON 字段做条件
来源：http://dali.nanxinkj.top/Article/details/gtaaueahvh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gtdqygxoxf.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gtfvfhtvbc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gtavxaoebn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gtdodnukmk.html

[Q89] 判断表是否存在
来源：http://dali.aibaodan.cn/Article/details/gtwyspzvdf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gtozupipaf.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gtvszccwol.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gtkdnryibc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtyuqlgeen.html

R. Bash 专题
来源：http://dali.nwbrower.top/Article/details/gtqylaajgl.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtecdidyyi.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gthbwaimfj.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gtckvzxeur.html

set -euo pipefail
来源：http://dali.hammf.cn/Article/details/gtyqcwjpbb.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gtcefqcnmo.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gtogkruekv.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gtbasnnnwl.html

readonly PI=3.14
来源：http://dali.feifeiyinyue.top/Article/details/gtkqpzgtni.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpaqtlznh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gtpxcacyrl.html

[R05] 参数默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdmkufts.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gtuybjepnr.html

[R06] 判断命令是否存在
来源：http://dali.svipenyu.cn/Article/details/gtttjcmgqn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gthrcinekt.html

[R07] if 判断文件
来源：http://dali.yanxiufei.cn/Article/details/gtzlfmtbkx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aizwys.cn/Article/details/gtulatadgr.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gtfbmdouir.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtkryefxhp.html

[R09] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalhxuepr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gtdpcqfwje.html

[R10] 正则匹配
来源：http://dali.ydzc1.top/Article/details/gtodbjfyny.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gthcrwcrok.html

[R11] case 多分支
来源：http://dali.yueranfly.top/Article/details/gtzpjypfpk.html

case "$1" in
来源：http://dali.tianlin.xyz/Article/details/gtouogfzua.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtnnahrmrx.html

stop)  echo "停止" ;;
来源：http://dali.yangfankeji.com/Article/details/gtnogyqlaf.html

*)     echo "未知命令" ;;
来源：http://dali.fzhhl.top/Article/details/gthlyhuaka.html

esac
来源：http://dali.9152youxi.cn/Article/details/gtqamvygek.html

[R12] for 遍历文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkwqvfnm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gtrwrauvqn.html

[R13] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtwejgexdk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtnzzmiyqu.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtqoljakis.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtojehbvtt.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtugxenutb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gtkfaskfit.html

[R16] until 等待条件
来源：http://dali.chenlongwang.top/Article/details/gtwktrpjct.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtuofewwrg.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gtngnijnqc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhongyouzk.top/Article/details/gtlvjbisbv.html

[R18] 遍历数组
来源：http://dali.yanxiufei.cn/Article/details/gtsinnxhci.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.9152youxi.cn/Article/details/gtkrzmgecv.html

[R19] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gttvkqnjqs.html

echo "${#arr[@]}"
来源：http://dali.sweek.top/Article/details/gtpwkkrvay.html

[R20] 关联数组（字典）
来源：http://dali.ybcxt.top/Article/details/gtdtcpijcd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aizwys.cn/Article/details/gtaagsjudd.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gtwcnusefi.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gtkqytvywr.html

[R22] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtmelxdbqq.html

echo "${s:0:5}"
来源：http://dali.tanke756.top/Article/details/gtfufhjvpj.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtvoemokce.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.birdmap.top/Article/details/gtsczknuyj.html

[R24] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtepbclrjp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuxming.cn/Article/details/gtvafjzspf.html

[R25] 去后缀 / 去前缀
来源：http://dali.birdmap.top/Article/details/gttodqceck.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gtatbncfkf.html

[R26] 命令替换
来源：http://dali.cheryme.top/Article/details/gttehtxhxz.html

now=$(date +%F); echo "$now"
来源：http://dali.hongshengwenyu.top/Article/details/gtayopwjao.html

[R27] 算术展开
来源：http://dali.tian-w.cn/Article/details/gtxxbzzwhx.html

echo $((1 + 2 * 3))
来源：http://dali.hammf.cn/Article/details/gtbnapmtcb.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gtiadcuftw.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzilsbwws.html

[R29] 定义函数
来源：http://dali.yueranfly.top/Article/details/gtscrafwyh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jyoumei.cn/Article/details/gtpivkqaqw.html

[R30] 函数返回状态码
来源：http://dali.sxryk.cn/Article/details/gtrxdemjov.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gtxzbmaojp.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gtdldbpcxr.html

f() { local x=1; echo "$x"; }
来源：http://dali.meibo888.top/Article/details/gtizunuyzl.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtmkbopjuk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtvxbiatxj.html

[R33] 捕获错误并提示行号
来源：http://dali.fengsongda.top/Article/details/gtfjfgsxjk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ivvv.top/Article/details/gtxpozoxof.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gtwvznffwq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbompkxad.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gthewfxepu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlxefjlc.html

[R36] 并发执行多个任务
来源：http://dali.cheryme.top/Article/details/gturuvrhwf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hongshengwenyu.top/Article/details/gtnkoqibht.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gtjgjslmei.html

files=$(ls -1)
来源：http://dali.jiagoushi.top/Article/details/gtxvsmwwsu.html

[R38] 管道串联
来源：http://dali.ehwqpu.com/Article/details/gtylbqjfvl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gtyopqqcle.html

[R39] 重定向标准输出与错误
来源：http://dali.hywenlv.cn/Article/details/gtxlvkvvac.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtfbuqindl.html

[R40] 追加写日志
来源：http://dali.hnqzz.top/Article/details/gtrcwjygoe.html

echo "log" >> out.log
来源：http://dali.daxiang520.top/Article/details/gtagmjhofh.html

[R41] 丢弃输出
来源：http://dali.guowangkeji.top/Article/details/gtufjtrldh.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gtavqphhbu.html

[R42] 输入重定向
来源：http://dali.tianlin.xyz/Article/details/gtyrjvnejg.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gtemldpltm.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gtyayuwgzf.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gtetworcdl.html

[R44] 按修改时间查找
来源：http://dali.zdqjudy.top/Article/details/gtnkqtwogt.html

find . -mtime -7 -type f
来源：http://dali.xuanzx.com/Article/details/gtdwtkdxdo.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gtzbsmffmm.html

find . -name "*.tmp" -delete
来源：http://dali.svipenyu.cn/Article/details/gtgcdrbtcd.html

[R46] 递归替换文件内容
来源：http://dali.havefunace.top/Article/details/gtdsageqzt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gtscotfxvp.html

[R47] sed 单行替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzwbnhci.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrfgaaea.html

[R48] awk 取指定列
来源：http://dali.tian-w.cn/Article/details/gtcqluumao.html

awk '{print $1, $3}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtrddvxbpd.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gtulbzjjfk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gtgrvfixqk.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gtmhbekzdt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtujkjsqso.html

[R51] 排序去重取前几
来源：http://dali.pycfn.com/Article/details/gtfsqijwmt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gtjenxtgrd.html

[R52] 统计行数
来源：http://dali.jinqigufen.top/Article/details/gtfybjjfsm.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gtwymkfnvd.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gtwwqqnsmr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daxiang520.top/Article/details/gtgkdonwrj.html

[R54] 比较两个文件
来源：http://dali.ehwqpu.com/Article/details/gtefbtsbhq.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gtxmpaeykg.html

[R55] 压缩与解压
来源：http://dali.aibaodan.cn/Article/details/gtvphalyxc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aibaodan.cn/Article/details/gtoiwiipsx.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gtahtgkfoz.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gtcekvyjmf.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gtytgotjcy.html

ssh user@host 'uptime'
来源：http://dali.ivvv.top/Article/details/gtalumusoh.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gtvegzvkuw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtxqeqin.html

[R59] 发 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtdlzbecln.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cqqwz.cn/Article/details/gtcnhlryxo.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtwpaknxfe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.andypj.xyz/Article/details/gtgcharkio.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gtuzxfsicn.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gtmviuskzv.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gttokevaft.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258888.top/Article/details/gtodlfabbu.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gtwihbbeen.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gtzkgtpzga.html

[R64] 结束进程
来源：http://dali.yuxming.cn/Article/details/gteokddyzz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jyoumei.cn/Article/details/gtznwcbbnd.html

[R65] 查看端口占用
来源：http://dali.jyoumei.cn/Article/details/gtggwnipfg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gttcijezke.html

[R66] 定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwdvbgyk.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gtmlchsjez.html

[R67] 生成随机十六进制串
来源：http://dali.gotoacloud.top/Article/details/gtwwgucmiz.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gtjukloykl.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gtpskyplxx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yvedp.cn/Article/details/gtbyaqbsxs.html

[R69] 生成随机密码
来源：http://dali.ybcxt.top/Article/details/gtbuextcpc.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtnxjyawtz.html

[R70] 时间戳与互转
来源：http://dali.xuetiantiany.cn/Article/details/gtxmjlzoke.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gtpoyqefwa.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gthkqknbmb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gtcpunufhw.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gtuofuwkzs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtoivahhov.html

[R73] 分割大日志
来源：http://dali.c1oappe.top/Article/details/gtxrcjjxqv.html

split -l 1000 big.log part_
来源：http://dali.fzhhl.top/Article/details/gtjbmxyzxn.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gtegpnvlwn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gtboyurydy.html

[R75] 导出环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtbmmqpfnh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gtpsfaopbr.html

[R76] 使用临时文件
来源：http://dali.hnqzz.top/Article/details/gtzujxiexc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtvhjpljen.html

[R77] 读取用户输入
来源：http://dali.nanxuanxn.top/Article/details/gtfrxvtpwq.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gtivdbbdsh.html

[R78] 交互式菜单
来源：http://dali.yongpay.top/Article/details/gtnoykzgeg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gtiuailxbg.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gtbnhqirtv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxuanxn.top/Article/details/gttvdrjcab.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gtpwataydd.html

time ./run.sh
来源：http://dali.sxryk.cn/Article/details/gtotionwdb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtfcpytkpw.html

S. C / C++ 专题
来源：http://dali.yongpay.top/Article/details/gttrxrpdyt.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxtmmqbak.html

[S01] C：Hello World
来源：http://dali.yvedp.cn/Article/details/gtxcjrmwci.html

#include <stdio.h>
来源：http://dali.yongpay.top/Article/details/gtjhpkroow.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gtfuvabqts.html

[S02] C：变量与格式化输出
来源：http://dali.daxiang520.top/Article/details/gtuphotqrd.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gtkjncmojv.html

[S03] C：读入整数
来源：http://dali.hnxiangtu.top/Article/details/gtqouoqjtj.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfukaoivi.html

[S04] C：字符串复制
来源：http://dali.daxiang520.top/Article/details/gtnuydklzj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gtzekrqwng.html

[S05] C：字符串长度
来源：http://dali.xinyue.icu/Article/details/gtxpwvamus.html

strlen(s)
来源：http://dali.dashuyun.cn/Article/details/gtygytwhsl.html

[S06] C：字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtmjlcvgtb.html

strcmp(a, b) == 0
来源：http://dali.cqqwz.cn/Article/details/gtiyttgota.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gtdncmaldl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gthhdxympo.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gtqavlcopn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.birdmap.top/Article/details/gtqwzdycjl.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gtuizseryc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gtqfdtxbde.html

[S10] C：指针与解引用
来源：http://dali.sysykeji.top/Article/details/gtqlkbniai.html

int *p = &a;  *p = 5;
来源：http://dali.sweek.top/Article/details/gtdxmggwni.html

[S11] C：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtvlmzgugj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258888.top/Article/details/gtbjdqhkcv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cashguo.top/Article/details/gtnzgnrtcb.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwwwrhjs.html

[S12] C：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtfaxnebfz.html


<!-- 参考信息 -->