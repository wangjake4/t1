代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gtaxzgmtzf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigufen.top/Article/details/gtkpzgfzet.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gthgshyigx.html

[Q49] 更新单行
来源：http://dali.hnxiangtu.top/Article/details/gtbodgtlip.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtcwywizbn.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gtiepjpufa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gthkfnxcmz.html

[Q51] 用子查询更新
来源：http://dali.xuanzx.com/Article/details/gtjabjmvtu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtkcembrlr.html

[Q52] 删除指定行
来源：http://dali.cheryme.top/Article/details/gtjvrootgx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gtxdgaczlz.html

[Q53] 按条件删除
来源：http://dali.aizwys.cn/Article/details/gtukmxsbko.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gtnkueowim.html

[Q54] 清空表
来源：http://dali.hfpthk.cn/Article/details/gtifbkzafi.html

TRUNCATE TABLE logs;
来源：http://dali.gaohongyu789.top/Article/details/gtcitmbfzl.html

[Q55] 排名（并列占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysfivvrk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtkmbtfpqc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gtkmfushkl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cheryme.top/Article/details/gtxierjjvj.html

[Q57] 行号
来源：http://dali.ydzc1.top/Article/details/gtqfwsblqr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtsqdybrxt.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gtvyhqibeg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtzrshrlas.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gtoqxxyxvt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtmqxjkemh.html

[Q60] 取上一行 / 下一行
来源：http://dali.shangyingyoupin.top/Article/details/gtezhmhsqi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gtjdufgnri.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtouxrxgwd.html

[Q61] 移动平均
来源：http://dali.cucudq.cn/Article/details/gtnuhjjllf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtscqaeitq.html

[Q62] 分组占比
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolqwutnu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzqqcogz.html

[Q63] 开启事务
来源：http://dali.quarkkingdee.top/Article/details/gtbzuccuol.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gtnzgxbfro.html

[Q64] 提交事务
来源：http://dali.shuidangran.top/Article/details/gtwqiluthc.html

COMMIT;
来源：http://dali.quarkkingdee.top/Article/details/gtpvxfkdsn.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gtwonyryim.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gtidrjsudw.html

[Q66] 行锁查询
来源：http://dali.quarkkingdee.top/Article/details/gtpxtdkhsy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gtcizybuyh.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gtsxseknrq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tian-w.cn/Article/details/gtgvrxeffs.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gtlwqdpybl.html

SAVEPOINT sp1;
来源：http://dali.redwolf501.top/Article/details/gtyxfjkecd.html

ROLLBACK TO sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtpglaykhf.html

[Q69] 查看执行计划
来源：http://dali.yj202588.top/Article/details/gtmiujrfbh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dianchejie.cn/Article/details/gtycjbgskn.html

[Q70] 更新统计信息
来源：http://dali.hywenlv.cn/Article/details/gtoxpedsdy.html

ANALYZE TABLE users;
来源：http://dali.wangshuangyany.cn/Article/details/gttwpjhcgo.html

[Q71] 查看建表语句
来源：http://dali.ydzc1.top/Article/details/gtodqoqlxy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gtcmhbgjcp.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gthqjynjjb.html

SHOW INDEX FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtlfilkndt.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gtyysnvots.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtongxxlzp.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gtsrkbouey.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gtbglwusoe.html

[Q75] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtalvbacma.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tanke756.top/Article/details/gtkomslhcq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gtddbwivtv.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gtyskjrqmz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gtgzzayzrs.html

[Q77] 时间加减
来源：http://dali.vqdsnc.cn/Article/details/gtmhdmxzam.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.quarkkingdee.top/Article/details/gtklhfxoey.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gtzudhpzjc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gtbqtljyhg.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyrthbux.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnqzz.top/Article/details/gtueyabkjc.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gtrhjgkcir.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ivvv.top/Article/details/gtzluzcgdt.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqwxwrhe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnqzz.top/Article/details/gtnkvplayt.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgfzy.top/Article/details/gtkfdusdxw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtqdqjjgan.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtgghddhkk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtxpyamgyu.html

