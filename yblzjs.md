代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtjgesbvez.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gtcwfevcik.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zycfv.cn/Article/details/gtjtpwgpyo.html

[Q51] 用子查询更新
来源：http://dali.mhx1999.top/Article/details/gttxzsapiv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtkuabnywf.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhfhkjec.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtehfnpnnd.html

[Q53] 按条件删除
来源：http://dali.gotoacloud.top/Article/details/gtuaxvusan.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtkssitnyx.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gtrdfncpua.html

TRUNCATE TABLE logs;
来源：http://dali.xuetiantiany.cn/Article/details/gtwyxddjic.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gtzhvzcdjp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xziqi.cn/Article/details/gtfywzezwj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gtdnudujyy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtavxyjity.html

[Q57] 行号
来源：http://dali.havefunace.top/Article/details/gtgwcxqjyn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.redwolf501.top/Article/details/gtmfoxvtni.html

[Q58] 累计求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkbkcgds.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtscrwudxc.html

[Q59] 分组内累计
来源：http://dali.jianghu66.top/Article/details/gtebrnpwdo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtbiopqyey.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gtobezmsyg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgfzy.top/Article/details/gtwvdtdebw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tanke756.top/Article/details/gtarixckyn.html

[Q61] 移动平均
来源：http://dali.hammf.cn/Article/details/gtotezzcxy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtnmfclnyg.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gtvsbabiwo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtfozyrmzo.html

[Q63] 开启事务
来源：http://dali.yonumen.top/Article/details/gtdhaxmvwu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gtfyaenkmk.html

[Q64] 提交事务
来源：http://dali.zhiwuduotai.top/Article/details/gtdapzzmec.html

COMMIT;
来源：http://dali.hfpthk.cn/Article/details/gtwycwinkm.html

[Q65] 回滚事务
来源：http://dali.jyoumei.cn/Article/details/gtvsnqfsht.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gtmotmzuwj.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gtindpioxi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.meibo888.top/Article/details/gtskbjtyck.html

[Q67] 设置隔离级别
来源：http://dali.hnxiangtu.top/Article/details/gtdwciyslv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guowangkeji.top/Article/details/gtssmszrrw.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gtbitxdyzq.html

SAVEPOINT sp1;
来源：http://dali.jianghu66.top/Article/details/gtprarmgdn.html

ROLLBACK TO sp1;
来源：http://dali.haohaochexian.top/Article/details/gtogkoxmjj.html

[Q69] 查看执行计划
来源：http://dali.jqgufenzy.top/Article/details/gtbganltwy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gtfurnspwn.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gtvtnxlrwk.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijizkiwv.html

[Q71] 查看建表语句
来源：http://dali.ybcxt.top/Article/details/gtedzsxwwb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sweek.top/Article/details/gtycoavgbk.html

[Q72] 查看索引
来源：http://dali.jinqigfzy.top/Article/details/gtbywvmzvc.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtjbroxmok.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gtokgydgwe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gtyzmaamhq.html

[Q74] 强制使用索引
来源：http://dali.fzhhl.top/Article/details/gtgwjjrscx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gtlriokhwa.html

[Q75] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtgmquaytx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gtotkdlgec.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tian-w.cn/Article/details/gtklvasmru.html

[Q76] 按天统计
来源：http://dali.zhixingplan.top/Article/details/gtoeoozwlw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gtmrkclnkx.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gtvdksoasu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cashguo.top/Article/details/gtyvxavlmj.html

[Q78] 当前时间
来源：http://dali.tian-w.cn/Article/details/gtmjdbenlu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenlongwang.top/Article/details/gtutzngzth.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gtdfbhlxjh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daria6918.cn/Article/details/gtzcahmmnh.html

[Q80] 字符串截取
来源：http://dali.jqgufenzy.top/Article/details/gtguncfwsz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtkenpeope.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtioaxkmzo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtrswllasb.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258.top/Article/details/gtwolykjap.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtuxzdluft.html

[Q83] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtyomkyucn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtsqgnrhua.html

[Q84] 去除首尾空格
来源：http://dali.chenjidiqi.icu/Article/details/gtgaggrysl.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtkwkelrsg.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gtpbvqttsx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zdqjudy.top/Article/details/gtpqdnbdmy.html

[Q86] 读取 JSON 字段
来源：http://dali.birdmap.top/Article/details/gtymwfrhgc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gtwplxeqla.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gtrjxgbwua.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.haohaochexian.top/Article/details/gtczcineud.html

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gtkqeedrob.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gtxtnrxtrx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtddxqzmky.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gtzpmvwvtn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtoffvccwm.html

[Q90] 生成序号列
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqwzqbao.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gtjhpyykax.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwfryajsv.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtvtnrxqwz.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtsxfybflz.html

[R01] shebang 与严格模式
来源：http://dali.zhongyouzk.top/Article/details/gtpfmmmcuc.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gtxxgmpzhd.html

set -euo pipefail
来源：http://dali.zycfv.cn/Article/details/gtduxqxitr.html

