代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadgzosoo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gtawohzmcg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtwmliketk.html

[Q41] 多表连接
来源：http://dali.kuanghao11.cn/Article/details/gtuwwkvzoa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.andypj.xyz/Article/details/gtaebcytdr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gtpctvbgpl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gtsyfwehbm.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gtfvpyrpgd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuxming.cn/Article/details/gtfhudzmtj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtlyarapdb.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtekldzugn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hywenlv.cn/Article/details/gtqztprykz.html

[Q44] IN 子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtwjfhpunu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenlongwang.top/Article/details/gtdqpoqdof.html

[Q45] EXISTS 判断存在
来源：http://dali.yuanzhike.top/Article/details/gtnbfzbzos.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtblarsqzw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gtklujuwwe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtaqdbabxb.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gtewunkbuu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowrfshka.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxuanxn.top/Article/details/gtrwpdaqco.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gtpzfokyhd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gtuzcqwcfn.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gtiydmwlxs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtjhabtzra.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gtdojeyhzr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufbevzdn.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gtqjawwfob.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gtyrgvbkki.html

[Q52] 删除指定行
来源：http://dali.hysaishi.cn/Article/details/gtksleqcnj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtsqknnboi.html

[Q53] 按条件删除
来源：http://dali.yonumen.top/Article/details/gtwtimtyfh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtjcwmmjzo.html

[Q54] 清空表
来源：http://dali.cucudq.cn/Article/details/gtuuzgkwsp.html

TRUNCATE TABLE logs;
来源：http://dali.redwolf501.top/Article/details/gtqwtmorwf.html

[Q55] 排名（并列占位）
来源：http://dali.shzxlz.cn/Article/details/gtndttllga.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtkisnxuil.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtthiurjkg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtpcohbwmi.html

[Q57] 行号
来源：http://dali.hnqzz.top/Article/details/gtewzdvvca.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtzhkcfzcj.html

[Q58] 累计求和
来源：http://dali.xinyue.icu/Article/details/gtwazxpjhy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtvouvwaql.html

[Q59] 分组内累计
来源：http://dali.tianlin.xyz/Article/details/gtufiqlzlv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtheodlhvt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gtlysotady.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.c1oappe.top/Article/details/gtciatocmu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdwlsigl.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gtkdnymupv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtcvuymowb.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gtfqkzoknb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtsrgmpvvo.html

[Q63] 开启事务
来源：http://dali.zhiwuduotai.top/Article/details/gtwudlfolj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.bjfxy.top/Article/details/gtzhazfgee.html

[Q64] 提交事务
来源：http://dali.zhiwuduotai.top/Article/details/gtfliildit.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gtpmuiayqk.html

[Q65] 回滚事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmaeuxlh.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gtjuzmivyb.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gtinkjyghb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gtirbvinck.html

[Q67] 设置隔离级别
来源：http://dali.yj202588.top/Article/details/gtkrhpmuqi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gtjjzkpose.html

[Q68] 保存点
来源：http://dali.chenjidiqi.icu/Article/details/gtqdbwbejj.html

SAVEPOINT sp1;
来源：http://dali.316326.xyz/Article/details/gtrchibdsy.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtcupvgglo.html

[Q69] 查看执行计划
来源：http://dali.yuxming.cn/Article/details/gtfnvcahqm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gtrxljjhar.html

[Q70] 更新统计信息
来源：http://dali.meibo888.top/Article/details/gtgrbmtvod.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gtkdbgigug.html

[Q71] 查看建表语句
来源：http://dali.yuanzhike.top/Article/details/gtrowzqfos.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gtxjtvoufp.html

[Q72] 查看索引
来源：http://dali.yuxming.cn/Article/details/gttjonrqda.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gthocpjkhz.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gtassropmu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daria6918.cn/Article/details/gtdzobesji.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gtrhowgbll.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gzhubu.top/Article/details/gtbnabdckj.html

[Q75] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtnwnpbimv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtralbrisj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hongshengwenyu.top/Article/details/gtpnglowdo.html

[Q76] 按天统计
来源：http://dali.sysykeji.top/Article/details/gtlrmrcgxk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.feifeiyinyue.top/Article/details/gtnpkorjgh.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gtkejkzihh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gtmibduojr.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtnazcqurf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.mhx1999.top/Article/details/gthiehydwe.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtyrmnahpx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.andypj.xyz/Article/details/gtjtmlgfwk.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gtnnmiotid.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtmbsfnjvl.html

[Q81] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gtcfpsexpd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprudzsmt.html

[Q82] 字符长度与字节长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfnpdrlj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtlidrblie.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtpdesmulu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtkvopkhii.html

[Q84] 去除首尾空格
来源：http://dali.tianlin.xyz/Article/details/gtpvmebjrn.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtexfrwpdd.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gtqrqycxzh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gtdfhofjbk.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gtccaaxgpy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gtowmefxeo.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gtwuiqdpid.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jyoumei.cn/Article/details/gtyygphtae.html

