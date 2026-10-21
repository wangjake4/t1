代发 wailian999

[Q44] IN 子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtquikeggb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gtevtdehcc.html

[Q45] EXISTS 判断存在
来源：http://dali.yanxiufei.cn/Article/details/gtpxmfmrea.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtsnxqzvhm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gtakrzsqla.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtpxmxnbvf.html

[Q47] 与平均值比较
来源：http://dali.hnqzz.top/Article/details/gtnvohzzjz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangdashe.top/Article/details/gtnxxaptam.html

[Q48] CTE 公用表表达式
来源：http://dali.andypj.xyz/Article/details/gtwvhkomyo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gzhubu.top/Article/details/gtnlgazxqd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.meibo888.top/Article/details/gtaxxhlswr.html

[Q49] 更新单行
来源：http://dali.daxiang520.top/Article/details/gtfujpdiec.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gtqfgkvjtd.html

[Q50] 批量更新
来源：http://dali.shzxlz.cn/Article/details/gtejuhfhhr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daria6918.cn/Article/details/gttsfxvimy.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gtqrxdjtky.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gtrvnultkn.html

[Q52] 删除指定行
来源：http://dali.havefunace.top/Article/details/gtorsrtswa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtdgoradkk.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gtwprxxnyk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtgxecixoe.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gtrspzunch.html

TRUNCATE TABLE logs;
来源：http://dali.jyoumei.cn/Article/details/gtmcwfdkmj.html

[Q55] 排名（并列占位）
来源：http://dali.jianghu66.top/Article/details/gtybouehdc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtuyopmpim.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtkymtethu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtiigjdfzf.html

[Q57] 行号
来源：http://dali.aibaodan.cn/Article/details/gtygkdopwz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gtkioshusj.html

[Q58] 累计求和
来源：http://dali.tanke756.top/Article/details/gtzvaocasr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gtwdurwbtu.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gtseqjqobn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtclyibgat.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gtvimpebjj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gthfaqwozd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtkpejiumt.html

[Q61] 移动平均
来源：http://dali.hammf.cn/Article/details/gtqtsahbgs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtrxtwbmll.html

[Q62] 分组占比
来源：http://dali.daria6918.cn/Article/details/gtpxthzgbs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtiktbbisp.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gtsngvgypp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gtkoigwfjj.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytbglwkp.html

COMMIT;
来源：http://dali.yonumen.top/Article/details/gtcmijukkb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gtqahixdqd.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gttgftvtmx.html

[Q66] 行锁查询
来源：http://dali.yuanzhike.top/Article/details/gtertztrip.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daria6918.cn/Article/details/gtijzfwvir.html

[Q67] 设置隔离级别
来源：http://dali.guowangkeji.top/Article/details/gttleovzrd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gtprycmvfh.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfmeehbg.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gtavtjfjkl.html

ROLLBACK TO sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuanzmrlg.html

[Q69] 查看执行计划
来源：http://dali.tian-w.cn/Article/details/gtbvqnjwvx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgpaqmyl.html

[Q70] 更新统计信息
来源：http://dali.zhoulong.xyz/Article/details/gteqpsxijs.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gtuavamljz.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gtrwcpqixq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gtiqonmgxw.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gtxoxhalzx.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gtnhqljrcn.html

[Q73] 查看表状态
来源：http://dali.aibaodan.cn/Article/details/gtxjkllbcx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuanzx.com/Article/details/gtntmnbksz.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gtprauvsja.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tanke756.top/Article/details/gtjoptydud.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtoyxkbumn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtvvrykjqh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.svipenyu.cn/Article/details/gtulumewmm.html

[Q76] 按天统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssltpqdp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ivvv.top/Article/details/gtkalwwdqq.html

[Q77] 时间加减
来源：http://dali.shanyushiyangtech.top/Article/details/gtzismxfee.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gtqzivrdfl.html

[Q78] 当前时间
来源：http://dali.zhongyouzk.top/Article/details/gtuzdwnnnb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gtewfmguqv.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gtlknaathm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.mhx1999.top/Article/details/gtldneucio.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gtegtlojqt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtqcdxmsfc.html

[Q81] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gttyzupjmu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtazrrkkuk.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gtgrzlnrfo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtikbnrjfz.html

[Q83] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtreipqsoj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtaojcjtmd.html

[Q84] 去除首尾空格
来源：http://dali.yanxiufei.cn/Article/details/gttoesmjtv.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtzgtktnkr.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gtrldkgbxx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuanzx.com/Article/details/gtnjohggpq.html

[Q86] 读取 JSON 字段
来源：http://dali.andypj.xyz/Article/details/gtfterndba.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258.top/Article/details/gtsrnaobuw.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gthepcmuez.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yanxiufei.cn/Article/details/gtjesjgicu.html

[Q88] 行转列（条件聚合）
来源：http://dali.iojbl.cn/Article/details/gtltoserkl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shuidangran.top/Article/details/gtczctpuxq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sxryk.cn/Article/details/gthpoprkay.html

