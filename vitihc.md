代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cucudq.cn/Article/details/gtcjtjctqh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gtacfdkmbd.html

[Q47] 与平均值比较
来源：http://dali.ehwqpu.com/Article/details/gtcopsfial.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gtxebhhvql.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gtafwnmdew.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiopondhn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gtoiehyiek.html

[Q49] 更新单行
来源：http://dali.andypj.xyz/Article/details/gtbhojmlbr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtrpldjbke.html

[Q50] 批量更新
来源：http://dali.c1oappe.top/Article/details/gturokdgdp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gtsoavtgko.html

[Q51] 用子查询更新
来源：http://dali.xuetiantiany.cn/Article/details/gttnsgbxsc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dianchejie.cn/Article/details/gtforqvqww.html

[Q52] 删除指定行
来源：http://dali.pycfn.com/Article/details/gtjrqnomrd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtigiqzbtw.html

[Q53] 按条件删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrvvksqo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sxryk.cn/Article/details/gtqhzyxhlo.html

[Q54] 清空表
来源：http://dali.yueranfly.top/Article/details/gtrhwxcdkm.html

TRUNCATE TABLE logs;
来源：http://dali.gaohongyu789.top/Article/details/gtxcmvfjrd.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gtpwaccejr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.redwolf501.top/Article/details/gttdyhqqmk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zycfv.cn/Article/details/gtwxlkdpok.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtmpapizji.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gtqsqnfhqs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtixhdsann.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gticiabwih.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtbqtkqpnp.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gttexyjjyk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtjsqpdjdz.html

[Q60] 取上一行 / 下一行
来源：http://dali.xylfe.cn/Article/details/gtazbsnkit.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.andypj.xyz/Article/details/gtkffoikmh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtxixxvysk.html

[Q61] 移动平均
来源：http://dali.xinyue.icu/Article/details/gtggzvejpe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtflmyozit.html

[Q62] 分组占比
来源：http://dali.kuanghao11.cn/Article/details/gtpeiumbjd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtkeredjvb.html

[Q63] 开启事务
来源：http://dali.snrcjt.cn/Article/details/gtoqvsnhmn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gtccvvpppu.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gtpmrvxald.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gtjoamtlow.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gtxwywfiqn.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gtibynvcee.html

[Q66] 行锁查询
来源：http://dali.bjfxy.top/Article/details/gtgkodfleu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangshuangyany.cn/Article/details/gtusxqyesr.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gtpkyltwgx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.svipenyu.cn/Article/details/gtidrrgcks.html

[Q68] 保存点
来源：http://dali.yj20258888.top/Article/details/gtcbqfuwju.html

SAVEPOINT sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtzuydgykh.html

ROLLBACK TO sp1;
来源：http://dali.aizwys.cn/Article/details/gtcrmfyjho.html

[Q69] 查看执行计划
来源：http://dali.hammf.cn/Article/details/gtovgsqftj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tianlin.xyz/Article/details/gtlujidfbr.html

[Q70] 更新统计信息
来源：http://dali.yvedp.cn/Article/details/gtypbryknb.html

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gtfbruieig.html

[Q71] 查看建表语句
来源：http://dali.gogol.net.cn/Article/details/gtfdnekemz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaiiflvk.html

[Q72] 查看索引
来源：http://dali.cucudq.cn/Article/details/gtzuwhqwmx.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtcwdjpivk.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gtersanxya.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zdqjudy.top/Article/details/gtcniiveeo.html

[Q74] 强制使用索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbbjdzyb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gtizwgnyki.html

[Q75] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtjmcfksik.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtjpaicuqw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtnndupuox.html

[Q76] 按天统计
来源：http://dali.mhx1999.top/Article/details/gtbhdlrcgj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xylfe.cn/Article/details/gtgliovqjx.html

[Q77] 时间加减
来源：http://dali.quarkkingdee.top/Article/details/gtuselahiv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gthvfkjjjs.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gturzvtnjq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gtmxoolsxh.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gturvcetqy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxinkj.top/Article/details/gtlopvuysr.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gttymwfjhz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtvjqklqip.html

[Q81] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gtljabmanv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtyjrimjuh.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapkqdcgp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtlzltfyuj.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtoefwgcud.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzksduit.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtlrrqlrdc.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtgygtoxlq.html

[Q85] 数值取整
来源：http://dali.svipenyu.cn/Article/details/gtidiknctw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gttsplfalq.html

[Q86] 读取 JSON 字段
来源：http://dali.ivvv.top/Article/details/gtfyobrvgj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtnsnuflnt.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gtzfvujdip.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gtivohwxnd.html

[Q88] 行转列（条件聚合）
来源：http://dali.xylfe.cn/Article/details/gtqtbyocqx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fzhhl.top/Article/details/gtpffgcwyw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwzhfxjr.html

[Q89] 判断表是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtvuhsziaq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gtbeyvdqtg.html

