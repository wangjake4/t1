代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gtlagntrzg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhixingplan.top/Article/details/gtujyuzyva.html

[Q43] 标量子查询
来源：http://dali.xuetiantiany.cn/Article/details/gteisvmzdv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.redwolf501.top/Article/details/gtnxhcspot.html

[Q44] IN 子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtccdosrjn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gthmgopfei.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gttflywtjr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gttcuyuqaw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gaohongyu789.top/Article/details/gtejlprsai.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtljvpdlpf.html

[Q47] 与平均值比较
来源：http://dali.nanxuanxn.top/Article/details/gthdjlcgxj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yangfankeji.com/Article/details/gtzucscgjc.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gtcvlraqyl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gzhubu.top/Article/details/gtpfowkdxj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gthdvgoovv.html

[Q49] 更新单行
来源：http://dali.zhiwuduotai.top/Article/details/gtdeqwulmf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gtzhhcyqgn.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gtziznxnoi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtkcjtemjq.html

[Q51] 用子查询更新
来源：http://dali.yj202588.top/Article/details/gtdqcyddza.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuanzhike.top/Article/details/gtyiouvawr.html

[Q52] 删除指定行
来源：http://dali.ppjwa.cn/Article/details/gtbhpdawco.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtnagzerak.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gtzthobrmx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtysufpjzm.html

[Q54] 清空表
来源：http://dali.yvedp.cn/Article/details/gttmwpirgm.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtmfielaax.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigfzy.top/Article/details/gtjuebvxru.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfptwdpz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pengpengdd.cyou/Article/details/gthfegbvmb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtdlbycgov.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gtslvzityp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sweek.top/Article/details/gtnwfxueyc.html

[Q58] 累计求和
来源：http://dali.kuanghao11.cn/Article/details/gtfxwluimo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gtuapxsyox.html

[Q59] 分组内累计
来源：http://dali.hnqzz.top/Article/details/gtokwyjbqf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtcvyanmpi.html

[Q60] 取上一行 / 下一行
来源：http://dali.shangyingyoupin.top/Article/details/gtyjxxpypc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hysaishi.cn/Article/details/gtbvqwzhtp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtgdtinjba.html

[Q61] 移动平均
来源：http://dali.bjfxy.top/Article/details/gtujzvszei.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtcrijiqps.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gtkendoqpp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gteqzhtbyk.html

[Q63] 开启事务
来源：http://dali.9152youxi.cn/Article/details/gtuotsvbhr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.316326.xyz/Article/details/gtqavzhokg.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gtvpiqfuus.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gtbdzmosun.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gtsspykmaz.html

ROLLBACK;
来源：http://dali.tanke756.top/Article/details/gtcpmaqsmv.html

[Q66] 行锁查询
来源：http://dali.zhongyouzk.top/Article/details/gtbrqlqvyb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gtladwwyva.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gtvvlwooru.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ppjwa.cn/Article/details/gtmhwwltkg.html

[Q68] 保存点
来源：http://dali.yvedp.cn/Article/details/gtmpszldrq.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gtpemzrxfv.html

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gtgepbsmym.html

[Q69] 查看执行计划
来源：http://dali.ydzc1.top/Article/details/gtpsbonopf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gtytubivvt.html

[Q70] 更新统计信息
来源：http://dali.yj20258888.top/Article/details/gtkqiigzee.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gtplvoqths.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gtmuilbfwk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gtfggsehvs.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gtxhegyvpb.html

SHOW INDEX FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtxcrcmeoo.html

[Q73] 查看表状态
来源：http://dali.fengsongda.top/Article/details/gtnwdrkoby.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvnhttab.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtdbxetpjt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gteiucrhpm.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gtyumurtrj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtvllexcet.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daxiang520.top/Article/details/gtztqtgwhh.html

[Q76] 按天统计
来源：http://dali.mhx1999.top/Article/details/gtazlyvlsy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zycfv.cn/Article/details/gtnghblbcl.html