[Q89] 判断表是否存在
来源：http://dali.chenzaomai.com/Article/details/gtbufidbkn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.316326.xyz/Article/details/gtnaszyjpn.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gtvuwxpfxi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.smart0.xyz/Article/details/gtaalmlsxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtaxdtmtfj.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gtixrmkcgj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqpzcqxjp.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gtzbbtszld.html

#!/usr/bin/env bash
来源：http://dali.zhengqikj.top/Article/details/gtuujqkvcm.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gtdkwesnof.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gtywifekxs.html

name="Tom"; echo "$name"
来源：http://dali.hywenlv.cn/Article/details/gtzhlmjcwi.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gtiqejliil.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gtokrbhfzi.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtyohcgdvz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gtiqmoshnk.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gthbwqidaq.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gtvuhytjll.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gtnlyrjhcz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtexkanybb.html

[R07] if 判断文件
来源：http://dali.andypj.xyz/Article/details/gtjanmjvxl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gtkfsveful.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtbszetsrb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtfzpslxsw.html

[R09] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtrrodnivw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gtcokxxoaj.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gtcdqhsvsm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtasyqflnf.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gtdlafqvke.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gtrnocndsy.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gtztuboowz.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gtxwgkdsix.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gtghrhmssg.html

esac
来源：http://dali.jqgfzy.top/Article/details/gtsctkhymt.html

[R12] for 遍历文件
来源：http://dali.shangyingyoupin.top/Article/details/gtwqvbkhwe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtwygsuhto.html

[R13] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gtzztoppsf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gtowmapeth.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gtzjmjtjch.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtkvjfsaxo.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtqqykvxui.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hysaishi.cn/Article/details/gtgpnihslj.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtiixhaeke.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtxkqoieak.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gtrqokqogc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xinyue.icu/Article/details/gtvtxhlcgp.html

[R18] 遍历数组
来源：http://dali.aizwys.cn/Article/details/gthwpylngi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ybcxt.top/Article/details/gthfombymi.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtvcrofyfd.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdbkrjfo.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gtznpbmaea.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.kuanghao11.cn/Article/details/gtamrydqpy.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtrfxiaahm.html

echo "${#s}"
来源：http://dali.bjfxy.top/Article/details/gtipiixxen.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtwqriiwmg.html

echo "${s:0:5}"
来源：http://dali.jlsjyb.cn/Article/details/gtahsvowks.html

[R23] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtzsfhweqs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gtmmatwgth.html

[R24] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gttsrdqdpd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gtjoyqtsxk.html

[R25] 去后缀 / 去前缀
来源：http://dali.hfpthk.cn/Article/details/gtsbwjinqr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gtdvbkczdx.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gtzvmnonuq.html

now=$(date +%F); echo "$now"
来源：http://dali.shzxlz.cn/Article/details/gtaolqfjri.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gtrbjqmedd.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryqrgxjs.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gtdatkjyfj.html

echo "scale=2; 10/3" | bc
来源：http://dali.c1oappe.top/Article/details/gtnvlbfdxk.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtskxvuguv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.snrcjt.cn/Article/details/gtmmazvdxq.html

[R30] 函数返回状态码
来源：http://dali.chenlongwang.top/Article/details/gtwzxgarxw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gtbxfryfww.html

[R31] 局部变量
来源：http://dali.guowangkeji.top/Article/details/gthbcdjzjv.html

f() { local x=1; echo "$x"; }
来源：http://dali.yanxiufei.cn/Article/details/gtazauggfl.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gtuvzwsxzr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtmipqlwnh.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gtsqortrsa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aibaodan.cn/Article/details/gtqodcmpqi.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gtnqtypngs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtqkbfhaoi.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gtbmxxsnqw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gtulgxwmxw.html

[R36] 并发执行多个任务
来源：http://dali.hfpthk.cn/Article/details/gtshupawft.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gtzxkexksy.html

[R37] 把输出赋给变量
来源：http://dali.zhoulong.xyz/Article/details/gtwnncfpfk.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gtzqojject.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gtfzdyjifl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtqfuingua.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gtghmunlmn.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtaojflwmb.html

[R40] 追加写日志
来源：http://dali.shuidangran.top/Article/details/gtaugxvxyp.html

echo "log" >> out.log
来源：http://dali.tanke756.top/Article/details/gtpdtujfym.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcyvhnik.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtuxjomowj.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gtzlgniqhb.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gtplbuvcyh.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gtwifmlvoo.html

find . -name "*.log" -type f
来源：http://dali.aizwys.cn/Article/details/gtgzgjuoqr.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gtydthgwqx.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gtoxjmwzzy.html

[R45] 批量删除
来源：http://dali.jiagoushi.top/Article/details/gtjfeyrrba.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gttudghmnq.html

[R46] 递归替换文件内容
来源：http://dali.gzhubu.top/Article/details/gthsmsnjjr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gtfuthzubw.html

[R47] sed 单行替换
来源：http://dali.pycfn.com/Article/details/gtsujlquja.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cqqwz.cn/Article/details/gteafjxsom.html

[R48] awk 取指定列
来源：http://dali.hammf.cn/Article/details/gtcfhinjxx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtctzdrelg.html

