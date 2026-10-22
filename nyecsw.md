代发 wailian999

[Q44] IN 子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttimftdrg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shangyingyoupin.top/Article/details/gtcdamzsqu.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gtgoifkqnu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtrofwkose.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yvedp.cn/Article/details/gtzeydgdmx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnckhawcg.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gtfpvlnwff.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.c1oappe.top/Article/details/gtglosyjcd.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxuanxn.top/Article/details/gtkndnzveg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xylfe.cn/Article/details/gtcrzjgbre.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhixingplan.top/Article/details/gthdlgbvwd.html

[Q49] 更新单行
来源：http://dali.guannengcc.top/Article/details/gtyefwgyzz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtxnnkweno.html

[Q50] 批量更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycgaqrkh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxinkj.top/Article/details/gttejecxdo.html

[Q51] 用子查询更新
来源：http://dali.zhixingplan.top/Article/details/gtjaswodps.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shuidangran.top/Article/details/gtwwimbxnd.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gtuuhgozgx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtavajclem.html

[Q53] 按条件删除
来源：http://dali.svipenyu.cn/Article/details/gtwheyoeyv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gtenptexjb.html

[Q54] 清空表
来源：http://dali.xziqi.cn/Article/details/gtwksktccw.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gtkrvcegfq.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gtkvytzktu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtfxbzqwqz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhengqikj.top/Article/details/gtgxnzwovi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtzofydtes.html

[Q57] 行号
来源：http://dali.havefunace.top/Article/details/gttzbaqdmz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gthgriqkcw.html

[Q58] 累计求和
来源：http://dali.jinqigufen.top/Article/details/gtvykxtaxc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtpszzkeng.html

[Q59] 分组内累计
来源：http://dali.shzxlz.cn/Article/details/gtsbfjoacj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtgogsuvin.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gtsaxdukwd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gtgvkwrubf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtccluwwhk.html

[Q61] 移动平均
来源：http://dali.daxiang520.top/Article/details/gtlkncuezl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtrxsexzgp.html

[Q62] 分组占比
来源：http://dali.zhoulong.xyz/Article/details/gtiwvfutii.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtynxpfpdp.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gtdpfgusoq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cdnleiting.top/Article/details/gtrobxbwpn.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtmwfgyixg.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gtxybdfatx.html

[Q65] 回滚事务
来源：http://dali.shuidangran.top/Article/details/gtbzqlfbhu.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gtaitovydb.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gthwdhqyhd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zdqjudy.top/Article/details/gteobuqogt.html

[Q67] 设置隔离级别
来源：http://dali.shangyingyoupin.top/Article/details/gtwbwzckum.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenlongwang.top/Article/details/gtuptaratd.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gtcsnierxg.html

SAVEPOINT sp1;
来源：http://dali.fzhhl.top/Article/details/gthkhwouvy.html

ROLLBACK TO sp1;
来源：http://dali.tianlin.xyz/Article/details/gtmfodgbbs.html

[Q69] 查看执行计划
来源：http://dali.zdqjudy.top/Article/details/gtncllnsjk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnxiangtu.top/Article/details/gtzizrewil.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gtebjmmhjv.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyveqkram.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekdrfqia.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gtdcnppjql.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gtyzndrdbn.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtuijlnxoo.html

[Q73] 查看表状态
来源：http://dali.gogol.net.cn/Article/details/gtjfrlbyzt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.bjfxy.top/Article/details/gtthpfzxqu.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gtrnhcmnpg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.9152youxi.cn/Article/details/gtcaoxapft.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgjrswng.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtpshsyijv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yonumen.top/Article/details/gtkgvwbwjv.html

[Q76] 按天统计
来源：http://dali.yangfankeji.com/Article/details/gtehskkrkl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.feifeiyinyue.top/Article/details/gttkdwdsul.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzoxchqd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtuvgoxzgk.html

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gtntcxwnmc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtgzddsahq.html

[Q79] 字符串拼接
来源：http://dali.gzhubu.top/Article/details/gtxresbnje.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zdqjudy.top/Article/details/gtrwjmjlam.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gtyewwbxyj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtiycmocxo.html

