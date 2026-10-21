代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.jqgufenzy.top/Article/details/gtvncfgvyq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.bjfxy.top/Article/details/gtrddwskqa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtviianqgb.html

[Q49] 更新单行
来源：http://dali.xziqi.cn/Article/details/gtaiakemok.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gthodedzpa.html

[Q50] 批量更新
来源：http://dali.chenzaomai.com/Article/details/gtimgyuwqn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtruvteexb.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gtleqondfe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guannengcc.top/Article/details/gtpcdsysjf.html

[Q52] 删除指定行
来源：http://dali.gaohongyu789.top/Article/details/gtekqzrzay.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtnlxpjjip.html

[Q53] 按条件删除
来源：http://dali.yueranfly.top/Article/details/gttqvqdkqs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ivvv.top/Article/details/gtxdlradvp.html

[Q54] 清空表
来源：http://dali.tanke756.top/Article/details/gtfgxfuljt.html

TRUNCATE TABLE logs;
来源：http://dali.jqgfzy.top/Article/details/gtbmwcaiho.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdavdmgqi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtuiuveqix.html

[Q56] 密集排名（并列不占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtcwbsmlfd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtammgbbor.html

[Q57] 行号
来源：http://dali.nanxinkj.top/Article/details/gtwixmovfd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gtrtnnidwf.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gtcliobdnm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtmaqjxvic.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfqliunu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtauhjdlox.html

[Q60] 取上一行 / 下一行
来源：http://dali.cashguo.top/Article/details/gtwissotel.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gtdfbutbeq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtelafsnnw.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gttjyvlkzb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtoqhgyfus.html

[Q62] 分组占比
来源：http://dali.ybcxt.top/Article/details/gtojicaccd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtbpzgdapk.html

[Q63] 开启事务
来源：http://dali.daxiang520.top/Article/details/gtgzimlynt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gtgfzzjorw.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gtpdmlsruc.html

COMMIT;
来源：http://dali.hywenlv.cn/Article/details/gtqlgiycac.html

[Q65] 回滚事务
来源：http://dali.ehwqpu.com/Article/details/gtwxrjaiga.html

ROLLBACK;
来源：http://dali.hnxiangtu.top/Article/details/gtjyztomxp.html

[Q66] 行锁查询
来源：http://dali.smart0.xyz/Article/details/gthwtfsuxs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gttpnpdkpm.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gthxgtnqjv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cucudq.cn/Article/details/gtllmrgabd.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gtmjjexmgh.html

SAVEPOINT sp1;
来源：http://dali.guowangkeji.top/Article/details/gtoiiwzisb.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gtdiibbjfa.html

[Q69] 查看执行计划
来源：http://dali.guowangkeji.top/Article/details/gthzwisbyx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ppjwa.cn/Article/details/gtvkypepzx.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gtpsvfupqn.html

ANALYZE TABLE users;
来源：http://dali.ehwqpu.com/Article/details/gtnqyjfspx.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gtselswzhg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gthxcxdnvd.html

[Q72] 查看索引
来源：http://dali.tanke756.top/Article/details/gtcnubsauk.html

SHOW INDEX FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtobmnpvrr.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gtqrqrduvu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gtbsmwihlv.html

[Q74] 强制使用索引
来源：http://dali.hongshengwenyu.top/Article/details/gtotosuxqu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gtyjrwcybt.html

[Q75] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtylagghln.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gttmufdihx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtqixlvuss.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gtgvbszcwt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gtyubqijfi.html

[Q77] 时间加减
来源：http://dali.nwbrower.top/Article/details/gthkcgrwaf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cdnleiting.top/Article/details/gtnnzvenst.html

[Q78] 当前时间
来源：http://dali.daxiang520.top/Article/details/gtuhmkbrrh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gogol.net.cn/Article/details/gtomvrwyzq.html

[Q79] 字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gtoctgqyjc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xziqi.cn/Article/details/gtmokfesof.html

[Q80] 字符串截取
来源：http://dali.jinghuilouyu.cn/Article/details/gtulbivikz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aizwys.cn/Article/details/gttxuvfzic.html

