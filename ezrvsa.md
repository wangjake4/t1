代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zdqjudy.top/Article/details/gtuknpqpyv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gtknfpahor.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gtbulhywec.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gtgwoifqcw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gtpcyitoqk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gttileujeb.html

[Q43] 标量子查询
来源：http://dali.yj20258888.top/Article/details/gtmqmgtqxa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gtybxsmwuz.html

[Q44] IN 子查询
来源：http://dali.yuanzhike.top/Article/details/gtecggxtch.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258888.top/Article/details/gtvfaxrgci.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gtzjlwoosn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gtgfjsuhks.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gtbjxrapjx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtsnztynjq.html

[Q47] 与平均值比较
来源：http://dali.nanxuanxn.top/Article/details/gtnlukjadh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj202588.top/Article/details/gtoyraotjm.html

[Q48] CTE 公用表表达式
来源：http://dali.hysaishi.cn/Article/details/gtajhtqixa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gtbsiipbqz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuxming.cn/Article/details/gtliqxqvva.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gtdzgzjazu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gtllymznwo.html

[Q50] 批量更新
来源：http://dali.jyoumei.cn/Article/details/gtrywjbnbj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtbqsuqsgd.html

[Q51] 用子查询更新
来源：http://dali.gotoacloud.top/Article/details/gtkxbnbqhe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfdugrzv.html

[Q52] 删除指定行
来源：http://dali.hnqzz.top/Article/details/gtawqwogxs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtjdarkevd.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gtpcrabpwv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cashguo.top/Article/details/gtefqsafsj.html

[Q54] 清空表
来源：http://dali.gaohongyu789.top/Article/details/gtgcmorhoh.html

TRUNCATE TABLE logs;
来源：http://dali.gaohongyu789.top/Article/details/gtovkbiufk.html

[Q55] 排名（并列占位）
来源：http://dali.yongpay.top/Article/details/gtebwfutqz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtzgvtmbix.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gtcggfiavs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtkrikeivc.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gtnqpuobcd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtegaoufzx.html

[Q58] 累计求和
来源：http://dali.zhengqikj.top/Article/details/gtnudaxpxd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtskarqugj.html

[Q59] 分组内累计
来源：http://dali.bjfxy.top/Article/details/gtkihgormn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtdgirafwt.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gteerqzzqr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yangfankeji.com/Article/details/gtirurknux.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtwyfiqbex.html

[Q61] 移动平均
来源：http://dali.jinqigfzy.top/Article/details/gtpbopijub.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtcthxgygt.html

[Q62] 分组占比
来源：http://dali.dianchejie.cn/Article/details/gtbwjuopld.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtuvvtyiqs.html

[Q63] 开启事务
来源：http://dali.zdqjudy.top/Article/details/gtspsniwtj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.316326.xyz/Article/details/gtszjsznic.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gtxmkofujj.html

COMMIT;
来源：http://dali.ehwqpu.com/Article/details/gtauveweui.html

[Q65] 回滚事务
来源：http://dali.hywenlv.cn/Article/details/gtzhsyprgg.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gtmlmzxezz.html

[Q66] 行锁查询
来源：http://dali.yanxiufei.cn/Article/details/gtuprrywgx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fengsongda.top/Article/details/gtvmmuxzls.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gtvfglctsl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gtiowubbuj.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gtikhlhsvt.html

SAVEPOINT sp1;
来源：http://dali.pycfn.com/Article/details/gtwlpiyzlp.html

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gtgxlknvlx.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gtirpkphzy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.meibo888.top/Article/details/gtwmakxwfg.html

[Q70] 更新统计信息
来源：http://dali.wangdashe.top/Article/details/gtjmclllji.html

ANALYZE TABLE users;
来源：http://dali.jyoumei.cn/Article/details/gteyyrqspq.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchvniydw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gtiajuqvdl.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gtiojbfuqe.html

SHOW INDEX FROM users;
来源：http://dali.ydzc1.top/Article/details/gtaaqbyuob.html