[Q81] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtljuiagni.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtxbezwflh.html

[Q82] 字符长度与字节长度
来源：http://dali.pycfn.com/Article/details/gtykuchhtk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtvlybezay.html

[Q83] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtlyuzfgak.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtciqsqqbz.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtnouqpfcf.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtiobwfxub.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtuholqx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gtmpazywrt.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gtdicvwhtp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuanzx.com/Article/details/gtxkkjzsuh.html

[Q87] JSON 字段做条件
来源：http://dali.cucudq.cn/Article/details/gteeibgoky.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gtrwiczsdd.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtnazrpopb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gtfzohbsqd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gtgbgvccqd.html

[Q89] 判断表是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtxjhhinoh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shuidangran.top/Article/details/gtuwnftoki.html

[Q90] 生成序号列
来源：http://dali.yuanzhike.top/Article/details/gtjgwoxrqe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtcwcavcqg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtzupnjgum.html

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gtliaggrmz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjpdoskzv.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtkckwcoby.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gtzhyoythv.html

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gtemewyyon.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gtblychctu.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtoqnuydnr.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gtzljctqur.html

readonly PI=3.14
来源：http://dali.nanxinkj.top/Article/details/gtqqpreygo.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gtwftwwlpq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gtmvjyjmwv.html

[R05] 参数默认值
来源：http://dali.yuxming.cn/Article/details/gtbgwkzdpa.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gtaznvrzqr.html

[R06] 判断命令是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtlgldmrlu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtzgwyihxa.html

[R07] if 判断文件
来源：http://dali.9152youxi.cn/Article/details/gticuyeicn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guowangkeji.top/Article/details/gtncudjtra.html

[R08] 数值比较
来源：http://dali.ivvv.top/Article/details/gtpxahttwn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gtluaeirxk.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtuhdbhllr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ehwqpu.com/Article/details/gtootnkjbf.html

[R10] 正则匹配
来源：http://dali.birdmap.top/Article/details/gtewqkporo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawcjeaxv.html

[R11] case 多分支
来源：http://dali.hongshengwenyu.top/Article/details/gtwnmgesig.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gtqnvnsjab.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gtqekybhso.html

stop)  echo "停止" ;;
来源：http://dali.dianchejie.cn/Article/details/gtzhjzkqao.html

*)     echo "未知命令" ;;
来源：http://dali.yuxming.cn/Article/details/gtjqdakuof.html

esac
来源：http://dali.zhengqikj.top/Article/details/gtcrpwsamu.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gteunexblw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ydzc1.top/Article/details/gtextcfpgy.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gtgageqpya.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gtxmlvsxzg.html

[R14] C 风格 for
来源：http://dali.zhongyouzk.top/Article/details/gtrugasmca.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gtjizgcode.html

[R15] while 逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtstdzjudt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gtcvgnsnzs.html

[R16] until 等待条件
来源：http://dali.gotoacloud.top/Article/details/gttcmxzsgd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtoasaqmiy.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gtuvloclul.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtmqckkmny.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gtoeajpgkj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gtebqfpzxc.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gtnshjuuau.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gtyyyaojdk.html

[R20] 关联数组（字典）
来源：http://dali.yj202588.top/Article/details/gtfzirklzl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gtitdbvfjb.html

[R21] 字符串长度
来源：http://dali.jianghu66.top/Article/details/gtaqjsmmwm.html

echo "${#s}"
来源：http://dali.aizwys.cn/Article/details/gtpiltkhtk.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gtelkcfyba.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gtywtbspgg.html

[R23] 字符串替换
来源：http://dali.sweek.top/Article/details/gtssuwsbnj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gtnbvmjfmy.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtdszhygto.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gtuqkiylxb.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gtttfglzgi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnxiangtu.top/Article/details/gtppydiwdx.html

[R26] 命令替换
来源：http://dali.cdnleiting.top/Article/details/gtxgdrxfxo.html