[Q77] 时间加减
来源：http://dali.yuanzhike.top/Article/details/gteswbyome.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gtporhfpyp.html

[Q78] 当前时间
来源：http://dali.aizwys.cn/Article/details/gttqhxqvhg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gttlilgrwe.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtobgocqgr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.iojbl.cn/Article/details/gtcjqfeyto.html

[Q80] 字符串截取
来源：http://dali.andypj.xyz/Article/details/gtgqdfcuru.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtueepdfew.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtyoqbuoar.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gtcmqjmwkc.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gtlveftdsv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtermdhzyq.html

[Q83] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtcgkatlsv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gteidecvpy.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gtlshnlswr.html

SELECT TRIM(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtniaodurp.html

[Q85] 数值取整
来源：http://dali.fengsongda.top/Article/details/gtnxmfylum.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dashuyun.cn/Article/details/gtrzpwjtul.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gtlsuozmep.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gtikkbznei.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gtlbjfsdjd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jlsjyb.cn/Article/details/gtphrddxax.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gtnishyyvp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gtznfnkkds.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtoxnrlmag.html

[Q89] 判断表是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gticxyjdde.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jiagoushi.top/Article/details/gtrfmqnjma.html

[Q90] 生成序号列
来源：http://dali.tianlin.xyz/Article/details/gtwmpfmqdm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.birdmap.top/Article/details/gtlzifqbuq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtfpwmubia.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gtwpfoevdi.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttuhbygnc.html

[R01] shebang 与严格模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgtltkdr.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gtiljhgnwp.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzefdjeaz.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gtahyzvrkh.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gthfatzivq.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gtsdpvsrzq.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gtsafeoehg.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gtgvoarmpr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gtdwvqjujj.html

[R05] 参数默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqhsahxr.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gtndrunnnr.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gtlszhsodq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtpxahcdwz.html

[R07] if 判断文件
来源：http://dali.dashuyun.cn/Article/details/gtsruftttx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtueqkadns.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtzszfxdrn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cashguo.top/Article/details/gtmfgvljdg.html

[R09] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtxekcgsgh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigufen.top/Article/details/gtncjnowgs.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtegeahhiz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gtcmxscilv.html

[R11] case 多分支
来源：http://dali.9152youxi.cn/Article/details/gtttqnlrif.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gtucompkty.html

start) echo "启动" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtjnkkpped.html

stop)  echo "停止" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtaeouotno.html

*)     echo "未知命令" ;;
来源：http://dali.yangfankeji.com/Article/details/gtrsbgsyei.html

esac
来源：http://dali.wangshuangyany.cn/Article/details/gtrgqkydre.html

[R12] for 遍历文件
来源：http://dali.havefunace.top/Article/details/gtwwzkfjyy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gtyxvebdxc.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtavzgtroi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtcizvdhwm.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtcklovaxk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtowsiomvm.html

[R15] while 逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtetcahsgb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tianlin.xyz/Article/details/gtifjffulh.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gtbsvimiav.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtyoqzvwqq.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gtyxtfgwje.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tianlin.xyz/Article/details/gtdimlsgul.html

[R18] 遍历数组
来源：http://dali.smart0.xyz/Article/details/gtfwxkcdhn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolbzbxve.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtjtnnbtzk.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gtglijbuex.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gtialiabud.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtcvsvyrbb.html

[R21] 字符串长度
来源：http://dali.daria6918.cn/Article/details/gtdkrqwwir.html

echo "${#s}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvepmfchg.html

[R22] 截取子串
来源：http://dali.ydzc1.top/Article/details/gtllxglpxv.html

echo "${s:0:5}"
来源：http://dali.dashuyun.cn/Article/details/gtztncbioi.html

[R23] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbjjleef.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtswvmrhgs.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gturmktphg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtqihjkjst.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gtvgkjqldf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yongpay.top/Article/details/gtpipamksv.html

[R26] 命令替换
来源：http://dali.sufxvd.cn/Article/details/gtalqnsprj.html

now=$(date +%F); echo "$now"
来源：http://dali.xylfe.cn/Article/details/gtszqdtvwf.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gtufythkua.html