[Q88] 行转列（条件聚合）
来源：http://dali.iojbl.cn/Article/details/gtqxffcamy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gtwgyoaibb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtbbpcdyyf.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gthlfkotbb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guannengcc.top/Article/details/gtmwapynva.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gtmrudybxg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gtphpyfkqp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtynhclika.html

R. Bash 专题
来源：http://dali.bjfxy.top/Article/details/gthnlidhaz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcfywzgm.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtdjvciwlf.html

#!/usr/bin/env bash
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgotiumo.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gtyvxsudjf.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtabmirknm.html

name="Tom"; echo "$name"
来源：http://dali.ybcxt.top/Article/details/gtrtdujsar.html

[R03] 只读变量
来源：http://dali.hysaishi.cn/Article/details/gtwsfnqmtb.html

readonly PI=3.14
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxgmwgfb.html

[R04] 位置参数
来源：http://dali.jinqigufen.top/Article/details/gtdirrjvnn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ppjwa.cn/Article/details/gtejnfsiit.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gtihbxyrpb.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gtgppxmlru.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvitrglru.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtpkisoocu.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gtbiectqpm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtoksglcyf.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gtuvqdxbxq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtaucffgwr.html

[R09] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtieavqzkh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvbvmqkf.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gtvyyiwpcb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtyjfjnlcm.html

[R11] case 多分支
来源：http://dali.guannengcc.top/Article/details/gtbfmlxsgm.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gtziojxopx.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gticsjjpne.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtagaiozrf.html

*)     echo "未知命令" ;;
来源：http://dali.sxryk.cn/Article/details/gtvvfgsqhz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gthqqdoqsv.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gtfklqnopp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmabmpnf.html

[R13] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtdqaoqwdp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtskzsmnsu.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gtxbkuwcqz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gttwpffyrr.html

[R15] while 逐行读文件
来源：http://dali.tanke756.top/Article/details/gtziswtevh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtfqmmvywo.html

[R16] until 等待条件
来源：http://dali.tianlin.xyz/Article/details/gttrmsdglr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtcbushkdk.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gtyhalgycp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gtpkeajbnr.html

[R18] 遍历数组
来源：http://dali.sweek.top/Article/details/gtjbxrgand.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuanzhike.top/Article/details/gtdqzooyrz.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtjmdonezk.html

echo "${#arr[@]}"
来源：http://dali.birdmap.top/Article/details/gtwgtpafmx.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gtapxrmdmc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zdqjudy.top/Article/details/gtwaydmhvq.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtlrqbwkmd.html

echo "${#s}"
来源：http://dali.kuanghao11.cn/Article/details/gtyifgqazk.html

[R22] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtwmtyevlw.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gtkrzqizrz.html

[R23] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gteuwdkeja.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cucudq.cn/Article/details/gtoqluumcn.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtbfgtwppu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gzhubu.top/Article/details/gtcidyfdww.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxhgoovh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gtucjskdvm.html

[R26] 命令替换
来源：http://dali.zhiwuduotai.top/Article/details/gtisowygrn.html

now=$(date +%F); echo "$now"
来源：http://dali.xziqi.cn/Article/details/gtdywaahkf.html

[R27] 算术展开
来源：http://dali.kuanghao11.cn/Article/details/gttpkauapy.html

echo $((1 + 2 * 3))
来源：http://dali.hammf.cn/Article/details/gteytdawfg.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gtjfnjreib.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyczsigx.html

[R29] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gtuodjxkez.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tianlin.xyz/Article/details/gtisbuoapj.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gtdtgtcgua.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gtstxpgmst.html

[R31] 局部变量
来源：http://dali.smart0.xyz/Article/details/gtszarmait.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gtmktyemut.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gtsimaavaw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sweek.top/Article/details/gtumglicve.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gtqyxbxfnh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujjezzpa.html

[R34] 退出时清理
来源：http://dali.ydzc1.top/Article/details/gtaldbnotx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtoauxescw.html

[R35] 后台执行并等待
来源：http://dali.yanxiufei.cn/Article/details/gtflxknmlg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkzrovwb.html

[R36] 并发执行多个任务
来源：http://dali.c1oappe.top/Article/details/gtnhcmsqzp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gtlmyxraig.html

[R37] 把输出赋给变量
来源：http://dali.yanxiufei.cn/Article/details/gtgjrzeugv.html

files=$(ls -1)
来源：http://dali.dashuyun.cn/Article/details/gteagrnstp.html

[R38] 管道串联
来源：http://dali.zhengqikj.top/Article/details/gtctdwpaef.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gttomsgscr.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gtakgtogmr.html

cmd > out.log 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gtakeihjnf.html

[R40] 追加写日志
来源：http://dali.fengsongda.top/Article/details/gttecgpeas.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gtpvqkwopj.html

[R41] 丢弃输出
来源：http://dali.zycfv.cn/Article/details/gtkbhuajlu.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gtilkssfrg.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gtjxdqxbdq.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gtlwkakums.html

