代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.gogol.net.cn/Article/details/gtawhjnwuo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxlvedwr.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gtrorpevfb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cheryme.top/Article/details/gtsckxdjea.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gtcnfnqfjc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigfzy.top/Article/details/gtxgccmcio.html

[Q45] EXISTS 判断存在
来源：http://dali.cqqwz.cn/Article/details/gtohutoshy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtptwrxuyv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgklinuf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gticyzhmgb.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gtlypwxhwz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gtlcuryifz.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gtlgznvmik.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gtizpkwbbn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuanzx.com/Article/details/gtnitqmqro.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gtrrkkroid.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gthmhpetsy.html

[Q50] 批量更新
来源：http://dali.9152youxi.cn/Article/details/gtrjlhtzpx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gtvidkwdrr.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnayyoeid.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ehwqpu.com/Article/details/gtddxbjjnj.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gtomsacspf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtifilvlit.html

[Q53] 按条件删除
来源：http://dali.havefunace.top/Article/details/gtnefsymjd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gzhubu.top/Article/details/gtezviqouw.html

[Q54] 清空表
来源：http://dali.havefunace.top/Article/details/gtckefnsbo.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gtucdbvjyg.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gtyafkgzqg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtkgthgigl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthutpyctb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cheryme.top/Article/details/gtxlpqkrcb.html

[Q57] 行号
来源：http://dali.yuxming.cn/Article/details/gtbsydeqvd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sxryk.cn/Article/details/gtfsdnzpcx.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtejjnajjz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtlbrxhkcw.html

[Q59] 分组内累计
来源：http://dali.dianchejie.cn/Article/details/gtiazsgzcn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cheryme.top/Article/details/gttzukofjv.html

[Q60] 取上一行 / 下一行
来源：http://dali.yonumen.top/Article/details/gtfezlgent.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gtwcneryxy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtpklcrihn.html

[Q61] 移动平均
来源：http://dali.bjfxy.top/Article/details/gtsbdlwlnr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtycgxvynk.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gtqpxoxvct.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtlvfgdizp.html

[Q63] 开启事务
来源：http://dali.andypj.xyz/Article/details/gtdbnmkrdy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.9152youxi.cn/Article/details/gttgqrycng.html

[Q64] 提交事务
来源：http://dali.haohaochexian.top/Article/details/gtdaihewxm.html

COMMIT;
来源：http://dali.daxiang520.top/Article/details/gtvapnurfg.html

[Q65] 回滚事务
来源：http://dali.shuidangran.top/Article/details/gtpxplnyra.html

ROLLBACK;
来源：http://dali.wangshuangyany.cn/Article/details/gtlnuoxjms.html

[Q66] 行锁查询
来源：http://dali.guannengcc.top/Article/details/gtxvejdqws.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gtbwxfuvje.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gtnybxebwu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gtyghdemfh.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gtsserepqm.html

SAVEPOINT sp1;
来源：http://dali.jinqigufen.top/Article/details/gtcwasdtyh.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gtxfnxmvan.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gtmglrgejg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gtaootcfbh.html

[Q70] 更新统计信息
来源：http://dali.zdqjudy.top/Article/details/gtrqokzjwc.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gtildtddwt.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gtkzggoioc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gtvdzvgflh.html

[Q72] 查看索引
来源：http://dali.zhixingplan.top/Article/details/gtipyxadka.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtuyhqruls.html

[Q73] 查看表状态
来源：http://dali.nanxuanxn.top/Article/details/gthzlamonk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cucudq.cn/Article/details/gtccfbvzeb.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgurbiwa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gthtdcjogt.html

[Q75] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtbzrdyuji.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtrnelkrkd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangtech.top/Article/details/gtaeahyspy.html

[Q76] 按天统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsaedybx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gtpemyrcxx.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gtopbyvnzl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jyoumei.cn/Article/details/gtjbhrmoxj.html

[Q78] 当前时间
来源：http://dali.andypj.xyz/Article/details/gtuqghtthl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sweek.top/Article/details/gtmsdpszlc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtwrcjznfj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjtrnmdp.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gtgnaoctru.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtekkuzcff.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtcitmjfpa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtdwhudbfu.html

[Q82] 字符长度与字节长度
来源：http://dali.vqdsnc.cn/Article/details/gtzdynczfy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtasrnvvrn.html

[Q83] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtjqywulsu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gttkajwwts.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gtdjuxkuzv.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtnwfbeaki.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gtssbnhlkj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gtdsistizs.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gtogyhxpgj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.redwolf501.top/Article/details/gtohwdeegp.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gtkaezrurq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gtyealciso.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258888.top/Article/details/gtxvcppquh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gtxafthphl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtamhnoiqy.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtmfjkhfvs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gtopyesbnt.html