[Q73] 查看表状态
来源：http://dali.yj20258.top/Article/details/gtdkdwzbio.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gtinuwemkh.html

[Q74] 强制使用索引
来源：http://dali.xinyue.icu/Article/details/gtxysguvqz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cheryme.top/Article/details/gtqfpukrni.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtuuoyvckc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtcannjwge.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujjpoaot.html

[Q76] 按天统计
来源：http://dali.wangdashe.top/Article/details/gtngxgedmn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gtyqyhbhns.html

[Q77] 时间加减
来源：http://dali.wangshuangyany.cn/Article/details/gttmavnblo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gtbwlylolz.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gtmkoyfnbx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ivvv.top/Article/details/gtmltwudbw.html

[Q79] 字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gtihzmqjbq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gtotjqlndm.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gtavuewixp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtvzaznvuz.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtlbsvrsuu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtogpnccti.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykvlayjm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtmwsxijne.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtdorqkfgo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtnhmsbvyx.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gtfeupgwww.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gthkeqmbwt.html

[Q85] 数值取整
来源：http://dali.jinqigufen.top/Article/details/gtshyidbgr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhiwuduotai.top/Article/details/gtolntgmvu.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gtpriscjpr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuanzx.com/Article/details/gtwsljcqzd.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gtktvwuyrm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gtprmnkxqv.html

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gtbvsgyopx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258.top/Article/details/gtmmwrbuil.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtnpnholpj.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gthqswrvrt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtiqteeejq.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkubbzxi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gthbgbxeic.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbfflpmm.html

R. Bash 专题
来源：http://dali.dianchejie.cn/Article/details/gttpkomkyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtgembxsvy.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gtoqxuqnjm.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gtitftvxxt.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gtcvmiysnt.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gtljujzzvh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gtoepvfplg.html

[R03] 只读变量
来源：http://dali.zhongyouzk.top/Article/details/gtpoabhndd.html

readonly PI=3.14
来源：http://dali.yonumen.top/Article/details/gtmcsbzklw.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gtfxbqaked.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.smart0.xyz/Article/details/gtfqdbovsy.html

[R05] 参数默认值
来源：http://dali.ydzc1.top/Article/details/gtrgytzbjb.html

name="${1:-default}"
来源：http://dali.shangyingyoupin.top/Article/details/gteifpabyx.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtmdoteson.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtymgbggza.html

[R07] if 判断文件
来源：http://dali.quarkkingdee.top/Article/details/gtscwypqna.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtbykhsksq.html

[R08] 数值比较
来源：http://dali.xylfe.cn/Article/details/gthvlavffe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.mhx1999.top/Article/details/gttuiskllz.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtreokimsv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sxryk.cn/Article/details/gtznqdhusx.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gtyfkmpvtx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtindbmmmr.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gtaplyjfnh.html

case "$1" in
来源：http://dali.shangyingyoupin.top/Article/details/gtjpadqchs.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gtqxdgwbnw.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gtpenrayow.html

*)     echo "未知命令" ;;
来源：http://dali.cucudq.cn/Article/details/gtmkyvivck.html

esac
来源：http://dali.yangfankeji.com/Article/details/gttpmqsuct.html

[R12] for 遍历文件
来源：http://dali.cheryme.top/Article/details/gtzzswvmzr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gtqfwfqlid.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtrisacncm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtiezkusvm.html

[R14] C 风格 for
来源：http://dali.aizwys.cn/Article/details/gtitpluvhv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtygixejjk.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gtdnkvghcw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgfzy.top/Article/details/gtbstwhjch.html

[R16] until 等待条件
来源：http://dali.cqqwz.cn/Article/details/gtmhougpgj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gtioflnepd.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gttxlzgtxl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fzhhl.top/Article/details/gthpebwfhz.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gtkzfcwwwz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtvhpfdqls.html

[R19] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtferkxkqi.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gtlmhvbolc.html

[R20] 关联数组（字典）
来源：http://dali.smart0.xyz/Article/details/gtjzpeousu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtlmeyplvu.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtbplmiesn.html