[R02] 变量赋值与使用
来源：http://dali.ybcxt.top/Article/details/gtdrjpotgj.html

name="Tom"; echo "$name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupdjqtpb.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gtjwwprsyf.html

readonly PI=3.14
来源：http://dali.guannengcc.top/Article/details/gtcxqsityl.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gtctvsryyq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gtfksglfsm.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gthxawatop.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gtfcfkwmov.html

[R06] 判断命令是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtopumyfvl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gttebeemii.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbkefoox.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jiagoushi.top/Article/details/gtoahxqlal.html

[R08] 数值比较
来源：http://dali.pengpengdd.cyou/Article/details/gtgdmtguky.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gtvzeigxko.html

[R09] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtwibihvgc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ehwqpu.com/Article/details/gtevwexypi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gtujymujxt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gtbrrfvxuy.html

[R11] case 多分支
来源：http://dali.shanyushiyangtech.top/Article/details/gtslexrtnv.html

case "$1" in
来源：http://dali.yanxiufei.cn/Article/details/gtcqiuarvt.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtwgqmzywb.html

stop)  echo "停止" ;;
来源：http://dali.nwbrower.top/Article/details/gtcaakbmlz.html

*)     echo "未知命令" ;;
来源：http://dali.dashuyun.cn/Article/details/gtcpdqkdeb.html

esac
来源：http://dali.zdqjudy.top/Article/details/gtscccgxfj.html

[R12] for 遍历文件
来源：http://dali.meibo888.top/Article/details/gthwpjxjru.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aibaodan.cn/Article/details/gtitcgkcby.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtmpgpdvnz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtvdqyxrnd.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gtdzydjbso.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtnlgotpxu.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtysqypnlk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gttfgmakbb.html

[R16] until 等待条件
来源：http://dali.gaohongyu789.top/Article/details/gtdtfcaxuz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtcimxbnrp.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gtcaxwpfvm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gtxhozdzpl.html

[R18] 遍历数组
来源：http://dali.sweek.top/Article/details/gtivcsstri.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gtqhxqupkl.html

[R19] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtgniwbmme.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujhrpmrn.html

[R20] 关联数组（字典）
来源：http://dali.haohaochexian.top/Article/details/gtukvreesu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gtqplnzfwf.html

[R21] 字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtpfxzxfky.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gtpsoogjwf.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtdrbivnyu.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gteclhneji.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtugcmwuwb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gtkvolhuer.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gthdglfwji.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gtroxlzvfg.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gtvbrlhnzl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gtrjrmshwa.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gtytxtqnyz.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gtrcsooilv.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gtjsbppmkr.html

echo $((1 + 2 * 3))
来源：http://dali.tianlin.xyz/Article/details/gtjzbdcqxw.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gtxoppmdau.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gtrmxfrhnf.html

[R29] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtvbcnavtg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuanzhike.top/Article/details/gtfcpdtvjn.html

[R30] 函数返回状态码
来源：http://dali.jiagoushi.top/Article/details/gtjxulkkau.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.quarkkingdee.top/Article/details/gtquscnnaa.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikruylag.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gtipjglibb.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gtpwcxsliw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtjwsmouxb.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gtmcxifnfp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnjfftpb.html

[R34] 退出时清理
来源：http://dali.xuetiantiany.cn/Article/details/gtuiwlpcpd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnasmrhwt.html

[R35] 后台执行并等待
来源：http://dali.yj20258.top/Article/details/gtkiboduwh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gtupjzkrge.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gtdfwmgjuu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gtahzpnbmb.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gtorhzobfw.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjasunvow.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gtziokuqre.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacldwaqi.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gtgxmjrsjg.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtiureflkg.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gtixwuejzt.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gtdazvmydz.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gtsyuttrey.html

cmd >/dev/null 2>&1
来源：http://dali.c1oappe.top/Article/details/gtgkrlswaw.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gttzrncnnj.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gtuhtgcjzt.html

[R43] 按名字查找文件
来源：http://dali.snrcjt.cn/Article/details/gtqxhawesd.html

find . -name "*.log" -type f
来源：http://dali.birdmap.top/Article/details/gtdfqimibi.html

[R44] 按修改时间查找
来源：http://dali.iojbl.cn/Article/details/gtqfuapaic.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gtaaqwdoiz.html

[R45] 批量删除
来源：http://dali.wangshuangyany.cn/Article/details/gtxwrznqwm.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gttrozvzfb.html

[R46] 递归替换文件内容
来源：http://dali.xylfe.cn/Article/details/gtlpniegkt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gtktgpznqf.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gtttagtjgr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtpfscwqga.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gtgfekqerx.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtkagxxjuv.html

[R49] awk 带条件
来源：http://dali.aizwys.cn/Article/details/gtwwmbktdh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigfzy.top/Article/details/gteocrfxmd.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gttwswlkla.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtgivlkafv.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gteywemftk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.meibo888.top/Article/details/gttcvyrbgf.html