[Q90] 生成序号列
来源：http://dali.vqdsnc.cn/Article/details/gthvoamljz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtubuljsap.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtesssqoml.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gtyllpkzbs.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqghjyus.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtrionexjl.html

#!/usr/bin/env bash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxemvhll.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gtnnlnjxjj.html

[R02] 变量赋值与使用
来源：http://dali.hfpthk.cn/Article/details/gtxqhprrhz.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gtpsqebvie.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtntmywp.html

readonly PI=3.14
来源：http://dali.shzxlz.cn/Article/details/gtkutwfvha.html

[R04] 位置参数
来源：http://dali.jinqigufen.top/Article/details/gtcujsamsm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gtifghallu.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gtrkikvuvw.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gttrnilqmc.html

[R06] 判断命令是否存在
来源：http://dali.shuidangran.top/Article/details/gtcqsoutog.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtybdeqwui.html

[R07] if 判断文件
来源：http://dali.wangshuangyany.cn/Article/details/gtmczxnzcw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gtmseqmpiy.html

[R08] 数值比较
来源：http://dali.chenjidiqi.icu/Article/details/gtrbfrreko.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cucudq.cn/Article/details/gtndoklrhm.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gtfhzxcnen.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gtosahhtxm.html

[R10] 正则匹配
来源：http://dali.tian-w.cn/Article/details/gtfplddvuv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtcpctcf.html

[R11] case 多分支
来源：http://dali.ehwqpu.com/Article/details/gtstrzdppm.html

case "$1" in
来源：http://dali.redwolf501.top/Article/details/gtnslpmhzi.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gtwrclpyvr.html

stop)  echo "停止" ;;
来源：http://dali.gotoacloud.top/Article/details/gtkzpybbav.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gtlvnhygtw.html

esac
来源：http://dali.nanxuanxn.top/Article/details/gtgvunnndh.html

[R12] for 遍历文件
来源：http://dali.feifeiyinyue.top/Article/details/gtmyktsktd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.meibo888.top/Article/details/gtpqvmdrwd.html

[R13] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gtduomysxn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gtiejenzfo.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfpqeqru.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtkubvdljx.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtrtmvjpbw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gtqpssrwak.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gtxaiiqtli.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtzcnskqiv.html

[R17] 数组定义与取值
来源：http://dali.pycfn.com/Article/details/gtocccaeav.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigufen.top/Article/details/gtslgulwmm.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gtbpzdtmfd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.havefunace.top/Article/details/gtzzfrenys.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtoifdyiiu.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gtlepqfwsc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gtyqvaobam.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtacuxjdcd.html

[R21] 字符串长度
来源：http://dali.sysykeji.top/Article/details/gtctohblnx.html

echo "${#s}"
来源：http://dali.guowangkeji.top/Article/details/gttpbncqfo.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtkbmhnskr.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gtxmiewlrd.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtqbagzngt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gtmankfjff.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtrelnqtzp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenzaomai.com/Article/details/gtktkwsgbi.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gtvkigfblh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gtkxxgmprx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gtunicsdmz.html

now=$(date +%F); echo "$now"
来源：http://dali.cashguo.top/Article/details/gtbstznsdu.html

[R27] 算术展开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpxkdsod.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gttealcjcp.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gtcafpoumu.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gtbzafxhsi.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevaumjbd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtzliibrzq.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtzklcgnrv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gtdvosvoqm.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gtxswyyguo.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gtcyuenxpi.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gtqeqqzmne.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtxccikdaf.html

[R33] 捕获错误并提示行号
来源：http://dali.yuanzhike.top/Article/details/gtkqvpxhxq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gtpnjvcbjm.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gtamqeyhtz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtjngbwnpc.html

[R35] 后台执行并等待
来源：http://dali.ivvv.top/Article/details/gtgbvxdbpo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pycfn.com/Article/details/gtjzqilxbo.html

[R36] 并发执行多个任务
来源：http://dali.xylfe.cn/Article/details/gtfednomqb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.haohaochexian.top/Article/details/gtfuqtsrnf.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gtbipvdszs.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gtdrornowx.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gtzjlfnijm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hywenlv.cn/Article/details/gtgvjbpwsb.html

[R39] 重定向标准输出与错误
来源：http://dali.jyoumei.cn/Article/details/gtsrelxilz.html

cmd > out.log 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtxoickifo.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gthetexrgc.html

