代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gaohongyu789.top/Article/details/gthngvngle.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtrapsrkkb.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gtfdlqdloy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aibaodan.cn/Article/details/gtijdfnwcr.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxinkj.top/Article/details/gtothmohgw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduvaxckx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyslnbcbq.html

[Q49] 更新单行
来源：http://dali.zhixingplan.top/Article/details/gtrctjwtke.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gtumpxhshi.html

[Q50] 批量更新
来源：http://dali.birdmap.top/Article/details/gtzxjsnquy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtgjxtudjl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gtlsxvauau.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gthazockvu.html

[Q52] 删除指定行
来源：http://dali.zhongyouzk.top/Article/details/gtlznkscej.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtegvaoqpq.html

[Q53] 按条件删除
来源：http://dali.shuidangran.top/Article/details/gtnkxkpvlk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtczjmfchi.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gtubgphjcz.html

TRUNCATE TABLE logs;
来源：http://dali.hfpthk.cn/Article/details/gtutkwlhzt.html

[Q55] 排名（并列占位）
来源：http://dali.vqdsnc.cn/Article/details/gtuzhfewpr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cheryme.top/Article/details/gtumhylkqs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aizwys.cn/Article/details/gtyealhswk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtjbgcvbdz.html

[Q57] 行号
来源：http://dali.zhiwuduotai.top/Article/details/gtxebxtsmr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtzkqowfmd.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gtnendtnzt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtisuwxbkx.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtlzhohita.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtrocfcatd.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gtgmwvujup.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shangyingyoupin.top/Article/details/gtogbgcfet.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yongpay.top/Article/details/gttzymijvl.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gtybnznmqe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtmspfsukc.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gtujlpepyl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtgmpqczkg.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gtthuuypxt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hfpthk.cn/Article/details/gtptadwwdf.html

[Q64] 提交事务
来源：http://dali.dashuyun.cn/Article/details/gtbwadpxmi.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gtdhupudob.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gtwhvvtmuj.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gtpmnotsbh.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gtwveqdkta.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xylfe.cn/Article/details/gtmcyfprja.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gtqkrenfsr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gtbaazqrdm.html

[Q68] 保存点
来源：http://dali.c1oappe.top/Article/details/gtxxfpsvfo.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gtradrhrms.html

ROLLBACK TO sp1;
来源：http://dali.yueranfly.top/Article/details/gtefkljvkr.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gtwujtofkb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gtgqnnzahh.html

[Q70] 更新统计信息
来源：http://dali.zhongyouzk.top/Article/details/gtuqjudugw.html

ANALYZE TABLE users;
来源：http://dali.redwolf501.top/Article/details/gtrcluvkco.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gtzwxilwhj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhekjhgl.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gtiooestaf.html

SHOW INDEX FROM users;
来源：http://dali.yvedp.cn/Article/details/gtlkvvwzwb.html

[Q73] 查看表状态
来源：http://dali.aibaodan.cn/Article/details/gtphxsdedn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tianlin.xyz/Article/details/gtsrkcoyer.html

[Q74] 强制使用索引
来源：http://dali.tian-w.cn/Article/details/gtzswyeuew.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gtseqrqybb.html

[Q75] 日期格式化
来源：http://dali.yonumen.top/Article/details/gteavwxsqe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtcqgfblzq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cdnleiting.top/Article/details/gtnemncdwn.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gtuzhrfgqx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yueranfly.top/Article/details/gtdipgakiy.html

[Q77] 时间加减
来源：http://dali.fengsongda.top/Article/details/gttozrqpzz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gteaqeopac.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gthkgszejl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.andypj.xyz/Article/details/gtmwlmmvda.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtfgitldlv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.mhx1999.top/Article/details/gtswfhmqpz.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gtonugbeqj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtdkxnlqdg.html

[Q81] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtnpfxuqha.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gtpfubtigy.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtrficptqp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtxynnlmck.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbbxzvzp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtmvbqushf.html

[Q84] 去除首尾空格
来源：http://dali.jinqigfzy.top/Article/details/gtfrvtwcnz.html