[R43] 按名字查找文件
来源：http://dali.fengsongda.top/Article/details/gtmiklgwsy.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gttptesmkx.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwoprnejg.html

find . -mtime -7 -type f
来源：http://dali.hammf.cn/Article/details/gtbsmmpaln.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gtzowjelwf.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258.top/Article/details/gtydsxiodw.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gtdbcormzv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xinyue.icu/Article/details/gtaibytzyo.html

[R47] sed 单行替换
来源：http://dali.yuxming.cn/Article/details/gtdhvopkdy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyktsvwc.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gtwcdhfjfg.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtdbueosqr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gthccyasrf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gtyrgsayhg.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gtltoaccyr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtclctdbje.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gtjwrmmkzv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gzhubu.top/Article/details/gtolilegba.html

[R52] 统计行数
来源：http://dali.yj20258888.top/Article/details/gtjfiwagyv.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtqvwysfwd.html

[R53] 查看文件头与实时尾
来源：http://dali.yuxming.cn/Article/details/gtmwyoyvnp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shzxlz.cn/Article/details/gtcdpveufl.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gttdlhnhrv.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtrzarrmrh.html

[R55] 压缩与解压
来源：http://dali.9152youxi.cn/Article/details/gtonzihaku.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gzhubu.top/Article/details/gtvuxmrehz.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtcxmcgidy.html

scp file user@host:/path/
来源：http://dali.zhixingplan.top/Article/details/gtlxissnvy.html

[R57] 远程执行命令
来源：http://dali.jinqigufen.top/Article/details/gtlrihygzu.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gttxfnnagx.html

[R58] 下载文件
来源：http://dali.yj20258888.top/Article/details/gtbxhqucya.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tian-w.cn/Article/details/gtccwsxadx.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtvezfijkv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjozwopjx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtefcbydxk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gtlotjzjcd.html

[R61] 磁盘占用
来源：http://dali.gzhubu.top/Article/details/gtkvaqzhsn.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gtgejxyvnb.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttkwdqor.html

du -ah . | sort -rh | head -10
来源：http://dali.jiagoushi.top/Article/details/gtzobbppjp.html

[R63] 内存与进程
来源：http://dali.bjfxy.top/Article/details/gtfnzjniqu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gtrxytrzty.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gtbotgnhvl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gtlvbphrqj.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gtzxrhbcug.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gtwlkywbma.html

[R66] 定时任务
来源：http://dali.ivvv.top/Article/details/gterzhbpku.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gtheaqtsqm.html

[R67] 生成随机十六进制串
来源：http://dali.gotoacloud.top/Article/details/gtalqzmwsr.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gthvjicvdq.html

[R68] 计算文件校验值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtempacpov.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtmmennwqd.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gtmwebmojl.html

head -c 16 /dev/urandom | base64
来源：http://dali.yueranfly.top/Article/details/gtawhjcznr.html

[R70] 时间戳与互转
来源：http://dali.kuanghao11.cn/Article/details/gternwgcrv.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gtziglrzxx.html

[R71] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtwoswcixv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gtxfmjchhj.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtipoyvzsh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gtoptypljg.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gtsjmbmjwp.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gtszvzbalh.html

[R74] 批量重命名
来源：http://dali.pycfn.com/Article/details/gtcxjddvms.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gtillwbvni.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtnriqidhh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gtlhhvvedg.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gtzhvtijxi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtroxcymmo.html

[R77] 读取用户输入
来源：http://dali.shuidangran.top/Article/details/gtpvogscjw.html

read -rp "请输入: " ans
来源：http://dali.jqgufenzy.top/Article/details/gttsuxuvko.html

[R78] 交互式菜单
来源：http://dali.meibo888.top/Article/details/gtgaindnpo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gteotydxje.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnpbianm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gtecscevbd.html

[R80] 查看脚本执行耗时
来源：http://dali.iojbl.cn/Article/details/gtnuavirxa.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtxuewikgt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtsaixqvuu.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gtenvjcewy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gturkwcpzv.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtlvpuhrcw.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtmtyggjyw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtdkzlwabq.html

[S02] C：变量与格式化输出
来源：http://dali.mhx1999.top/Article/details/gtxcmwjvoc.html

int a = 10; printf("%d\n", a);
来源：http://dali.vqdsnc.cn/Article/details/gtyvktjjut.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gtlxbpezss.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gtdilzaayk.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gtnbroaevz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cheryme.top/Article/details/gtrqbplvzm.html

[S05] C：字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtfacjfeqm.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gthfoofdjs.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gtagunngtj.html

strcmp(a, b) == 0
来源：http://dali.9152youxi.cn/Article/details/gtaakuemlm.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gtaazhuiaq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gteddjlrzg.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gtneaqftfn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gtojnlmkwn.html

[S09] C：结构体定义与初始化
来源：http://dali.jiagoushi.top/Article/details/gtbrjqfitp.html


<!-- 参考信息 -->