now=$(date +%F); echo "$now"
来源：http://dali.birdmap.top/Article/details/gtdmflnzvg.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gtfbcrgfzh.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gtwjalkmzu.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvkvfdql.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gtfuccshka.html

[R29] 定义函数
来源：http://dali.316326.xyz/Article/details/gtzdjhoxsg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gtpxnuxizr.html

[R30] 函数返回状态码
来源：http://dali.yj20258.top/Article/details/gtnxherueu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gtbpqpziuu.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gthzceehyg.html

f() { local x=1; echo "$x"; }
来源：http://dali.ybcxt.top/Article/details/gthwhrtlzq.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gtsgfdkfar.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtifzlzjrl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gtvwxanddu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gttdptkoay.html

[R34] 退出时清理
来源：http://dali.tian-w.cn/Article/details/gtiofpcddd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtpewqjxoo.html

[R35] 后台执行并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtvvmbmlfa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdcbsmdv.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gtsgomwlav.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gtcydxnznu.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gtwzbsxifj.html

files=$(ls -1)
来源：http://dali.yonumen.top/Article/details/gtaqphfnjx.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gtehajiswe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gtciemzbyh.html

[R39] 重定向标准输出与错误
来源：http://dali.chenlongwang.top/Article/details/gtaggkhacm.html

cmd > out.log 2>&1
来源：http://dali.xinyue.icu/Article/details/gtbzwjbqrp.html

[R40] 追加写日志
来源：http://dali.dashuyun.cn/Article/details/gtomtlvpjp.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtpexcyqxe.html

[R41] 丢弃输出
来源：http://dali.bjfxy.top/Article/details/gtcglfpxho.html

cmd >/dev/null 2>&1
来源：http://dali.zycfv.cn/Article/details/gtfcbphago.html

[R42] 输入重定向
来源：http://dali.nanxinkj.top/Article/details/gthghyogmb.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtndwhfxuy.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gttaoqiwle.html

find . -name "*.log" -type f
来源：http://dali.jiagoushi.top/Article/details/gtjuqwzzhm.html

[R44] 按修改时间查找
来源：http://dali.gogol.net.cn/Article/details/gttncbzjel.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gtwuatlarq.html

[R45] 批量删除
来源：http://dali.shangyingyoupin.top/Article/details/gtafmzzfad.html

find . -name "*.tmp" -delete
来源：http://dali.yonumen.top/Article/details/gtpxlsaigb.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtqqmcqthk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gtlaxcotzq.html

[R47] sed 单行替换
来源：http://dali.tianlin.xyz/Article/details/gtcbygitwx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeixejlj.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gtohchnbiz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtbjgvbexs.html

[R49] awk 带条件
来源：http://dali.tanke756.top/Article/details/gtwfopmxpe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.feifeiyinyue.top/Article/details/gtwcgbveop.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtbatqagyj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtciqcikhb.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gtyftkoaxp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gtbnxilwjc.html

[R52] 统计行数
来源：http://dali.iojbl.cn/Article/details/gtrgggwltm.html

wc -l a.txt
来源：http://dali.gzhubu.top/Article/details/gtqblmvlla.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gtygrwrepv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yangfankeji.com/Article/details/gtsnlzqywx.html

[R54] 比较两个文件
来源：http://dali.jiagoushi.top/Article/details/gtaxhxhvkd.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gtjtwvwgmk.html

[R55] 压缩与解压
来源：http://dali.sysykeji.top/Article/details/gtanpzzgim.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjonqhjdp.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gtryjtcapp.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gtsazlbvsu.html

[R57] 远程执行命令
来源：http://dali.sufxvd.cn/Article/details/gtnqaizjhm.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gthdmonzup.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gthqhxzxzs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gtffnyiack.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtwdutnigd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gtbzscufcf.html

[R60] 只看 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gtlmccegxg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ppjwa.cn/Article/details/gttjfoyobe.html

[R61] 磁盘占用
来源：http://dali.c1oappe.top/Article/details/gtcbkxgvgz.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gtlkyngprk.html

