代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.jlsjyb.cn/Article/details/gtnhfbzylh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.birdmap.top/Article/details/gtrzslnksk.html

[Q43] 标量子查询
来源：http://dali.jiagoushi.top/Article/details/gtjshdzrnj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tian-w.cn/Article/details/gtgoawjgvs.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gtyrcgjqud.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhtcyryu.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gtccmpdtdr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gtangliycw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gtuiafjuor.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtpbdtivnv.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gtomxiiovi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gtxplfosru.html

[Q48] CTE 公用表表达式
来源：http://dali.zhengqikj.top/Article/details/gtvwaieobs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yanxiufei.cn/Article/details/gtxuiehpvi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gtpcakcuhz.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gtfauqvjmw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtmcpqppmj.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gtfqtazjkv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gtmbjcszdu.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gtynpnxceh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqusixfpn.html

[Q52] 删除指定行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevcztcww.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtelauzevp.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gtvmeauvnf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtumpebykn.html

[Q54] 清空表
来源：http://dali.redwolf501.top/Article/details/gtbsnsbmjh.html

TRUNCATE TABLE logs;
来源：http://dali.aizwys.cn/Article/details/gtgzqjrxvh.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gtuijzinpf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtyhtisuow.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fzhhl.top/Article/details/gtsjefjfxr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gtbsigekmy.html

[Q57] 行号
来源：http://dali.ydzc1.top/Article/details/gthbygaahd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtjnkfxkuf.html

[Q58] 累计求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozefhwqf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gtuddmmefl.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtmwnleaua.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtgsbxljhn.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gtelrqlkay.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sxryk.cn/Article/details/gtjbukthuy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtdffqpkrc.html

[Q61] 移动平均
来源：http://dali.hnxiangtu.top/Article/details/gtfglkstff.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtjoiplycx.html

[Q62] 分组占比
来源：http://dali.chenlongwang.top/Article/details/gtkvkaduyn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtcwddhgva.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gtvzgorqla.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yvedp.cn/Article/details/gtkhrewswb.html

[Q64] 提交事务
来源：http://dali.nwbrower.top/Article/details/gtxildsctc.html

COMMIT;
来源：http://dali.chenlongwang.top/Article/details/gtpsjcjwqx.html

[Q65] 回滚事务
来源：http://dali.yvedp.cn/Article/details/gtomkztklo.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gtimyvvqto.html

[Q66] 行锁查询
来源：http://dali.kuanghao11.cn/Article/details/gtzcsnpbwq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gttshyqtoj.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gtxavccmsl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangshuangyany.cn/Article/details/gtfwzhvhyp.html

[Q68] 保存点
来源：http://dali.nanxinkj.top/Article/details/gtsoaxzggf.html

SAVEPOINT sp1;
来源：http://dali.aizwys.cn/Article/details/gtpynnbbvo.html

ROLLBACK TO sp1;
来源：http://dali.daxiang520.top/Article/details/gtgqootxrv.html

[Q69] 查看执行计划
来源：http://dali.shzxlz.cn/Article/details/gteavifkgr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gtsysbsdlm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gtdxmbkiuc.html

ANALYZE TABLE users;
来源：http://dali.meibo888.top/Article/details/gtxhytydxb.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gtagtjncpg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gtgztbkdin.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaauqezzj.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuwlugxa.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gtcqdczolq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gtitlblpue.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtrmhvpjcn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aibaodan.cn/Article/details/gtjgubksmf.html

[Q75] 日期格式化
来源：http://dali.yonumen.top/Article/details/gtdlnrwhai.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtrdygwplg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.feifeiyinyue.top/Article/details/gtrxcboxll.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gtvzvnfuot.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.redwolf501.top/Article/details/gtotlezvpa.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gtxjxupstc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yongpay.top/Article/details/gtogsinkwf.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtvsbpsfaw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhoulong.xyz/Article/details/gttoylmzqy.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtkpnmivjh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xylfe.cn/Article/details/gtxhhbzhry.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gtqvienftt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtngsbuvty.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtspszhsil.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gtibyzeogc.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gtpbwogtuw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtvkxqtkgf.html

[Q83] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtvvdqpwzb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gthztuuaeu.html

[Q84] 去除首尾空格
来源：http://dali.xylfe.cn/Article/details/gtxzrhsbxn.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtfwcalfnj.html

[Q85] 数值取整
来源：http://dali.hysaishi.cn/Article/details/gtqewoddfj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.havefunace.top/Article/details/gtoeoikhmx.html

[Q86] 读取 JSON 字段
来源：http://dali.svipenyu.cn/Article/details/gtexwgwhld.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gtpgbudghc.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gtvdbmrdgs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nwbrower.top/Article/details/gtbtvniziu.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gtgnfqdlkm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhiwuduotai.top/Article/details/gtdkrchkof.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yvedp.cn/Article/details/gtvnpzghrl.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gtuwcoxama.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gtliqdyakv.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gtvdpwmams.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xinyue.icu/Article/details/gtdjvlebij.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtaprlocwa.html

