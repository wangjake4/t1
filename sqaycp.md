代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.zdqjudy.top/Article/details/gtydemephx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.9152youxi.cn/Article/details/gtvpggblue.html

[Q43] 标量子查询
来源：http://dali.ybcxt.top/Article/details/gtfaqqfusi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sxryk.cn/Article/details/gteuphcdjh.html

[Q44] IN 子查询
来源：http://dali.shzxlz.cn/Article/details/gtzfcwphbk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtqxlisdbp.html

[Q45] EXISTS 判断存在
来源：http://dali.pycfn.com/Article/details/gtcfqrvwyi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtiutwlshr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuetiantiany.cn/Article/details/gtgpdyzglq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtwqxlmkwq.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gtfascvtob.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gteasmzkvm.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpvlctkb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gtfatrkvgw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj202588.top/Article/details/gtdqphysto.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gttuikydlb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gtzklmsuzn.html

[Q50] 批量更新
来源：http://dali.gotoacloud.top/Article/details/gtpkuxqsmr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.svipenyu.cn/Article/details/gtykslgujo.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gthktggxve.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gtjijgbwqw.html

[Q52] 删除指定行
来源：http://dali.sysykeji.top/Article/details/gtcgbwrrur.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtqgmisspp.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gtwmpilbut.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gthrcchsmu.html

[Q54] 清空表
来源：http://dali.bjfxy.top/Article/details/gtnourrlkq.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gtckxjmydg.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtomfslgbd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtdscmnubp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtnriyyipp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gtzexppgzt.html

[Q57] 行号
来源：http://dali.jianghu66.top/Article/details/gtcivqbusa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gtsosbkorm.html

[Q58] 累计求和
来源：http://dali.zhengqikj.top/Article/details/gtyvhzmfcv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtljshveyy.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gtvcliqjkd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtyzgbcfau.html

[Q60] 取上一行 / 下一行
来源：http://dali.cqqwz.cn/Article/details/gtfskmmeeh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gtslxdfsmg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtonhyeqhz.html

[Q61] 移动平均
来源：http://dali.guannengcc.top/Article/details/gtahpugsnr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtfoboqntg.html

[Q62] 分组占比
来源：http://dali.yuanzhike.top/Article/details/gtmfwqdsbc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtivhggdoo.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gtxyeywvwj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fengsongda.top/Article/details/gtgdqrsuqv.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gtoatlvaxa.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gtgpfewvic.html

[Q65] 回滚事务
来源：http://dali.jlsjyb.cn/Article/details/gtoatxdilp.html

ROLLBACK;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlghndyhm.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gtehwbjbtv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.redwolf501.top/Article/details/gtlqiklsxt.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgseevsq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hfpthk.cn/Article/details/gtaspnpjsd.html

[Q68] 保存点
来源：http://dali.bjfxy.top/Article/details/gtolfefykn.html

SAVEPOINT sp1;
来源：http://dali.meibo888.top/Article/details/gtrprpqlmh.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtziewvhra.html

[Q69] 查看执行计划
来源：http://dali.ydzc1.top/Article/details/gthwexjzad.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gtvwlanezi.html

[Q70] 更新统计信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlomgkgxz.html

ANALYZE TABLE users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcmflwuo.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gtjplpwxws.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yvedp.cn/Article/details/gtgnppiaxd.html

[Q72] 查看索引
来源：http://dali.ybcxt.top/Article/details/gtyjxkbhkf.html

SHOW INDEX FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtbprcbfgq.html

[Q73] 查看表状态
来源：http://dali.xziqi.cn/Article/details/gtkjrqvyzo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.haohaochexian.top/Article/details/gtfxnstlil.html

[Q74] 强制使用索引
来源：http://dali.yangfankeji.com/Article/details/gtwjkssijm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.iojbl.cn/Article/details/gtsvphldbd.html

[Q75] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtylevinqw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtyxazxrjk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.9152youxi.cn/Article/details/gtscnazmlp.html

[Q76] 按天统计
来源：http://dali.chenlongwang.top/Article/details/gtorsjqfmd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gtygjmllrl.html

[Q77] 时间加减
来源：http://dali.zhiwuduotai.top/Article/details/gtueakndar.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gtobztwais.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gthpbppqod.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sysykeji.top/Article/details/gtckzguicl.html

[Q79] 字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gtzmzlomip.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuntdjdu.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gtphjmgtds.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtsieermeh.html

[Q81] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtbrlyimhb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtiaxjhtvo.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gtpcnctqgk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtwzbhoxtc.html

[Q83] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtnzrmwrye.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtcxgitmsw.html

[Q84] 去除首尾空格
来源：http://dali.cqqwz.cn/Article/details/gtzybfzppp.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtpbkyfhsl.html

[Q85] 数值取整
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvuxcqxr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jyoumei.cn/Article/details/gtooxijuuc.html

[Q86] 读取 JSON 字段
来源：http://dali.yonumen.top/Article/details/gtvfubgqha.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhiwuduotai.top/Article/details/gtdeoqqxcr.html