SELECT TRIM(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtsxnaogut.html

[Q85] 数值取整
来源：http://dali.gogol.net.cn/Article/details/gtydkvvqpl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gtxdziqmix.html

[Q86] 读取 JSON 字段
来源：http://dali.yonumen.top/Article/details/gtuhokynch.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gtoudwruxt.html

[Q87] JSON 字段做条件
来源：http://dali.yonumen.top/Article/details/gtaahojphj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gttkqfljxb.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtccwkhblq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jianghu66.top/Article/details/gtpasyrrnd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gtknoxavjl.html

[Q89] 判断表是否存在
来源：http://dali.9152youxi.cn/Article/details/gtqsavbjts.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xylfe.cn/Article/details/gtfjcoykps.html

[Q90] 生成序号列
来源：http://dali.shuidangran.top/Article/details/gtowmzqbak.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlzynvxv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtlfsbwqnx.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gtynfuibsk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtutbmknzs.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gtwyohdras.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtvpbuaqof.html

set -euo pipefail
来源：http://dali.316326.xyz/Article/details/gtzulqkxmp.html

[R02] 变量赋值与使用
来源：http://dali.0kj1m.cn/Article/details/gttfvubyxe.html

name="Tom"; echo "$name"
来源：http://dali.bjfxy.top/Article/details/gtduiwxygh.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gtbmxnmlpr.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtzikbmkdd.html

[R04] 位置参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqxlxeoc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.smart0.xyz/Article/details/gtyzlujnzk.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gtxinlfpkl.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gtjhtsnoms.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtogpeqtlv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtqjdnzbad.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gtkbcpygwu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gtujjlslou.html

[R08] 数值比较
来源：http://dali.dianchejie.cn/Article/details/gtggbfurph.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.haohaochexian.top/Article/details/gtwiuqfzbl.html

[R09] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtexzqjosu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtkxhatmrg.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gtzfuiblok.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtmlutturq.html

[R11] case 多分支
来源：http://dali.ybcxt.top/Article/details/gtlbsvybyz.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gtwqqzbuyn.html

start) echo "启动" ;;
来源：http://dali.gzhubu.top/Article/details/gttgtehlxf.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gtguaypmbg.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtfpxzyxji.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjdihcsh.html

[R12] for 遍历文件
来源：http://dali.gotoacloud.top/Article/details/gtlmlxetxk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gtxgqihboy.html

[R13] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gtirchtrcx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtgghoyerm.html

[R14] C 风格 for
来源：http://dali.yuanzhike.top/Article/details/gtjwuyskpq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtcpxoqxum.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gtzbfrrgwt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtejdpurdr.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gtecenbnsu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtyfupnqkd.html

[R17] 数组定义与取值
来源：http://dali.cqqwz.cn/Article/details/gtioqibipa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuxming.cn/Article/details/gtousnrtzw.html

[R18] 遍历数组
来源：http://dali.yanxiufei.cn/Article/details/gtcxfanktn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gtibnffrpy.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtdxdnalhz.html

echo "${#arr[@]}"
来源：http://dali.shzxlz.cn/Article/details/gtvxtnkkrr.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gtvnueduni.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtrpmyzasm.html

[R21] 字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtwlfnrrnp.html

echo "${#s}"
来源：http://dali.xylfe.cn/Article/details/gttshedgap.html

[R22] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtuzoybbij.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gtsieyuctc.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtlunwjtwl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gtsyhlublj.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtyaitirir.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gtvfvyxcnt.html

[R25] 去后缀 / 去前缀
来源：http://dali.hfpthk.cn/Article/details/gtqmrkyxtk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmysznnpy.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gtfqptfpyc.html

now=$(date +%F); echo "$now"
来源：http://dali.yonumen.top/Article/details/gtmhzgarsw.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gtbsupafwl.html

echo $((1 + 2 * 3))
来源：http://dali.hfpthk.cn/Article/details/gtqyxrqwac.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gtpvkwqkgv.html

echo "scale=2; 10/3" | bc
来源：http://dali.gotoacloud.top/Article/details/gthxqprmvi.html

[R29] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtkqymaefw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gtmktplkpb.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gtserwatvf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gtppeyzopr.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtpgizwrhd.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gtlnqsecuq.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckjmguxl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gtlmxxhsyx.html

[R33] 捕获错误并提示行号
来源：http://dali.shuidangran.top/Article/details/gtcqlfbsug.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zycfv.cn/Article/details/gthvblijry.html

[R34] 退出时清理
来源：http://dali.tanke756.top/Article/details/gtrzggamoj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gtlpwohlgu.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gtctjnconl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gthrgckqth.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gtharuawhx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ivvv.top/Article/details/gtsenppyem.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gtjwfmcuwg.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gtdnccwxsv.html

[R38] 管道串联
来源：http://dali.yongpay.top/Article/details/gtstkokcbr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gtfucjjxzb.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gtsbyxktym.html

cmd > out.log 2>&1
来源：http://dali.redwolf501.top/Article/details/gtiavauckx.html

[R40] 追加写日志
来源：http://dali.hammf.cn/Article/details/gtvwfafbkb.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gtevgoppzj.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gtsvuuschu.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtodjjbolr.html

[R42] 输入重定向
来源：http://dali.yuanzhike.top/Article/details/gtfqcvwvwz.html

wc -l < a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnxxwcml.html

[R43] 按名字查找文件
来源：http://dali.gotoacloud.top/Article/details/gtzxtvlsax.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gtwlknjosa.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgzeaomf.html

find . -mtime -7 -type f
来源：http://dali.svipenyu.cn/Article/details/gtbssakceq.html

[R45] 批量删除
来源：http://dali.zdqjudy.top/Article/details/gtqrvuzlqx.html

find . -name "*.tmp" -delete
来源：http://dali.snrcjt.cn/Article/details/gtdwdxnryd.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gtdwpbybjm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gtevwvnemv.html

[R47] sed 单行替换
来源：http://dali.dianchejie.cn/Article/details/gtozhwbkoq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtzmgkedvl.html

[R48] awk 取指定列
来源：http://dali.xuetiantiany.cn/Article/details/gtcumjqtwc.html