[R49] awk 带条件
来源：http://dali.iojbl.cn/Article/details/gtcvvyuvhr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gttmtocfay.html

[R50] awk 求和
来源：http://dali.tianlin.xyz/Article/details/gtnmicgsog.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gttunmzzyb.html

[R51] 排序去重取前几
来源：http://dali.pengpengdd.cyou/Article/details/gtkcssjhfo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhongyouzk.top/Article/details/gthjvezlmv.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gtunudwpss.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gtqtqhraqg.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gthimyrgrv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.snrcjt.cn/Article/details/gthtryqccg.html

[R54] 比较两个文件
来源：http://dali.yuxming.cn/Article/details/gtifsxvapt.html

diff a.txt b.txt
来源：http://dali.yuanzhike.top/Article/details/gttwgpaato.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gttyoclvae.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gtfjxralvf.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gtqnmovnmj.html

scp file user@host:/path/
来源：http://dali.mhx1999.top/Article/details/gtlvpxujtz.html

[R57] 远程执行命令
来源：http://dali.hysaishi.cn/Article/details/gtjlafeota.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gtxtjoxqxh.html

[R58] 下载文件
来源：http://dali.smart0.xyz/Article/details/gtxzzqeydk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtwxcndqlw.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtwkctlreb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pengpengdd.cyou/Article/details/gtpxfnbwfy.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtulifpaml.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkudbitdj.html

[R61] 磁盘占用
来源：http://dali.zhixingplan.top/Article/details/gtbctlaxnn.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gtnjxhljrp.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gtypzzfsqh.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gtrzrhigyd.html

[R63] 内存与进程
来源：http://dali.chenlongwang.top/Article/details/gtxaqxzyqn.html

free -h;  ps aux | grep nginx
来源：http://dali.hywenlv.cn/Article/details/gtgxctkzba.html

[R64] 结束进程
来源：http://dali.jyoumei.cn/Article/details/gtorxkpovu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gtvdknyomt.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gtfrychcaf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aizwys.cn/Article/details/gtzvahgpnw.html

[R66] 定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gtgdvgzpqu.html

crontab -e;  crontab -l
来源：http://dali.xziqi.cn/Article/details/gtyoghohqn.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gtbmoovpfe.html

openssl rand -hex 16
来源：http://dali.tanke756.top/Article/details/gtxyqbowbq.html

[R68] 计算文件校验值
来源：http://dali.hnqzz.top/Article/details/gtdzyletup.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gtecatlbny.html

[R69] 生成随机密码
来源：http://dali.jianghu66.top/Article/details/gtklhkifrb.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenlongwang.top/Article/details/gtrqhxjnyy.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gtfdsqrctd.html

date +%s;  date -d @1700000000
来源：http://dali.shzxlz.cn/Article/details/gtobhrcnmn.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtdwpubvtc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.vqdsnc.cn/Article/details/gtndiwotke.html

[R72] 等待端口就绪
来源：http://dali.bjfxy.top/Article/details/gtktqxwkgk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtiypzhqwy.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtvpeybdjl.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gtmcnlergh.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gtfmccvhww.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tanke756.top/Article/details/gtklmhlxta.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gtpeennihh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.0kj1m.cn/Article/details/gticxklnxa.html

[R76] 使用临时文件
来源：http://dali.gzhubu.top/Article/details/gtbiipnhfp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtrutjdlcy.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gtxvheesup.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtbksiatcb.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gtkzxmguxd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gteycgiwpr.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gtyfvmoigq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.9152youxi.cn/Article/details/gtsostopyl.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdivejdej.html

time ./run.sh
来源：http://dali.yj20258.top/Article/details/gtwrjxqyow.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvvurkxtz.html

S. C / C++ 专题
来源：http://dali.iojbl.cn/Article/details/gtfahrgqpj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttqiqvuux.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtfmxobnsw.html

#include <stdio.h>
来源：http://dali.gogol.net.cn/Article/details/gthcsvpzso.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gtlybsraeu.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzogyypj.html

int a = 10; printf("%d\n", a);
来源：http://dali.9152youxi.cn/Article/details/gtvepisrtx.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyjorzlk.html

int x; scanf("%d", &x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfvtugec.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gtxbiqbwqt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jiagoushi.top/Article/details/gtzkpvwbnm.html

[S05] C：字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtzbeetvdb.html

strlen(s)
来源：http://dali.nanxinkj.top/Article/details/gtjvsgoral.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkaqmseov.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gtvsysgwrj.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gtmqlwuotw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sysykeji.top/Article/details/gtugodjtyb.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxuanxn.top/Article/details/gtqonpfsmh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gtgkklpqgl.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gtxuqkjzud.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gtprfuffdd.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gtlxpluvnw.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gtvmkvvray.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtdpvremej.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfedklmq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gtkbjlrfey.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdurwpxh.html

[S12] C：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtucmpvhux.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtqdnnzbhb.html

[S13] C：宏定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcblqciu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258.top/Article/details/gtcxvizdqv.html

[S14] C：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtgdzpkzid.html


<!-- 参考信息 -->