[R62] 找最占空间的文件
来源：http://dali.zhixingplan.top/Article/details/gtdncrutxf.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gtxvxvrotk.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gtmbpeoluf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gtnppyfwgf.html

[R64] 结束进程
来源：http://dali.vqdsnc.cn/Article/details/gtqydzuzrj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwqujgbi.html

[R65] 查看端口占用
来源：http://dali.hywenlv.cn/Article/details/gtkerrdarn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cashguo.top/Article/details/gtramkzypr.html

[R66] 定时任务
来源：http://dali.mhx1999.top/Article/details/gtubkvlmrz.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gtxtrpjguy.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gtetkgqmav.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gtuswzgnvt.html

[R68] 计算文件校验值
来源：http://dali.hongshengwenyu.top/Article/details/gtcmqeafpo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtgtqalgra.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gtmabaktdx.html

head -c 16 /dev/urandom | base64
来源：http://dali.jianghu66.top/Article/details/gtegciephu.html

[R70] 时间戳与互转
来源：http://dali.cucudq.cn/Article/details/gtsjkfdqog.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gtxwofwrws.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtkduwohwh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gtksdbvnpl.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtphvlojsg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtfuxwjcrr.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gtytoglwzu.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gtfzwljivy.html

[R74] 批量重命名
来源：http://dali.tian-w.cn/Article/details/gtndajidpy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gtlyxhhiea.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtkmumkptd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gtjmxaiayk.html

[R76] 使用临时文件
来源：http://dali.gzhubu.top/Article/details/gtywezwlex.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtfafoncfp.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gtlopsrbwd.html

read -rp "请输入: " ans
来源：http://dali.ybcxt.top/Article/details/gtjptlsuux.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gtqezopsmt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guowangkeji.top/Article/details/gtmvmlkhcs.html

[R79] 解析命令行选项
来源：http://dali.guannengcc.top/Article/details/gtqatyjhzy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gtpaurjglu.html

[R80] 查看脚本执行耗时
来源：http://dali.svipenyu.cn/Article/details/gtrmsnomku.html

time ./run.sh
来源：http://dali.yj20258888.top/Article/details/gthxrantgt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgcidmolx.html

S. C / C++ 专题
来源：http://dali.fzhhl.top/Article/details/gtvytwkkeb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gthuvnnjuq.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtdhmdngvk.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gtsxikbzqo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gtmqlkulgk.html

[S02] C：变量与格式化输出
来源：http://dali.yvedp.cn/Article/details/gtaufeytib.html

int a = 10; printf("%d\n", a);
来源：http://dali.hfpthk.cn/Article/details/gtkaehsiur.html

[S03] C：读入整数
来源：http://dali.birdmap.top/Article/details/gtpiaafrow.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gtyyrtwudr.html

[S04] C：字符串复制
来源：http://dali.xuetiantiany.cn/Article/details/gtaxpvrgyn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gtnztfayod.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtfiblkxgx.html

strlen(s)
来源：http://dali.hnxiangtu.top/Article/details/gttumbefvc.html

[S06] C：字符串比较
来源：http://dali.nwbrower.top/Article/details/gtcoieabwd.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gtdvucffhi.html

[S07] C：数组遍历求和
来源：http://dali.shuidangran.top/Article/details/gtibodvgmx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.havefunace.top/Article/details/gtohkvzjbd.html

[S08] C：动态内存分配与释放
来源：http://dali.ivvv.top/Article/details/gtumnbgiyz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpopaclu.html

[S09] C：结构体定义与初始化
来源：http://dali.xuetiantiany.cn/Article/details/gttgftpqtz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gtcmxeqoqj.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gtcysvbait.html

int *p = &a;  *p = 5;
来源：http://dali.0kj1m.cn/Article/details/gtpvnjojav.html

[S11] C：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtaoejpkqk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gtvtxzwnwb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtkubirdzf.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtfeitgsgu.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gtkozsqkse.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gteviodydi.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gtqcekgesp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigufen.top/Article/details/gtuxtbuxji.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtifzcrejh.html


<!-- 参考信息 -->