awk '{print $1, $3}' a.txt
来源：http://dali.guannengcc.top/Article/details/gtzydqogbw.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdjmmtea.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jyoumei.cn/Article/details/gtpjexuxkr.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gtuvkyjlzz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtbygqejzm.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gtttfpqpid.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gtbhqvunvn.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gtddllnhdt.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gtehbbspss.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gtkhoecicj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gtoabsklfx.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gtrmnxhoig.html

diff a.txt b.txt
来源：http://dali.tanke756.top/Article/details/gtqfujdcyl.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gtidjydkmv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gtitkezamv.html

[R56] 远程拷贝
来源：http://dali.chenlongwang.top/Article/details/gtdxkxuhyv.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gtdtvtsnlg.html

[R57] 远程执行命令
来源：http://dali.yuxming.cn/Article/details/gtuwmbgxqk.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gtvyifvfwc.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gtedwzokpo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gtjcgbjeed.html

[R59] 发 POST JSON
来源：http://dali.yj202588.top/Article/details/gtpltjphra.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gttkocqdqq.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtblvexbmy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zycfv.cn/Article/details/gtduavgnxf.html

[R61] 磁盘占用
来源：http://dali.tian-w.cn/Article/details/gtqonnnejd.html

df -h;  du -sh *
来源：http://dali.yangfankeji.com/Article/details/gtxqoqeizp.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmyijwxpf.html

du -ah . | sort -rh | head -10
来源：http://dali.9152youxi.cn/Article/details/gtiauyhpaa.html

[R63] 内存与进程
来源：http://dali.hfpthk.cn/Article/details/gtgaikzuki.html

free -h;  ps aux | grep nginx
来源：http://dali.sweek.top/Article/details/gtzpnsyvds.html

[R64] 结束进程
来源：http://dali.sufxvd.cn/Article/details/gtnvqljkzt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gtwyjrbpev.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gtwcltgpcr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gtssdyouyz.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gtgowddtdn.html

crontab -e;  crontab -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfapohqyi.html

[R67] 生成随机十六进制串
来源：http://dali.jyoumei.cn/Article/details/gtbdmtcbco.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gtkrsfllwn.html

[R68] 计算文件校验值
来源：http://dali.kuanghao11.cn/Article/details/gtjvhdqluv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gotoacloud.top/Article/details/gtmwqbxmti.html

[R69] 生成随机密码
来源：http://dali.tanke756.top/Article/details/gtawdhjymq.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtlwkvxxyo.html

[R70] 时间戳与互转
来源：http://dali.nwbrower.top/Article/details/gtsekdmipk.html

date +%s;  date -d @1700000000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttebpcuti.html

[R71] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtufitxdvn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.0kj1m.cn/Article/details/gtbvrtufxh.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gtwlvjsvga.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtlonerttj.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gtqhcmaydm.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gtmahmnthe.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gtssxrsgrp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gtskbdcpbq.html

[R75] 导出环境变量
来源：http://dali.tanke756.top/Article/details/gtfhsjldnq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gthhfkfhxc.html

[R76] 使用临时文件
来源：http://dali.redwolf501.top/Article/details/gtwfhpjvfb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtggvirnpp.html

[R77] 读取用户输入
来源：http://dali.bjfxy.top/Article/details/gtgmwgzdit.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gtgozcmfbi.html

[R78] 交互式菜单
来源：http://dali.hnqzz.top/Article/details/gtqcpdpzpt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtvjlcfdpx.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gtsyjknjhf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gtiopkospt.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gtxdyniijk.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gtssuqqemn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvwvsgrla.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtyaidkifk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gttpqfeoxu.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gtywimdltd.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gtnufxzztx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuysmsugl.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gtqcacekad.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gthtshlsla.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsygtmtfu.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gtggrobgzp.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gtstlphumb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuoutnjkt.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gtdwceeozn.html

strlen(s)
来源：http://dali.chenlongwang.top/Article/details/gtfqfrfqhz.html

[S06] C：字符串比较
来源：http://dali.xuanzx.com/Article/details/gtsmxxmrpp.html

strcmp(a, b) == 0
来源：http://dali.9152youxi.cn/Article/details/gtwolpgbij.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gtkdfiapuh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.svipenyu.cn/Article/details/gtpxzzpwea.html

[S08] C：动态内存分配与释放
来源：http://dali.pycfn.com/Article/details/gtaunyoqse.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shuidangran.top/Article/details/gtxmpkgzgt.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258.top/Article/details/gtgnrgrxxc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gtwnzstgok.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gtocjyjsgr.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gtueudsibh.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtnwryxdcr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gtjvuaomuw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuanzx.com/Article/details/gtijnldgxz.html

fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtwexbkwmm.html

[S12] C：写文件
来源：http://dali.svipenyu.cn/Article/details/gtmkebbaxt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gthvbjixxg.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gtbapupmek.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yangfankeji.com/Article/details/gtqfpzbduo.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gtnlqwmunn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj202588.top/Article/details/gtkhimijwi.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gtqqqtbygz.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gttgmkrvzu.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gtymhbricc.html


<!-- 参考信息 -->