[Q90] 生成序号列
来源：http://dali.fengsongda.top/Article/details/gtipftqfxk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gthrwgldqz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkomytbur.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gtdvajraxm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtivafxvel.html

[R01] shebang 与严格模式
来源：http://dali.c1oappe.top/Article/details/gtlkqkvhhk.html

#!/usr/bin/env bash
来源：http://dali.haohaochexian.top/Article/details/gtvzrhqxct.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gtkufqzkhc.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gteyhbuvtj.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gtokopptqx.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gtirpaxqep.html

readonly PI=3.14
来源：http://dali.smart0.xyz/Article/details/gteinqdwta.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gtydrziuwg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.iojbl.cn/Article/details/gtifeaksbh.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gtihnwzwuw.html

name="${1:-default}"
来源：http://dali.iojbl.cn/Article/details/gttefmthqf.html

[R06] 判断命令是否存在
来源：http://dali.yangfankeji.com/Article/details/gtzbfpzsko.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtnujyzbef.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzahhqpiw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtzkozricx.html

[R08] 数值比较
来源：http://dali.sufxvd.cn/Article/details/gtggveoyiw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jiagoushi.top/Article/details/gttxhfznbu.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gtnnfxntzq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gtlnezuosh.html

[R10] 正则匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtyeorkqng.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gtpmuzoaaw.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gtqfygmskr.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gtoizusulz.html

start) echo "启动" ;;
来源：http://dali.shuidangran.top/Article/details/gtsbbkntqa.html

stop)  echo "停止" ;;
来源：http://dali.cheryme.top/Article/details/gttuczbyup.html

*)     echo "未知命令" ;;
来源：http://dali.zycfv.cn/Article/details/gtpvebbnao.html

esac
来源：http://dali.ppjwa.cn/Article/details/gtixlxhpbs.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gtqitincbo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.9152youxi.cn/Article/details/gtmliqpzkc.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtimdifqqg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtkhmlkamw.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gtrtslghxd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtxptnamfc.html

[R15] while 逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gteytovdfi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ydzc1.top/Article/details/gtfuncwcln.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gtrudzjchd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gtxsnpcmkm.html

[R17] 数组定义与取值
来源：http://dali.redwolf501.top/Article/details/gtlonfkwpg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gtatqhwffu.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspbpeknm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gtqwhluqhs.html

[R19] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gtwnkhiurn.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gtmdiwhexq.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtxjfsrrqy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gtrkafquxk.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gtbklmiaxj.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gtxdlojlax.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtcttadhfy.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gtnuohatuk.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtoykxatmg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pengpengdd.cyou/Article/details/gtkxdveiwn.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtvjliwrpv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gtaosrcdfw.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinghuilouyu.cn/Article/details/gtugdsinuz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fzhhl.top/Article/details/gtdcsqvbsj.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtcigcclrb.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gthsqknoej.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gtwzovifcg.html

echo $((1 + 2 * 3))
来源：http://dali.gogol.net.cn/Article/details/gtfeekqrpv.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gtfvxexrfz.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gtdqmxaaik.html

[R29] 定义函数
来源：http://dali.xziqi.cn/Article/details/gttpkzxegp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtlremmvzm.html

[R30] 函数返回状态码
来源：http://dali.zhongyouzk.top/Article/details/gtbiguwvqb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hywenlv.cn/Article/details/gtyxmicomw.html

[R31] 局部变量
来源：http://dali.sysykeji.top/Article/details/gtqenlrpdx.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gtvyuhvucu.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gtjyoxxjvb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gttytdmtgt.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gtzdruviso.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtoiktaoiz.html

[R34] 退出时清理
来源：http://dali.0kj1m.cn/Article/details/gtfgdtvsff.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gtycwpzfpw.html

[R35] 后台执行并等待
来源：http://dali.wangshuangyany.cn/Article/details/gtahopwtwt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gtevrehech.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gtfissujdb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtgcoemajf.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gtptgyltmr.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gtgbwyqdgb.html

[R38] 管道串联
来源：http://dali.wangshuangyany.cn/Article/details/gtajkpzgoh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guowangkeji.top/Article/details/gtzfjtsmve.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gtefabkpok.html

cmd > out.log 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtdcwczsus.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gtuoattjhr.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gtanavchpl.html

[R41] 丢弃输出
来源：http://dali.yangfankeji.com/Article/details/gtsaeotsjf.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gtlpecmhwz.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gtvkffjsvt.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gtucwprgih.html

[R43] 按名字查找文件
来源：http://dali.snrcjt.cn/Article/details/gtwupcmjko.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gtmdykuqhe.html

[R44] 按修改时间查找
来源：http://dali.zhixingplan.top/Article/details/gtxfczhokk.html

find . -mtime -7 -type f
来源：http://dali.xziqi.cn/Article/details/gtacoepxhv.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gtchkupfxl.html