R. Bash 专题
来源：http://dali.meibo888.top/Article/details/gtuyzghgjh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkdvsxsky.html

[R01] shebang 与严格模式
来源：http://dali.sysykeji.top/Article/details/gtmzceptia.html

#!/usr/bin/env bash
来源：http://dali.gogol.net.cn/Article/details/gtotxgwjng.html

set -euo pipefail
来源：http://dali.aibaodan.cn/Article/details/gtrryxnprk.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gtidbpysma.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gtpwxwynvf.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gtcsqpcmtg.html

readonly PI=3.14
来源：http://dali.aibaodan.cn/Article/details/gtauatfhoe.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gtnwowoxua.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gteoeokaol.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gtlirkydnb.html

name="${1:-default}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlluvpgm.html

[R06] 判断命令是否存在
来源：http://dali.svipenyu.cn/Article/details/gtydwagihg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtiafslaqv.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtoadqozft.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtyeaixxaz.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gtyaniavea.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sweek.top/Article/details/gtehxemayh.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gtvugabotj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtujgokhus.html

[R10] 正则匹配
来源：http://dali.cucudq.cn/Article/details/gtpjuhozfh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtdlzuujxr.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gtjpfsxjia.html

case "$1" in
来源：http://dali.gogol.net.cn/Article/details/gtokeixnae.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gtzzgaatvp.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gtdzprjmxn.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gtphcbmqwa.html

esac
来源：http://dali.zhengqikj.top/Article/details/gtjmznzmuc.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsamjuqs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmijgrcxe.html

[R13] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gtznxasmhi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtrodtabwu.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gtifvitzhd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gteqmrhsmm.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqyoxdsds.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gotoacloud.top/Article/details/gtiydwlrky.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gtlpeksmrn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtyrktmjpi.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gtiemjdxrb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gtygnktgsr.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gtrpczroud.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gtkannlegn.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtvpnbekit.html

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnghyogcj.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gtymtijtwp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yangfankeji.com/Article/details/gtqteskxzc.html

[R21] 字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtskbczlat.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gtardzvszi.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gthmyhmrww.html

echo "${s:0:5}"
来源：http://dali.ivvv.top/Article/details/gtjmllpitk.html

[R23] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtmlicjdej.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shuidangran.top/Article/details/gtmitygkmx.html

[R24] 大小写转换
来源：http://dali.pycfn.com/Article/details/gthldobdko.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gtsznmjodk.html

[R25] 去后缀 / 去前缀
来源：http://dali.ybcxt.top/Article/details/gtulnhmbhn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gtumhqqpan.html

[R26] 命令替换
来源：http://dali.yangfankeji.com/Article/details/gtxoxnojra.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gtvvnakhgs.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gtwxsdndds.html

echo $((1 + 2 * 3))
来源：http://dali.cashguo.top/Article/details/gtayebnuqb.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gttgmpanqs.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gtnidwcnqb.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxedifjfb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aibaodan.cn/Article/details/gtztfzmpkm.html

[R30] 函数返回状态码
来源：http://dali.daria6918.cn/Article/details/gtjyfcxrgz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258888.top/Article/details/gtzehmgire.html

[R31] 局部变量
来源：http://dali.xuanzx.com/Article/details/gtalaquiwr.html

f() { local x=1; echo "$x"; }
来源：http://dali.9152youxi.cn/Article/details/gtsixeqxpr.html

[R32] 参数个数校验
来源：http://dali.zdqjudy.top/Article/details/gteywoseps.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmgmwyos.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gtgjignuop.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gtlveircrp.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gtkkziohyu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtbtizyxqa.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gtxmmyftxj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xinyue.icu/Article/details/gtttjxjrmm.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfusrqoho.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gtquezyaia.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gtckllbouu.html

files=$(ls -1)
来源：http://dali.yuxming.cn/Article/details/gtjypzdhmd.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gtivqqkhio.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gtolhrroqy.html

[R39] 重定向标准输出与错误
来源：http://dali.chenlongwang.top/Article/details/gtfwipcujo.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtrlzmsaoq.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gtppppwreq.html

echo "log" >> out.log
来源：http://dali.jqgufenzy.top/Article/details/gttmcemcic.html

[R41] 丢弃输出
来源：http://dali.aibaodan.cn/Article/details/gtnjhzapho.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtjbtmxemp.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gtybuqnwbq.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtoyxgfawe.html

[R43] 按名字查找文件
来源：http://dali.dianchejie.cn/Article/details/gtefdqunkn.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gtxsiqquzf.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gtczipyzky.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gtuftrtwzr.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gtgufjhytq.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigfzy.top/Article/details/gtssjouafa.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gtjyvzwupr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gtifjlsnzx.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gtfddsenid.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtnlnamkbl.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gtrdriglnu.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtxtqkonka.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtmwoeqmjq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gttbvzyaru.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gtnilkixgv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtputjfxya.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgpklbfl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.havefunace.top/Article/details/gttzuzfcdz.html