[Q84] 去除首尾空格
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrshrshdm.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtialfiudd.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gtjlxcngtc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gtviaofvps.html

[Q86] 读取 JSON 字段
来源：http://dali.sweek.top/Article/details/gtsvamslfm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.havefunace.top/Article/details/gtixoupcgg.html

[Q87] JSON 字段做条件
来源：http://dali.hywenlv.cn/Article/details/gttskblnuh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphhijsqy.html

[Q88] 行转列（条件聚合）
来源：http://dali.pengpengdd.cyou/Article/details/gtuxqzejbb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jlsjyb.cn/Article/details/gtcndkooot.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.redwolf501.top/Article/details/gtwyswasyf.html

[Q89] 判断表是否存在
来源：http://dali.zdqjudy.top/Article/details/gtrsnzhqgm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shzxlz.cn/Article/details/gtbmtdgrmn.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gtofpfuoyn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gtwscobkdt.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbokcpdd.html

R. Bash 专题
来源：http://dali.yvedp.cn/Article/details/gtvsvywagv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxbbjykuh.html

[R01] shebang 与严格模式
来源：http://dali.hfpthk.cn/Article/details/gtcueqecbc.html

#!/usr/bin/env bash
来源：http://dali.fengsongda.top/Article/details/gtoyjecayl.html

set -euo pipefail
来源：http://dali.meibo888.top/Article/details/gtkaupuhbr.html

[R02] 变量赋值与使用
来源：http://dali.nanxinkj.top/Article/details/gtkhscyueb.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gtcukbyibr.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gtxdrbxpgl.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gtcfiupwml.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gtvvldewtr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gtkaqqetod.html

[R05] 参数默认值
来源：http://dali.nanxinkj.top/Article/details/gtnhnjyjzt.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gtgqcalpkt.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gtffyuzayd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtsuuubdej.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gtynlhntrx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gtaodzbxwu.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gtmopskerk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guowangkeji.top/Article/details/gtyyfmpeox.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtkfmhjzyo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yvedp.cn/Article/details/gtmqmejypk.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gthgcyilpl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gtwdpzfrev.html

[R11] case 多分支
来源：http://dali.tian-w.cn/Article/details/gtohjqjfpq.html

case "$1" in
来源：http://dali.chenjidiqi.icu/Article/details/gtscvvfhin.html

start) echo "启动" ;;
来源：http://dali.chenlongwang.top/Article/details/gtxsfiscmj.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtecpgtrpt.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gtvvvgtyye.html

esac
来源：http://dali.gotoacloud.top/Article/details/gtzsncmwti.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtdomzhonu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gtzzfhlnmj.html

[R13] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtqncjrloa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtuhnqngoc.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gtnnmtzdvc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtgllgedok.html

[R15] while 逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtigfceyqh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhixingplan.top/Article/details/gtheyokmfc.html

[R16] until 等待条件
来源：http://dali.xuanzx.com/Article/details/gtftgrfuxp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdmnlxjq.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gtyzkujast.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gtepudqjdo.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gthvmmxikq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gthevsnuur.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtbtkybtmv.html

echo "${#arr[@]}"
来源：http://dali.xylfe.cn/Article/details/gtfogcwrbk.html

[R20] 关联数组（字典）
来源：http://dali.zhiwuduotai.top/Article/details/gthflndtkz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.vqdsnc.cn/Article/details/gtidvpcrtw.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtaqklndkp.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gtnzuwkkci.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtgplwxrgr.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gtqdyrevlb.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtxlksovmy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tianlin.xyz/Article/details/gtyjhzmsbn.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtgjqemize.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.havefunace.top/Article/details/gtmpdginzd.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gtcwetbdor.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gtbiyqsqit.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gtgonuszes.html