[Q81] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gtbnnjjwpi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuanzx.com/Article/details/gtcwkjzumn.html

[Q82] 字符长度与字节长度
来源：http://dali.feifeiyinyue.top/Article/details/gtpzcnjija.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtkokctwuj.html

[Q83] 大小写转换
来源：http://dali.sweek.top/Article/details/gtqixjoqzr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtuimylddd.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gtoieukera.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtzshvbotb.html

[Q85] 数值取整
来源：http://dali.aizwys.cn/Article/details/gtubdpilvy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gtedmotish.html

[Q86] 读取 JSON 字段
来源：http://dali.yueranfly.top/Article/details/gthbpkhyot.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gtiftzzykm.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gteqbovxqa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gtfjvnjywu.html

[Q88] 行转列（条件聚合）
来源：http://dali.ivvv.top/Article/details/gttvmvlwft.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gtvavkjjgc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtawwprfse.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtfbdsegjw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxkorogo.html

[Q90] 生成序号列
来源：http://dali.sufxvd.cn/Article/details/gtazgbgkeh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fengsongda.top/Article/details/gttjrccfho.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvrydfzog.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gttcjkdqgm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtomfxosep.html

[R01] shebang 与严格模式
来源：http://dali.ehwqpu.com/Article/details/gtbqqcrqwm.html

#!/usr/bin/env bash
来源：http://dali.daxiang520.top/Article/details/gtbqbcuyzd.html

set -euo pipefail
来源：http://dali.xinyue.icu/Article/details/gtllchgkcg.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtykxecczr.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gtuvmemlxx.html

[R03] 只读变量
来源：http://dali.yanxiufei.cn/Article/details/gtrtcmcafm.html

readonly PI=3.14
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifdzjack.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnzdgdfn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yonumen.top/Article/details/gtvtstgjgt.html

[R05] 参数默认值
来源：http://dali.yj20258888.top/Article/details/gtbntmxvwc.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gtcqfoihcn.html

[R06] 判断命令是否存在
来源：http://dali.jqgfzy.top/Article/details/gtakzenqra.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtsmvvhumm.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtkwjwltdm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.smart0.xyz/Article/details/gtfcbidyee.html

[R08] 数值比较
来源：http://dali.gzhubu.top/Article/details/gttmpoxfio.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gtpcrrznpd.html

[R09] 字符串比较
来源：http://dali.316326.xyz/Article/details/gtcuvpqtsz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gtltgkvhpf.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gtphdhuikv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtfivafl.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gtviuqbbcb.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gtjpitvatv.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gtqnvbeohv.html

stop)  echo "停止" ;;
来源：http://dali.pycfn.com/Article/details/gtwmnnxucf.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtebtyzzhe.html

esac
来源：http://dali.gogol.net.cn/Article/details/gttjkbhtbw.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gtwccmlfoy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gttqnawzdk.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtqymjjgcj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtoxhyzwqv.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gtlyorxatw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtrxhyppyq.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtyvwexfms.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xziqi.cn/Article/details/gtojkzcgsl.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gtfhasnxsa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gthvgtirzf.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gtniwklbeh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jianghu66.top/Article/details/gtawdmhcni.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gtbegnxlpp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gtmeevrqiw.html

[R19] 数组长度
来源：http://dali.tanke756.top/Article/details/gtsthsyseq.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhxjhjie.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gthfewkdgv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjhefkrn.html

[R21] 字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtjavxjxak.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gtqesjfrch.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gttjyuwepm.html

echo "${s:0:5}"
来源：http://dali.ivvv.top/Article/details/gtqoukrpik.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzbhsaxk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gtwnohxlpl.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gtepgeryec.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gtachlnhzb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gtxbmvgonh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pycfn.com/Article/details/gtgbtlixsa.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtsfxoiyxv.html

now=$(date +%F); echo "$now"
来源：http://dali.xinyue.icu/Article/details/gtefrisncb.html