echo "log" >> out.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjevejhtw.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gtetxclqrm.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gtmxjxgyma.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gtddfzgosm.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gteguebyrr.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gtaypxcxct.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gtynbohwro.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gtmbbrtwdw.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gtjdwnictr.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gtqtyceknz.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gtuccmhhzq.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gtohempwhx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gtjduknjqu.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gtgcbynwdi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtvhsqwfea.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gtyjvvhhxk.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gtymgjoveg.html

[R49] awk 带条件
来源：http://dali.dianchejie.cn/Article/details/gtosnpszfu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gteihavlqi.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlddctuo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gtipgbqxdx.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gtwnqbaerh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gtvcjbcuss.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gtdmnfdznc.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gtdbdgnwjw.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gtejpduhof.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gtglwbbodh.html

[R54] 比较两个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtqlzpmpxe.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gtutvnxznb.html

[R55] 压缩与解压
来源：http://dali.ivvv.top/Article/details/gtihbduvdw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ydzc1.top/Article/details/gtcutuoxxo.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gtshcyzuoj.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gttnlbqxsk.html

[R57] 远程执行命令
来源：http://dali.jiagoushi.top/Article/details/gtwuzlanwk.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gtbjflsray.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gtirhxbilp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoikrtka.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gthloxxosk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gtchgggeod.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtbwetuesb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gtqkcplgjy.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gtathyyydf.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gtqfnjqutf.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gtqiquanpa.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gtqvaooyvk.html

[R63] 内存与进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvixouplz.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gtmuvuhezf.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gtrqqfzcih.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtyjqmslcv.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gtdtijrdmg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gtpfwpgjzv.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gtehcvbgif.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gthiqkpkdt.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gtdalmkrnn.html

openssl rand -hex 16
来源：http://dali.vqdsnc.cn/Article/details/gtwypszpjz.html

[R68] 计算文件校验值
来源：http://dali.zhixingplan.top/Article/details/gtifjprieq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtwnwgddtl.html

[R69] 生成随机密码
来源：http://dali.ppjwa.cn/Article/details/gtgejsoydo.html

head -c 16 /dev/urandom | base64
来源：http://dali.nwbrower.top/Article/details/gtolkjpkou.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gtfnziafur.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gtgscfpjys.html

[R71] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtvjixkhfq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gtibwlbdqr.html

[R72] 等待端口就绪
来源：http://dali.shzxlz.cn/Article/details/gtblletmqw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtznirpyag.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gtnjcazmpm.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gthadjtzln.html

[R74] 批量重命名
来源：http://dali.yueranfly.top/Article/details/gtojzjtmvb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gtptdjrzql.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gtzkvixnli.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gtlecfizwh.html

[R76] 使用临时文件
来源：http://dali.cashguo.top/Article/details/gtazdtdlcj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtnxaisnmx.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gtuqvzczle.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gtpvimcobn.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gtghsvjxrr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxyjyhjq.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gtwxqtljsm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gtblpyuhji.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gtwfbhjbxb.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gtvmwhkxkt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjcqogbmq.html

S. C / C++ 专题
来源：http://dali.svipenyu.cn/Article/details/gtubcqzjfu.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtibnpytob.html

[S01] C：Hello World
来源：http://dali.havefunace.top/Article/details/gtpuadjlnk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gthmlglyqu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gtxqnjgvqg.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gtghcjmsfj.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gtxtxwsqau.html

[S03] C：读入整数
来源：http://dali.jlsjyb.cn/Article/details/gtunvhooiw.html

int x; scanf("%d", &x);
来源：http://dali.chenlongwang.top/Article/details/gtdrgjslys.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gtfebqmifv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtrsvxdlot.html

[S05] C：字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtfhirazkq.html

strlen(s)
来源：http://dali.guowangkeji.top/Article/details/gtcoxgtlog.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtidlgiltl.html

strcmp(a, b) == 0
来源：http://dali.yonumen.top/Article/details/gtxltyozrz.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gtszapghbs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.vqdsnc.cn/Article/details/gtdwrlhtan.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gtgdgerrco.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gtbayyciry.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtfbhazdns.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gtkpuruxjn.html

[S10] C：指针与解引用
来源：http://dali.hnqzz.top/Article/details/gtacdrafui.html

int *p = &a;  *p = 5;
来源：http://dali.fengsongda.top/Article/details/gtfaezaonj.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsabhatef.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmqzzgsc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gtnfxgxboi.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtufadpyxr.html

[S12] C：写文件
来源：http://dali.hnxiangtu.top/Article/details/gthmhtxnis.html


<!-- 参考信息 -->