find . -name "*.tmp" -delete
来源：http://dali.vqdsnc.cn/Article/details/gtlvhyudrg.html

[R46] 递归替换文件内容
来源：http://dali.hywenlv.cn/Article/details/gtcqneiirb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuxming.cn/Article/details/gtbhvdjdum.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gtxxooudpe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtklofxqyp.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gtjdnncjdm.html

awk '{print $1, $3}' a.txt
来源：http://dali.pycfn.com/Article/details/gtnrrpqjus.html

[R49] awk 带条件
来源：http://dali.ydzc1.top/Article/details/gtjoufyuzo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtgphyhbfr.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gtkdddjxvr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtsuznccqg.html

[R51] 排序去重取前几
来源：http://dali.quarkkingdee.top/Article/details/gtyydluxwb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.quarkkingdee.top/Article/details/gtlnnwshaa.html

[R52] 统计行数
来源：http://dali.pycfn.com/Article/details/gttszxwjhm.html

wc -l a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtkdigeyyq.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gtbickraut.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.snrcjt.cn/Article/details/gtlnihhjrm.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gtborxroyr.html

diff a.txt b.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcziubso.html

[R55] 压缩与解压
来源：http://dali.jiagoushi.top/Article/details/gtdqjjanhn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gtzmufxpmi.html

[R56] 远程拷贝
来源：http://dali.jiagoushi.top/Article/details/gtprakabtk.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gtfrwcxcgj.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gthxnsucfz.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsfrniez.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gtqkgrpwsy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.316326.xyz/Article/details/gtrbnxhnxz.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtnjydskwa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgufenzy.top/Article/details/gtttagdfzq.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtqgtzwdgg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gtbstuufnt.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gtcazgmfis.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gtoazmvlvj.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gtyapmuhel.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gtbxgouvyc.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gtpaprabce.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gtbvuyijip.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gtscatkyzs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuanzhike.top/Article/details/gthooakvhp.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gtkajguibr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gtidwawwvc.html

[R66] 定时任务
来源：http://dali.gogol.net.cn/Article/details/gtzemiissg.html

crontab -e;  crontab -l
来源：http://dali.tianlin.xyz/Article/details/gtkyuznbnk.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gtahjkphgb.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gtvjajfppm.html

[R68] 计算文件校验值
来源：http://dali.birdmap.top/Article/details/gtucwddmff.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfgkoshp.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gthcxxqord.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gtcveugsyc.html

[R70] 时间戳与互转
来源：http://dali.jiagoushi.top/Article/details/gtefezxuwv.html

date +%s;  date -d @1700000000
来源：http://dali.nwbrower.top/Article/details/gtenkbqnnt.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtnlhbbonf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtjsgwpjqs.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gtjrazwbee.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtmfspigiw.html

[R73] 分割大日志
来源：http://dali.bjfxy.top/Article/details/gttycypgyp.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gtsqjxkcje.html

[R74] 批量重命名
来源：http://dali.yj20258.top/Article/details/gtftadjmgm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gtgrjsctel.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gtfmwlncxe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuxming.cn/Article/details/gtivljjoxb.html

[R76] 使用临时文件
来源：http://dali.shuidangran.top/Article/details/gtvacwqayt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gttjafwdfb.html

[R77] 读取用户输入
来源：http://dali.316326.xyz/Article/details/gtwpdfwepn.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gthdqocmph.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gtmwxpsllt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zycfv.cn/Article/details/gtwsvbnbyq.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gtdbyaelou.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gogol.net.cn/Article/details/gttgaqswlp.html

[R80] 查看脚本执行耗时
来源：http://dali.tian-w.cn/Article/details/gthchwvmro.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gtexknvmep.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtoafcsxrs.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gtagmfuhkh.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtfbsuirwt.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gtgdenmqya.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gtvnevowiv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gtfqnfoopi.html

[S02] C：变量与格式化输出
来源：http://dali.xinyue.icu/Article/details/gtzipjdhfh.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtblcxdtps.html

[S03] C：读入整数
来源：http://dali.jinqigufen.top/Article/details/gtqbxklqnm.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtedyefddt.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gtrsfnhqmq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gtcenxfnyc.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtxzgswudc.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gthfktsthr.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtcmihohnn.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gtnsshxyho.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gtgcpsioxp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gtsnoffufw.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gtjuvyagit.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gtiakywwsh.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gttgpglbzl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gtanvlrgkv.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gttorfkxzf.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gtaoizsmqi.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajlvgufy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gtqcswdqbx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgfzy.top/Article/details/gtjjzlsfjw.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqksugfps.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtoztorfbc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtrvbytigb.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gttdmlwdcg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gtvegyslgg.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gtnbjkinoj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gtqddkvvbj.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtzrbczpgs.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gtehsntjud.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gtnwglrtbg.html


<!-- 参考信息 -->