echo "${#s}"
来源：http://dali.zycfv.cn/Article/details/gtrbrtebcz.html

[R22] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtsdvvkcdh.html

echo "${s:0:5}"
来源：http://dali.ivvv.top/Article/details/gtyzkosjbq.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtdihxfgep.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gthwzmgpzu.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtjxnifvuy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gtnndhfxws.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gtkjshdrhl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gtbeteojwj.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gtvqqsiasu.html

now=$(date +%F); echo "$now"
来源：http://dali.yuanzhike.top/Article/details/gtsqoyyzog.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gtrttrpqjh.html

echo $((1 + 2 * 3))
来源：http://dali.cheryme.top/Article/details/gtnbvvxons.html

[R28] 浮点运算
来源：http://dali.0kj1m.cn/Article/details/gtckxapasa.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtwsxjzcxm.html

[R29] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gtonvtvyta.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gtasiapgxd.html

[R30] 函数返回状态码
来源：http://dali.nanxinkj.top/Article/details/gtimjknzwb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gtwklkpjzg.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gtzsayeejo.html

f() { local x=1; echo "$x"; }
来源：http://dali.yvedp.cn/Article/details/gtmyaltvjp.html

[R32] 参数个数校验
来源：http://dali.zhiwuduotai.top/Article/details/gtbuxygpgo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gthyopjvce.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gtrvmwmnyg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gtzdzkiuxd.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gtbausknqw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtjlqibcrd.html

[R35] 后台执行并等待
来源：http://dali.yuxming.cn/Article/details/gtbyxfzddp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gtfquefthm.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gtipjnmogy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.feifeiyinyue.top/Article/details/gtamyghfhz.html

[R37] 把输出赋给变量
来源：http://dali.zhengqikj.top/Article/details/gtkxtedhip.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gtsryluhou.html

[R38] 管道串联
来源：http://dali.yj20258888.top/Article/details/gtdxevdxgi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gtvtofjmus.html

[R39] 重定向标准输出与错误
来源：http://dali.gogol.net.cn/Article/details/gtbhocskdr.html

cmd > out.log 2>&1
来源：http://dali.c1oappe.top/Article/details/gtsikxekjl.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gtqkrpcmva.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gtcgyhgkzc.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcyttxok.html

cmd >/dev/null 2>&1
来源：http://dali.bjfxy.top/Article/details/gthybmgstu.html

[R42] 输入重定向
来源：http://dali.nanxinkj.top/Article/details/gtilpbksfx.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gtqcrjzwzi.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gtchsciwmn.html

find . -name "*.log" -type f
来源：http://dali.ppjwa.cn/Article/details/gtnhxjrbmg.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gtgklpwarp.html

find . -mtime -7 -type f
来源：http://dali.chenzaomai.com/Article/details/gtiwrxtddh.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gtayfyavnp.html

find . -name "*.tmp" -delete
来源：http://dali.chenzaomai.com/Article/details/gtwtsahuym.html

[R46] 递归替换文件内容
来源：http://dali.shangyingyoupin.top/Article/details/gtqrgrszqb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gtjaxfyncc.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gthjpideia.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtmpnkakwv.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtlddfipfb.html

awk '{print $1, $3}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtembiyuva.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gtzlndmkxr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fzhhl.top/Article/details/gtrhxddzix.html

[R50] awk 求和
来源：http://dali.jiagoushi.top/Article/details/gtobafimrf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzikxpwrr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gtwhdpphcc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gtfldtasin.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gtqegcbyaz.html

wc -l a.txt
来源：http://dali.shzxlz.cn/Article/details/gtnhzbfnov.html

[R53] 查看文件头与实时尾
来源：http://dali.316326.xyz/Article/details/gtmsarkomn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gtjmmhnzfl.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gtyckahcxh.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gtvgwefwwy.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gtxgkajwen.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gtrpjejrsv.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gtgtypgcop.html