echo $((1 + 2 * 3))
来源：http://dali.sxryk.cn/Article/details/gtrmqjmgce.html

[R28] 浮点运算
来源：http://dali.yangfankeji.com/Article/details/gtzlzzolqq.html

echo "scale=2; 10/3" | bc
来源：http://dali.hfpthk.cn/Article/details/gtelkaektl.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gtemqyjrak.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtdyobsdlv.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gtabmknohp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgfzy.top/Article/details/gtozmhlanv.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gtrtkbuwaw.html

f() { local x=1; echo "$x"; }
来源：http://dali.guowangkeji.top/Article/details/gtljsbcutq.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gtzsnnohii.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtkrcqzhwn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhengqikj.top/Article/details/gtfxqjozlo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gtrhpjxoao.html

[R34] 退出时清理
来源：http://dali.pengpengdd.cyou/Article/details/gtvsfqwpuo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtrvpbrkdp.html

[R35] 后台执行并等待
来源：http://dali.dashuyun.cn/Article/details/gtoruwbgal.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gaohongyu789.top/Article/details/gtoqxnumsv.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gttjhsybiw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gtrnpthbie.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gtpzkzoicd.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gtskyrxpvz.html

[R38] 管道串联
来源：http://dali.xylfe.cn/Article/details/gtudahnruf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gtowliyprb.html

[R39] 重定向标准输出与错误
来源：http://dali.yj202588.top/Article/details/gtigcmaief.html

cmd > out.log 2>&1
来源：http://dali.smart0.xyz/Article/details/gtrsrocbss.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gtnsbxdsvb.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gtzedvoeqz.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gtlbziwnjg.html

cmd >/dev/null 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtdbyyotzp.html

[R42] 输入重定向
来源：http://dali.zhongyouzk.top/Article/details/gtbbmtkctg.html

wc -l < a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtuupmwbfn.html

[R43] 按名字查找文件
来源：http://dali.mhx1999.top/Article/details/gtngvymewx.html

find . -name "*.log" -type f
来源：http://dali.havefunace.top/Article/details/gtlxndiuwd.html

[R44] 按修改时间查找
来源：http://dali.gotoacloud.top/Article/details/gtskcazopw.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gtmpzbpnqf.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gtzdahdixb.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gtobkhwvpt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gtalrkmnuj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gthamnxdbp.html

[R47] sed 单行替换
来源：http://dali.xziqi.cn/Article/details/gtrfuwtxpz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nwbrower.top/Article/details/gttkvyxvwr.html

[R48] awk 取指定列
来源：http://dali.yanxiufei.cn/Article/details/gtmeihjhuu.html

awk '{print $1, $3}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtqgxhmqly.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gtwqghcwby.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gthftnwpij.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gtsehnvyqt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtbexgvfti.html

[R51] 排序去重取前几
来源：http://dali.9152youxi.cn/Article/details/gtwtjndczs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.svipenyu.cn/Article/details/gtbrtbtriv.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gthiqdmpzl.html

wc -l a.txt
来源：http://dali.wangdashe.top/Article/details/gtnfhvjubk.html

[R53] 查看文件头与实时尾
来源：http://dali.yongpay.top/Article/details/gtaaocagxm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gteawdndab.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gtnscnnbbg.html

diff a.txt b.txt
来源：http://dali.dashuyun.cn/Article/details/gtkmmvwgjm.html

[R55] 压缩与解压
来源：http://dali.wangshuangyany.cn/Article/details/gtseiscohv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gogol.net.cn/Article/details/gtlclmvfyw.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gtvsiqtvbm.html

scp file user@host:/path/
来源：http://dali.guowangkeji.top/Article/details/gtgquitvcc.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gtgnvszihd.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gtwbgtwwdk.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gtsdthscku.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258888.top/Article/details/gtccziqrtk.html

[R59] 发 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtjyvnroec.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hammf.cn/Article/details/gttdlrjksl.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtysluoxak.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gtlwbpnvrj.html