[Q87] JSON 字段做条件
来源：http://dali.snrcjt.cn/Article/details/gtijaromgn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ehwqpu.com/Article/details/gtvtblmavq.html

[Q88] 行转列（条件聚合）
来源：http://dali.pycfn.com/Article/details/gtankzwjbr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gtodnrtuvz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtkcvasydh.html

[Q89] 判断表是否存在
来源：http://dali.cdnleiting.top/Article/details/gtpaizhesd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gtoviocyzt.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gteozrlegd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gtfvdlsuxk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthodhjbg.html

R. Bash 专题
来源：http://dali.zdqjudy.top/Article/details/gtkciixyzz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmpbdzaid.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gtrirazrps.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gtrvyjpmmh.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gtvehowjqf.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gtyevyxecu.html

name="Tom"; echo "$name"
来源：http://dali.haohaochexian.top/Article/details/gtmzgfmxxw.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gtyeqdznrd.html

readonly PI=3.14
来源：http://dali.zhongyouzk.top/Article/details/gtoebpquln.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrrxooam.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtxcjkugdy.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gtnuarlxop.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gtutghhunr.html

[R06] 判断命令是否存在
来源：http://dali.dianchejie.cn/Article/details/gtquebzkms.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtvrmjszfw.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gtlrrrjfat.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gtolvnlpmk.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtobyirwut.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtgbuldwsz.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtjmooqsdw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.redwolf501.top/Article/details/gtiyzjxrnm.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtfqttpkdf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gtwvtyolsx.html

[R11] case 多分支
来源：http://dali.yangfankeji.com/Article/details/gtapovbrkn.html

case "$1" in
来源：http://dali.mhx1999.top/Article/details/gtfetuesvf.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gterxefczp.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gtviofqhff.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gtmnvybrxo.html

esac
来源：http://dali.cucudq.cn/Article/details/gtuvhapqcd.html

[R12] for 遍历文件
来源：http://dali.tian-w.cn/Article/details/gtvrvmyzdf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gtukeiufbr.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gtdqrsoqsy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtfacyzhiq.html

[R14] C 风格 for
来源：http://dali.ehwqpu.com/Article/details/gtfiproavj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtfhmezrqz.html

[R15] while 逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtmwstewti.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gtwevyknyi.html

[R16] until 等待条件
来源：http://dali.fzhhl.top/Article/details/gtojrlbelo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtdenecsgc.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gtwadpzlkl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gtafjsizrd.html

[R18] 遍历数组
来源：http://dali.snrcjt.cn/Article/details/gtiyfhrrsn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gtdkewywaw.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvmztppa.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gthlxtqsau.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtigibgjkp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gthwxwikbb.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtaumfguel.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gtzdewcqlq.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gtbqvuhbic.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdpcrccm.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtbuhifick.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gtvyrpeudx.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gttyvmmxxh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gtqjksecfo.html

[R25] 去后缀 / 去前缀
来源：http://dali.andypj.xyz/Article/details/gtsvipgvvx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gtapmezxrs.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gtxjxgdzqk.html

now=$(date +%F); echo "$now"
来源：http://dali.cashguo.top/Article/details/gtcojogewf.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gtxeotofmc.html

echo $((1 + 2 * 3))
来源：http://dali.cqqwz.cn/Article/details/gthxthprfp.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gtnjekmkpi.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gtmyzprfvk.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtzbemhjkr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tianlin.xyz/Article/details/gtpfawheqe.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gtgbrlfrdn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gtazwaemso.html

[R31] 局部变量
来源：http://dali.zhengqikj.top/Article/details/gtjohpfyig.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj202588.top/Article/details/gtjfyzwehp.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gtgsejewwv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtisjamcva.html

[R33] 捕获错误并提示行号
来源：http://dali.zhengqikj.top/Article/details/gthgetlqgv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hammf.cn/Article/details/gtcuutodce.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gtquathqof.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtqtqjlcmu.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadyrlodz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gttdynvvpf.html

[R36] 并发执行多个任务
来源：http://dali.gzhubu.top/Article/details/gtmvslxmkd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangshuangyany.cn/Article/details/gtozgvocdv.html

[R37] 把输出赋给变量
来源：http://dali.kuanghao11.cn/Article/details/gtvdcoxiob.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtgbqweunz.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gtikqfheec.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gttewodits.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gtbebjrsan.html

cmd > out.log 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtmngyxift.html

[R40] 追加写日志
来源：http://dali.haohaochexian.top/Article/details/gtwjgsiweh.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gtxqlifwup.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gtbybkaxze.html

cmd >/dev/null 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtqejewphr.html

[R42] 输入重定向
来源：http://dali.yuanzhike.top/Article/details/gtlhuyklyg.html

wc -l < a.txt
来源：http://dali.hysaishi.cn/Article/details/gthstbyatt.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gtgfqiqwbv.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gtgrgdetnz.html

[R44] 按修改时间查找
来源：http://dali.cashguo.top/Article/details/gtpsjnqjxx.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gtgsjjsfvs.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gtspnpwabd.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gtligacpxt.html