now=$(date +%F); echo "$now"
来源：http://dali.shuidangran.top/Article/details/gtssnudgmx.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gtdziyjcyx.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gtefnyqkqn.html

[R28] 浮点运算
来源：http://dali.jianghu66.top/Article/details/gtfibguhqg.html

echo "scale=2; 10/3" | bc
来源：http://dali.hammf.cn/Article/details/gtwyuubcba.html

[R29] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gttwagbbac.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.quarkkingdee.top/Article/details/gtumlgjrox.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gtjhbmvqje.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gtekaxhrrb.html

[R31] 局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmdlffvq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gtishvwuem.html

[R32] 参数个数校验
来源：http://dali.jqgufenzy.top/Article/details/gtjoubujsg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqpusermn.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtxykmsjum.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.quarkkingdee.top/Article/details/gtzrncyjbw.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gtpctrluef.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gttbznckee.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gtlmdvloks.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gtuqlqqljb.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gtjxkirgaa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gtkdomikvc.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gtlshtlhku.html

files=$(ls -1)
来源：http://dali.smart0.xyz/Article/details/gtaihnuclh.html

[R38] 管道串联
来源：http://dali.cucudq.cn/Article/details/gtoqolsgfu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.smart0.xyz/Article/details/gtwegfxasu.html

[R39] 重定向标准输出与错误
来源：http://dali.gaohongyu789.top/Article/details/gteiigiyaq.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gtgtaqnoeb.html

[R40] 追加写日志
来源：http://dali.yuanzhike.top/Article/details/gtwpqngkkg.html

echo "log" >> out.log
来源：http://dali.jqgfzy.top/Article/details/gtnjocaefo.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gtblqlbplc.html

cmd >/dev/null 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtskiinrad.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gtbrkygmvk.html

wc -l < a.txt
来源：http://dali.xinyue.icu/Article/details/gtfycctrgf.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gtrwnytsqx.html

find . -name "*.log" -type f
来源：http://dali.gotoacloud.top/Article/details/gtstuyspbo.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gtkmkptxgy.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gtvkpbdvej.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gtdkfdalov.html

find . -name "*.tmp" -delete
来源：http://dali.c1oappe.top/Article/details/gtpbnriwwk.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gtjggxxwxy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hywenlv.cn/Article/details/gterjhzwoz.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gtmbtxekwt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gtndbbjzns.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gtuzpdcwpx.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdobdzhn.html

[R49] awk 带条件
来源：http://dali.yj202588.top/Article/details/gtmhrguzzp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsbivqbk.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gtkxqcealu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.iojbl.cn/Article/details/gtarsunumh.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gtfcbxxotr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.feifeiyinyue.top/Article/details/gtujmsdziy.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gtahmhmxjo.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtnmfoughb.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgufenzy.top/Article/details/gtnsdpxlrv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.kuanghao11.cn/Article/details/gtrhtazfyu.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gtmdtpgtbg.html

diff a.txt b.txt
来源：http://dali.tanke756.top/Article/details/gtnhgzexov.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gtensikdie.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gtubaqbzqm.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gtocrywyqp.html

scp file user@host:/path/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjszwmlmp.html

[R57] 远程执行命令
来源：http://dali.xylfe.cn/Article/details/gtnkiudkwy.html

ssh user@host 'uptime'
来源：http://dali.pengpengdd.cyou/Article/details/gtljyaebmi.html

[R58] 下载文件
来源：http://dali.hysaishi.cn/Article/details/gtxmzbdsvt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gtwmdhconb.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gttudllesj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guowangkeji.top/Article/details/gtzvzcadfz.html

[R60] 只看 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gtddlsmlhb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gtekotljmr.html

[R61] 磁盘占用
来源：http://dali.hongshengwenyu.top/Article/details/gthdcgvahr.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gtoznuzxbw.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtxjkmqulx.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gtcffdmvoc.html