[R61] 磁盘占用
来源：http://dali.smart0.xyz/Article/details/gtyjjfcmpl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gtkhtxgjbp.html

[R62] 找最占空间的文件
来源：http://dali.wangdashe.top/Article/details/gtuprxpdgj.html

du -ah . | sort -rh | head -10
来源：http://dali.fzhhl.top/Article/details/gtobkyieka.html

[R63] 内存与进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubsyzdfi.html

free -h;  ps aux | grep nginx
来源：http://dali.sweek.top/Article/details/gtlgmlklaf.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gttesiacsv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.snrcjt.cn/Article/details/gtnklzgivb.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gttxtlohwm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cashguo.top/Article/details/gtqfufjwvt.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gtanhnehpy.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gtppyzorek.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gttskytybs.html

openssl rand -hex 16
来源：http://dali.quarkkingdee.top/Article/details/gtweiwumed.html

[R68] 计算文件校验值
来源：http://dali.zhixingplan.top/Article/details/gtfnjhqsxo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gtlnunwjvo.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gtyemyuulx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zdqjudy.top/Article/details/gtortgehha.html

[R70] 时间戳与互转
来源：http://dali.kuanghao11.cn/Article/details/gtbwtpybvv.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gtkzebokuw.html

[R71] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gteycqotiq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gtswwbenyo.html

[R72] 等待端口就绪
来源：http://dali.jlsjyb.cn/Article/details/gthfavpqss.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtpurlypyv.html

[R73] 分割大日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgkhubwd.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumwsozor.html

[R74] 批量重命名
来源：http://dali.birdmap.top/Article/details/gtvdvxssjh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dianchejie.cn/Article/details/gtrmmsvzee.html

[R75] 导出环境变量
来源：http://dali.yongpay.top/Article/details/gtbbmdrxze.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gtdqsexreo.html

[R76] 使用临时文件
来源：http://dali.sxryk.cn/Article/details/gtowmvbuwn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtyjswmrzx.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gtsnuxyfik.html

read -rp "请输入: " ans
来源：http://dali.jinqigufen.top/Article/details/gtwnyjcsdo.html

[R78] 交互式菜单
来源：http://dali.jinghuilouyu.cn/Article/details/gtklujyrha.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jianghu66.top/Article/details/gtyynjaxvj.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gthaxcclul.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtvgvjpbag.html

[R80] 查看脚本执行耗时
来源：http://dali.sweek.top/Article/details/gtjprhzejc.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gtkpbpfyrk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrotknqwk.html

S. C / C++ 专题
来源：http://dali.vqdsnc.cn/Article/details/gtbkmyytgb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gteyzwsmkz.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gthztoncuq.html

#include <stdio.h>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzorzshbr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxinkj.top/Article/details/gttzukqgjo.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gtadavoyrf.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gtpjoibwdb.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gtfxtvwkrx.html

int x; scanf("%d", &x);
来源：http://dali.wangdashe.top/Article/details/gtjvmsrxbc.html

[S04] C：字符串复制
来源：http://dali.cqqwz.cn/Article/details/gtpaxjulut.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigufen.top/Article/details/gttmmwliyr.html

[S05] C：字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtahdjadrq.html

strlen(s)
来源：http://dali.aibaodan.cn/Article/details/gthnvyhavf.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtqsubdaug.html

strcmp(a, b) == 0
来源：http://dali.9152youxi.cn/Article/details/gtuladxuzp.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gtlrrcbgvj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hammf.cn/Article/details/gtvjtkvjoo.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gthovbkqqa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gtydbbibpg.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gtwnfxxsoe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gotoacloud.top/Article/details/gtazrbjvhw.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gthxpnxoim.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gtmgxcghpd.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtaunxqcwv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.feifeiyinyue.top/Article/details/gtaxpzjwuq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gtknulimlh.html

fclose(f);
来源：http://dali.yvedp.cn/Article/details/gtlvdvgikm.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gttwjakijb.html


<!-- 参考信息 -->