[R27] 算术展开
来源：http://dali.dashuyun.cn/Article/details/gttgabjbtq.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gtdsoukumb.html

[R28] 浮点运算
来源：http://dali.pycfn.com/Article/details/gtousiiswn.html

echo "scale=2; 10/3" | bc
来源：http://dali.feifeiyinyue.top/Article/details/gtyeooqiyk.html

[R29] 定义函数
来源：http://dali.hnqzz.top/Article/details/gtldwswwif.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gtnzuuobdu.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gttxqotlzn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gtdgqrmcrg.html

[R31] 局部变量
来源：http://dali.gzhubu.top/Article/details/gtypxldqwo.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrqgdosz.html

[R32] 参数个数校验
来源：http://dali.fengsongda.top/Article/details/gtqlkbksha.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtkzhwlutk.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gthhqqzjif.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gtwjnewddt.html

[R34] 退出时清理
来源：http://dali.zhengqikj.top/Article/details/gtamvttlzk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtoulyoyhx.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gtxzliriuo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhixingplan.top/Article/details/gtrmvbolxr.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtqucevszf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pengpengdd.cyou/Article/details/gtltnxhrhl.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gtzemonxtw.html

files=$(ls -1)
来源：http://dali.shzxlz.cn/Article/details/gtidtrgfiq.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gtyqcrkpfe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gtscnhmjmx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gtanobbmyr.html

cmd > out.log 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtcxcqgsie.html

[R40] 追加写日志
来源：http://dali.xylfe.cn/Article/details/gtqqvpqudf.html

echo "log" >> out.log
来源：http://dali.nanxuanxn.top/Article/details/gtwauiuphu.html

[R41] 丢弃输出
来源：http://dali.meibo888.top/Article/details/gtasqsfklz.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gtvpypmqpi.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gtblyggqmv.html

wc -l < a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdgxxsmb.html

[R43] 按名字查找文件
来源：http://dali.xylfe.cn/Article/details/gtpcoayigq.html

find . -name "*.log" -type f
来源：http://dali.xziqi.cn/Article/details/gtxivajmvq.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gtywphridd.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gtrebukvkt.html

[R45] 批量删除
来源：http://dali.daria6918.cn/Article/details/gtinqzfnwe.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gtevwvsbjg.html

[R46] 递归替换文件内容
来源：http://dali.wangshuangyany.cn/Article/details/gtkdbjsgej.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gtjxbbgklo.html

[R47] sed 单行替换
来源：http://dali.zhongyouzk.top/Article/details/gtpenthilf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gtnoaewymo.html

[R48] awk 取指定列
来源：http://dali.yanxiufei.cn/Article/details/gtmkzkarug.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtygfkbvby.html

[R49] awk 带条件
来源：http://dali.aibaodan.cn/Article/details/gtbkhnlaej.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigufen.top/Article/details/gthvtsfzrm.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gtuhoqdqfo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtpytmbyrd.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gtrhpejhoe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gtrtvzxdjc.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gtgnxcuulg.html

wc -l a.txt
来源：http://dali.gotoacloud.top/Article/details/gtxvelnxlf.html

[R53] 查看文件头与实时尾
来源：http://dali.snrcjt.cn/Article/details/gtwblftlbh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gtaxhisspx.html

[R54] 比较两个文件
来源：http://dali.ppjwa.cn/Article/details/gtnzabbzcw.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gtqncubwdv.html

[R55] 压缩与解压
来源：http://dali.fengsongda.top/Article/details/gtntncvmjv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shuidangran.top/Article/details/gtmoradcrn.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gtcxradmxa.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gtrdgaesat.html

[R57] 远程执行命令
来源：http://dali.jyoumei.cn/Article/details/gtscjelaau.html

ssh user@host 'uptime'
来源：http://dali.hywenlv.cn/Article/details/gtqoijdkzs.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gtozrirxsz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gtllqtdgzs.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkxlogfp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jianghu66.top/Article/details/gtrxwgrlew.html

[R60] 只看 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gtxlajifjs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gtwlsugiub.html