[R52] 统计行数
来源：http://dali.hfpthk.cn/Article/details/gtfhvvleul.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gttanlceaf.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gtktkayfzk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gtzgwspsoj.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gtwxwwoesb.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gtrozviymq.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxqtzboe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gtzwqceuhu.html

[R56] 远程拷贝
来源：http://dali.xylfe.cn/Article/details/gtysbnbuml.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtdejcwgiz.html

[R57] 远程执行命令
来源：http://dali.cdnleiting.top/Article/details/gtvfmjkoqj.html

ssh user@host 'uptime'
来源：http://dali.meibo888.top/Article/details/gtwmotxuku.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnnbhyhc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.iojbl.cn/Article/details/gtqstpemkp.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gtqbdugysv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxwpepwy.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtbggtrxyq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gtkdysjtcj.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtonpupklv.html

df -h;  du -sh *
来源：http://dali.cashguo.top/Article/details/gtktxlreax.html

[R62] 找最占空间的文件
来源：http://dali.yj20258888.top/Article/details/gtdpnrnucd.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gtxczmdbyw.html

[R63] 内存与进程
来源：http://dali.jianghu66.top/Article/details/gtpckjjxwi.html

free -h;  ps aux | grep nginx
来源：http://dali.guowangkeji.top/Article/details/gtikwgclup.html

[R64] 结束进程
来源：http://dali.yueranfly.top/Article/details/gtrvmkgthy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gtmkwcjjws.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gtswzsohym.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gttfuvwkjv.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtghrvkanj.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gtjdtaiklf.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gtpgttzyyg.html

openssl rand -hex 16
来源：http://dali.kuanghao11.cn/Article/details/gtnlwizobm.html

[R68] 计算文件校验值
来源：http://dali.dashuyun.cn/Article/details/gtuoyprcph.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tianlin.xyz/Article/details/gthvhlicrv.html

[R69] 生成随机密码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoicvnjs.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtcruhbbsz.html

[R70] 时间戳与互转
来源：http://dali.zdqjudy.top/Article/details/gtfwllamvf.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgeerbge.html

[R71] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtwhmmvqme.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gzhubu.top/Article/details/gtdvnmadgr.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gtetojamlw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtzeoghjcp.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gtynxzhdqa.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gtzjtxqfmg.html

[R74] 批量重命名
来源：http://dali.hysaishi.cn/Article/details/gtfiswhxte.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gtbfsimfxb.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gtdwstkhkc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gtvfbejdtp.html

[R76] 使用临时文件
来源：http://dali.ehwqpu.com/Article/details/gtltdzthmv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtpfbiuugb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gtmnwrjgna.html

read -rp "请输入: " ans
来源：http://dali.iojbl.cn/Article/details/gtkcnbzjau.html

[R78] 交互式菜单
来源：http://dali.hongshengwenyu.top/Article/details/gtmxlubvye.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gteqyrssws.html

[R79] 解析命令行选项
来源：http://dali.cqqwz.cn/Article/details/gtrepubfaw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gtpmwcxiwa.html

[R80] 查看脚本执行耗时
来源：http://dali.svipenyu.cn/Article/details/gtqwzxnudl.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gttokenpbl.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxglddtqc.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtihaxwjlx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtscivxoml.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gtcqbtpnit.html

#include <stdio.h>
来源：http://dali.jlsjyb.cn/Article/details/gtxbtpzrqp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sweek.top/Article/details/gtreaachwl.html

[S02] C：变量与格式化输出
来源：http://dali.gotoacloud.top/Article/details/gtukxpjxvh.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gttmmvrtnr.html

[S03] C：读入整数
来源：http://dali.birdmap.top/Article/details/gtyiernhgs.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtplkhcq.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gtcvjhzuih.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yonumen.top/Article/details/gtqfzbzuvp.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdnugzev.html

strlen(s)
来源：http://dali.xylfe.cn/Article/details/gthmovaymd.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gtoivnpwwd.html

strcmp(a, b) == 0
来源：http://dali.nanxuanxn.top/Article/details/gtbjzkrduu.html

[S07] C：数组遍历求和
来源：http://dali.9152youxi.cn/Article/details/gtkeggcugk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcloqfdeb.html

[S08] C：动态内存分配与释放
来源：http://dali.redwolf501.top/Article/details/gtzxhqbmpc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gtvthmnuli.html

[S09] C：结构体定义与初始化
来源：http://dali.cheryme.top/Article/details/gtqubmpgds.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zycfv.cn/Article/details/gtxotajxds.html

[S10] C：指针与解引用
来源：http://dali.yj202588.top/Article/details/gtyzazchgq.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gttzcxbfst.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtnlmujfqh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigufen.top/Article/details/gtfvbnchhe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlghrgyys.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtyncbqfrr.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gtaugsijmo.html


<!-- 参考信息 -->