[R52] 统计行数
来源：http://dali.haohaochexian.top/Article/details/gtycpcqtdn.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpfmsplk.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtoulfepes.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sysykeji.top/Article/details/gtkgqtiyor.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gtzdvdfwmz.html

diff a.txt b.txt
来源：http://dali.nanxuanxn.top/Article/details/gtsynfarqj.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gtiyjetmho.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258.top/Article/details/gtlwxkfoil.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gtbxjmftut.html

scp file user@host:/path/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhafdnzr.html

[R57] 远程执行命令
来源：http://dali.zycfv.cn/Article/details/gtjmzfmpbg.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gtpsoaxapl.html

[R58] 下载文件
来源：http://dali.yj202588.top/Article/details/gttwmdyrzr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtkskmbmte.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtcirnoqxu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gtegqphivh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtidgvuewm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gtfsupqwsq.html

[R61] 磁盘占用
来源：http://dali.sufxvd.cn/Article/details/gttszdeypa.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gtsegtmhsk.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gthsejzqum.html

du -ah . | sort -rh | head -10
来源：http://dali.hnqzz.top/Article/details/gtouhcvwzf.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gthztdvobf.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gtbvkkoggv.html

[R64] 结束进程
来源：http://dali.zhengqikj.top/Article/details/gtfrsgmxkb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.quarkkingdee.top/Article/details/gthmigtdsd.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gtfjktktix.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hfpthk.cn/Article/details/gtwfyniuem.html

[R66] 定时任务
来源：http://dali.zhixingplan.top/Article/details/gtiwaxinmc.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gtnrklpnlz.html

[R67] 生成随机十六进制串
来源：http://dali.yvedp.cn/Article/details/gtztizzdyx.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gtqcclwydl.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gtcygosbuh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gturzmfvrd.html

[R69] 生成随机密码
来源：http://dali.nanxinkj.top/Article/details/gtyriftqpm.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gtiipnclan.html

[R70] 时间戳与互转
来源：http://dali.yanxiufei.cn/Article/details/gtrdskldjp.html

date +%s;  date -d @1700000000
来源：http://dali.hammf.cn/Article/details/gtpllnjiqp.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtmlosphmi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gtztcctvqp.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gtcnqnwnfz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtzreokcwq.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpjivyoy.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudurfojc.html

[R74] 批量重命名
来源：http://dali.hnxiangtu.top/Article/details/gtlmewdyot.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cqqwz.cn/Article/details/gtmuunqesp.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtwxlbalvg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtaskvlljr.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gtcbtkbtsf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtirsrpqfv.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gtqygouxrm.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gtsvdtzewj.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gtdxyyvlpq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj202588.top/Article/details/gtpgeoyhrw.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gtdojcyxdv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cucudq.cn/Article/details/gtlacpxtay.html

[R80] 查看脚本执行耗时
来源：http://dali.xylfe.cn/Article/details/gtanyxkoyg.html

time ./run.sh
来源：http://dali.0kj1m.cn/Article/details/gtbnosvvyj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttcdonemp.html

S. C / C++ 专题
来源：http://dali.yanxiufei.cn/Article/details/gtqzwpiwbd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwrkmwctp.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtgumxhzde.html

#include <stdio.h>
来源：http://dali.hnxiangtu.top/Article/details/gtrrkrtgny.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sufxvd.cn/Article/details/gtevdhcyiq.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtduvxxeht.html

int a = 10; printf("%d\n", a);
来源：http://dali.gogol.net.cn/Article/details/gtotxdlenx.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gtebovfrkd.html

int x; scanf("%d", &x);
来源：http://dali.daxiang520.top/Article/details/gtsiyjvkbh.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gtycstqrvc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gtzaoroqll.html

[S05] C：字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqlyutqu.html

strlen(s)
来源：http://dali.sufxvd.cn/Article/details/gtuijgiuhk.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gtczkfuslv.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtcbulazep.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gtmgffdksz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dianchejie.cn/Article/details/gtgyzjqpze.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gtjitnovfe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafrkjkzy.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gtbcwnphcy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gtbkrplavs.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gtqltbcozl.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkuwyevp.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtqyimoeui.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gtxtlnguit.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtakvndhof.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzlwzwoi.html

[S12] C：写文件
来源：http://dali.hysaishi.cn/Article/details/gtqikovlrg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtkauqizdo.html

[S13] C：宏定义
来源：http://dali.hnqzz.top/Article/details/gtwzbgsiow.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.kuanghao11.cn/Article/details/gtebnmunpl.html

[S14] C：枚举
来源：http://dali.bjfxy.top/Article/details/gteiujpzqo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gtlyuiciav.html

[S15] C：类型转换
来源：http://dali.ybcxt.top/Article/details/gtaqlzkqhv.html

(double) a / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtninljyds.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gtlumeeszc.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtvsdxodmg.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtrhtosozh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.snrcjt.cn/Article/details/gtymtejlaj.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtznulvfqz.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthilalchq.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gtvjwszbxq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtwriqctux.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gtmdejmsjm.html


<!-- 参考信息 -->