[R63] 内存与进程
来源：http://dali.svipenyu.cn/Article/details/gtmohohjbu.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gtfhiclrgh.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gtgckyggss.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gtznshzwuu.html

[R65] 查看端口占用
来源：http://dali.snrcjt.cn/Article/details/gtcjdsewge.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jyoumei.cn/Article/details/gtryfykfjn.html

[R66] 定时任务
来源：http://dali.0kj1m.cn/Article/details/gtgaxtrbju.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gtrgbipwea.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gtgghepprn.html

openssl rand -hex 16
来源：http://dali.dianchejie.cn/Article/details/gttozcmbsu.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gtedsjpzrk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hysaishi.cn/Article/details/gtxsgpajdu.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gtetgkhgbb.html

head -c 16 /dev/urandom | base64
来源：http://dali.andypj.xyz/Article/details/gtdueyaapx.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzghqffc.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gtkwuwxjjo.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtosgduosb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gtmeapipzq.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtnmvieena.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtimsgbxtc.html

[R73] 分割大日志
来源：http://dali.birdmap.top/Article/details/gtvyhbsqly.html

split -l 1000 big.log part_
来源：http://dali.cashguo.top/Article/details/gtldwtisir.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gtgncnxsbz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtyqxgibua.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gtcgvjynea.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gtwmrsoonn.html

[R76] 使用临时文件
来源：http://dali.nanxuanxn.top/Article/details/gtzgpeofjc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtumrcqdum.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gtttbasotq.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtzxdsgqgz.html

[R78] 交互式菜单
来源：http://dali.0kj1m.cn/Article/details/gtvcqqjoqw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj202588.top/Article/details/gtdbsuxrsx.html

[R79] 解析命令行选项
来源：http://dali.nwbrower.top/Article/details/gtuvucagwv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxinkj.top/Article/details/gtpqjwkdvf.html

[R80] 查看脚本执行耗时
来源：http://dali.shuidangran.top/Article/details/gtdqceeerm.html

time ./run.sh
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehddnuzn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvqtfutlh.html

S. C / C++ 专题
来源：http://dali.hysaishi.cn/Article/details/gtftacuocp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtckbzktqc.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtolkhtkue.html

#include <stdio.h>
来源：http://dali.vqdsnc.cn/Article/details/gtpnvtxzea.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gtkupguijo.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtmbvhfjbi.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gtjipnujfq.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtroaqkgox.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gtqvuocdmp.html

[S04] C：字符串复制
来源：http://dali.gogol.net.cn/Article/details/gtjydxwgav.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.bjfxy.top/Article/details/gtclbgpnnw.html

[S05] C：字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtpwzmisil.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gtnfoxpeus.html

[S06] C：字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtiyleopvj.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gtwtzletdi.html

[S07] C：数组遍历求和
来源：http://dali.jiagoushi.top/Article/details/gturdnqgpk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gtmabmcrkb.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gtwuhvjcqp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gteokczfug.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gtafurbhus.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gtbkghjikl.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gtdycjvyut.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gtzekhqewq.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtxzgvygoe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gtnilfraqh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gtxjdsolzs.html

fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtlltbyeys.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gtkrhiizxo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aizwys.cn/Article/details/gtsesnkpzm.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gtoyszklwe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gttcwiwoun.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gtzemxekpk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gteqnvylon.html

[S15] C：类型转换
来源：http://dali.ppjwa.cn/Article/details/gtyfipyvqb.html

(double) a / b
来源：http://dali.xuanzx.com/Article/details/gtodchhyyi.html

[S16] C：位操作置位
来源：http://dali.jlsjyb.cn/Article/details/gtskyqbsxk.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gtsmcetsge.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gteselgsxh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgufenzy.top/Article/details/gtfhiqcmuv.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtgyitmcza.html


<!-- 参考信息 -->