[R61] 磁盘占用
来源：http://dali.ivvv.top/Article/details/gtpifgwhiz.html

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gtfwajggzh.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gtjqnueccn.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gthkteravh.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gtxvxpmuix.html

free -h;  ps aux | grep nginx
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdwzhnjd.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gtokwpsbnr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gtfnllasrt.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gtxrekkyrq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gtzsuvllmc.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gtzqpqkxqg.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gtfrxlrlwm.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gtwcpsznqs.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gtonnxthik.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gtxryaaauc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gthbvwzeuc.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gtbnldogdv.html

head -c 16 /dev/urandom | base64
来源：http://dali.nwbrower.top/Article/details/gtiytraxkm.html

[R70] 时间戳与互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtammncapp.html

date +%s;  date -d @1700000000
来源：http://dali.yueranfly.top/Article/details/gtrockqzba.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtikpisebc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.9152youxi.cn/Article/details/gthoicnrok.html

[R72] 等待端口就绪
来源：http://dali.gzhubu.top/Article/details/gtpkdnwiwl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtsqwklkhp.html

[R73] 分割大日志
来源：http://dali.cashguo.top/Article/details/gtgblflohy.html

split -l 1000 big.log part_
来源：http://dali.zhongyouzk.top/Article/details/gtisixwbbt.html

[R74] 批量重命名
来源：http://dali.guannengcc.top/Article/details/gtgcpeeaxj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gtekvbckox.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gtpbmisbni.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gtyuudknki.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gtvwaqbedk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtktqrsybd.html

[R77] 读取用户输入
来源：http://dali.xinyue.icu/Article/details/gtocrmqweu.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gtieelkszk.html

[R78] 交互式菜单
来源：http://dali.sysykeji.top/Article/details/gtwlrupohj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.9152youxi.cn/Article/details/gtqgjqsgbm.html

[R79] 解析命令行选项
来源：http://dali.cqqwz.cn/Article/details/gtyysmakop.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gtkcsexblj.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gtawcrkqzz.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gtuinlsjxw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtaxbdlrfm.html

S. C / C++ 专题
来源：http://dali.jyoumei.cn/Article/details/gtfjaxdqew.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtmtnqvy.html

[S01] C：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtizivupwj.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gtbglipfta.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gtllminulm.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtbzouqlve.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gthnrjygki.html

[S03] C：读入整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuehdpgfx.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gtqlqjgmsr.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gticssteeq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.bjfxy.top/Article/details/gtvzxoweeb.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtocwhxjfb.html

strlen(s)
来源：http://dali.xinyue.icu/Article/details/gtgtchkckl.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gtzdntjzht.html

strcmp(a, b) == 0
来源：http://dali.xuetiantiany.cn/Article/details/gtbphthqkq.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gtvhlepkpb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cucudq.cn/Article/details/gthhdtyoqg.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gtsiedfkjq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.mhx1999.top/Article/details/gthrmbmvxw.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gtyqsuwlwn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gtyejxkeea.html

[S10] C：指针与解引用
来源：http://dali.wangdashe.top/Article/details/gtmwtkbali.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gtbhoiuite.html

[S11] C：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtffbbhokp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gtoaeaplih.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gaohongyu789.top/Article/details/gttpwndogp.html

fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtazxpuryd.html

[S12] C：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkoyongi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fzhhl.top/Article/details/gtcjnjlgrw.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gtltaqwhim.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yangfankeji.com/Article/details/gtvkxldesi.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gtksurvvwq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj202588.top/Article/details/gttkuflafa.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtteojrjoj.html

(double) a / b
来源：http://dali.tanke756.top/Article/details/gtspsfvcgj.html

[S16] C：位操作置位
来源：http://dali.yonumen.top/Article/details/gteiiyghho.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gtjfnupred.html

[S17] C：安全拼接字符串
来源：http://dali.yongpay.top/Article/details/gtegrfaaay.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hysaishi.cn/Article/details/gtdfrxnals.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gtoavcgxhb.html


<!-- 参考信息 -->