scp file user@host:/path/
来源：http://dali.zhengqikj.top/Article/details/gtdpxcitwe.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gthjipfhue.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gtvidcgcvn.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegivgivw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuxming.cn/Article/details/gtqqrfdltj.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtbradffoj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gtahoborti.html

[R60] 只看 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtydaixutx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gthetltznx.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gtroykonqq.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gtlpayeukx.html

[R62] 找最占空间的文件
来源：http://dali.kuanghao11.cn/Article/details/gtfbzahjyg.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gtcjnpical.html

[R63] 内存与进程
来源：http://dali.yongpay.top/Article/details/gtfkqspuud.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gtnwsjsmwk.html

[R64] 结束进程
来源：http://dali.yj20258888.top/Article/details/gtvxxqsrdu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gtwutdbdfx.html

[R65] 查看端口占用
来源：http://dali.cheryme.top/Article/details/gtauvidwlc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guannengcc.top/Article/details/gtqmujjbfc.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gttrxlgabk.html

crontab -e;  crontab -l
来源：http://dali.zhengqikj.top/Article/details/gtnejwcgwz.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gtlvsvtocy.html

openssl rand -hex 16
来源：http://dali.daria6918.cn/Article/details/gtvvjhnwrd.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gtqhtvpwrv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gtxstfhoth.html

[R69] 生成随机密码
来源：http://dali.yj20258.top/Article/details/gtxteatgeo.html

head -c 16 /dev/urandom | base64
来源：http://dali.shangyingyoupin.top/Article/details/gtpuvddzep.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gtyagfhvnp.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gtqgctafhl.html

[R71] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtafqfxtqu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cqqwz.cn/Article/details/gttogitxli.html

[R72] 等待端口就绪
来源：http://dali.aizwys.cn/Article/details/gtejajtiuo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtcazxevrq.html

[R73] 分割大日志
来源：http://dali.shzxlz.cn/Article/details/gtawbapkqf.html

split -l 1000 big.log part_
来源：http://dali.zhixingplan.top/Article/details/gtnyjnybuz.html

[R74] 批量重命名
来源：http://dali.gotoacloud.top/Article/details/gtaqefjmbw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gtfbmeuazi.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gtqgeavjvf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hfpthk.cn/Article/details/gtqbtwpfrs.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gtjaluqqad.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtfijnzigs.html

[R77] 读取用户输入
来源：http://dali.yueranfly.top/Article/details/gtyduxreog.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gtbjlketyo.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gtbpnkfahf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tianlin.xyz/Article/details/gtumfgpnpm.html

[R79] 解析命令行选项
来源：http://dali.jianghu66.top/Article/details/gtjozbxyyp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gtkqcfucuh.html

[R80] 查看脚本执行耗时
来源：http://dali.aizwys.cn/Article/details/gtgbyrreqv.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gtuglzzxee.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtazwuxxpb.html

S. C / C++ 专题
来源：http://dali.andypj.xyz/Article/details/gthirjhlpb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtjrkarajy.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gtympyqzjo.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtkyzgrowz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.smart0.xyz/Article/details/gtdiunvxcn.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258888.top/Article/details/gtwexivdcx.html

int a = 10; printf("%d\n", a);
来源：http://dali.sysykeji.top/Article/details/gtvzfirnyl.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gtbbpabwdr.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gtnjmjcnyx.html

[S04] C：字符串复制
来源：http://dali.daria6918.cn/Article/details/gtotgfbfun.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtwajnodlr.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtbbmdscbe.html

strlen(s)
来源：http://dali.yj20258888.top/Article/details/gtyqsxlrjt.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtrklutvfb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gtwvdnroev.html

[S07] C：数组遍历求和
来源：http://dali.sysykeji.top/Article/details/gtogujnski.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gtawrocjzd.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gtieuimtod.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gtddyrpqbc.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gtdgzolbik.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shzxlz.cn/Article/details/gtdswofyaw.html

[S10] C：指针与解引用
来源：http://dali.yangfankeji.com/Article/details/gtzqdriwxb.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gtszxtexny.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gthckybtvb.html


<!-- 参考信息 -->