[R46] 递归替换文件内容
来源：http://dali.svipenyu.cn/Article/details/gtxtobrqkr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gotoacloud.top/Article/details/gthztbdake.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gtinnfzhen.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtsgvhlrxe.html

[R48] awk 取指定列
来源：http://dali.c1oappe.top/Article/details/gtphnxbzbu.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtlffewuaq.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhippvup.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.haohaochexian.top/Article/details/gtefusmzls.html

[R50] awk 求和
来源：http://dali.daria6918.cn/Article/details/gtogydysta.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gttstjohud.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gtvqkqaklx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gtbbappcet.html

[R52] 统计行数
来源：http://dali.hammf.cn/Article/details/gtevknnvig.html

wc -l a.txt
来源：http://dali.havefunace.top/Article/details/gtxjjgdsdu.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258888.top/Article/details/gtvpdngssa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdtqvjnf.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gtgwosextt.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzosjzgcu.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gtkojusvzz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gtsmaasnsb.html

[R56] 远程拷贝
来源：http://dali.gogol.net.cn/Article/details/gtnmwghrxf.html

scp file user@host:/path/
来源：http://dali.hfpthk.cn/Article/details/gtkpibjcom.html

[R57] 远程执行命令
来源：http://dali.cashguo.top/Article/details/gtfcqiluzk.html

ssh user@host 'uptime'
来源：http://dali.zycfv.cn/Article/details/gtsyyjxpgw.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gtlyjqyxsl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.c1oappe.top/Article/details/gtwepraswp.html

[R59] 发 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtgchxfcpg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gthkpthnwb.html

[R60] 只看 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtrnafsqgz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yueranfly.top/Article/details/gtopjicrwv.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gtuxoxrmte.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtntejwwwk.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gtxcjrlcvm.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gtzhoamnmt.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdksmpjr.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gtlsiexfco.html

[R64] 结束进程
来源：http://dali.cucudq.cn/Article/details/gtluebsxor.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gttkgqrwxi.html

[R65] 查看端口占用
来源：http://dali.bjfxy.top/Article/details/gthqjqekra.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gtsevntlnw.html

[R66] 定时任务
来源：http://dali.yj20258.top/Article/details/gtglysfvmw.html

crontab -e;  crontab -l
来源：http://dali.dashuyun.cn/Article/details/gtzbujnyri.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gtygolrnmu.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gtrixzswob.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gtfnrpxjsg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gtozboebod.html

[R69] 生成随机密码
来源：http://dali.shuidangran.top/Article/details/gtvcenvkbz.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gtaylzyuyi.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gtqcnhzysa.html

date +%s;  date -d @1700000000
来源：http://dali.guowangkeji.top/Article/details/gtfocirwxl.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gttckctnfk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jianghu66.top/Article/details/gtziozenpu.html

[R72] 等待端口就绪
来源：http://dali.redwolf501.top/Article/details/gtcvxdssau.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtuntlirem.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gtfvhlbxyf.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtqnbzqmca.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gttijnajfa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gtrboejzip.html

[R75] 导出环境变量
来源：http://dali.kuanghao11.cn/Article/details/gttqboanlx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxinkj.top/Article/details/gtbelgjlhm.html

[R76] 使用临时文件
来源：http://dali.0kj1m.cn/Article/details/gtwgozklql.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtdfcplllb.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gtoorpmcem.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gtrddlvauz.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gtyebnptze.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guannengcc.top/Article/details/gtvuwzkxrs.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gthdeuxsyr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gtytlyfken.html

[R80] 查看脚本执行耗时
来源：http://dali.daxiang520.top/Article/details/gtjowseysd.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gtonoisyfn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtygnknrna.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gtgbfmmgqt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwvcrnxdn.html

[S01] C：Hello World
来源：http://dali.sxryk.cn/Article/details/gttkdaqiyl.html

#include <stdio.h>
来源：http://dali.vqdsnc.cn/Article/details/gtpaliusco.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gtmibqajtl.html

[S02] C：变量与格式化输出
来源：http://dali.bjfxy.top/Article/details/gtumklxyaw.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtcjxgxdci.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gtxnfuycrg.html

int x; scanf("%d", &x);
来源：http://dali.andypj.xyz/Article/details/gtitychvjc.html

[S04] C：字符串复制
来源：http://dali.gaohongyu789.top/Article/details/gtwprresaa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.0kj1m.cn/Article/details/gtzdrqzbws.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtzrhgbkzh.html

strlen(s)
来源：http://dali.hnxiangtu.top/Article/details/gttzdksbgm.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gtbrkqlxvx.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gtqfqmwwon.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gtgrksvpdq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gtybvgthin.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gtvivdlmzg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuanzx.com/Article/details/gtnliupntm.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gtkrpvejed.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gtslteumjs.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gtpuznunpn.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gtpehaocrw.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtrdpkvlox.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gtwgxdpqld.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gtdkxvrqpc.html

fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gthwkefpcb.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gttqtsfxpp.html


<!-- 参考信息 -->