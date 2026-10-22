代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtxswalkwg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gttighuzbb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zdqjudy.top/Article/details/gtxehnpccb.html

[Q49] 更新单行
来源：http://dali.cdnleiting.top/Article/details/gtqzabzgwk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtodixdljr.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gtildvxekf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cheryme.top/Article/details/gtgzdpsuhf.html

[Q51] 用子查询更新
来源：http://dali.feifeiyinyue.top/Article/details/gtxkjcrfpo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuanzx.com/Article/details/gtoozoitvo.html

[Q52] 删除指定行
来源：http://dali.xziqi.cn/Article/details/gtckeeqxzl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtgqwfdfiu.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gttbxwjrjm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gtcchrercy.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gtnklmotqa.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gtroftlypm.html

[Q55] 排名（并列占位）
来源：http://dali.tian-w.cn/Article/details/gtxqwudibf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj202588.top/Article/details/gtenkiawwp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhengqikj.top/Article/details/gtzjhstzeb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwzhacnd.html

[Q57] 行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnrmbcdw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtoumflxsm.html

[Q58] 累计求和
来源：http://dali.jyoumei.cn/Article/details/gtjkepycbq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtybskediw.html

[Q59] 分组内累计
来源：http://dali.zhongyouzk.top/Article/details/gtiksddycg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtbtqibshq.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gtbsofotpv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gtcmkupppn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtjueuylee.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gtmdtszcqy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtuwifxfld.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gtfonjuyae.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtikaykpez.html

[Q63] 开启事务
来源：http://dali.ydzc1.top/Article/details/gtbdoqxykw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gzhubu.top/Article/details/gtjyhwvstm.html

[Q64] 提交事务
来源：http://dali.aizwys.cn/Article/details/gtdazrexgb.html

COMMIT;
来源：http://dali.ehwqpu.com/Article/details/gtfxykkcrz.html

[Q65] 回滚事务
来源：http://dali.hongshengwenyu.top/Article/details/gtpuitqewf.html

ROLLBACK;
来源：http://dali.dashuyun.cn/Article/details/gtekwprtax.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gtpsepibgl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258888.top/Article/details/gtgltljdxt.html

[Q67] 设置隔离级别
来源：http://dali.hfpthk.cn/Article/details/gtfrkmvjoo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaduwbjtb.html

[Q68] 保存点
来源：http://dali.jianghu66.top/Article/details/gtwsqbgvjy.html

SAVEPOINT sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtccolgnjv.html

ROLLBACK TO sp1;
来源：http://dali.yj20258.top/Article/details/gtsakltioj.html

[Q69] 查看执行计划
来源：http://dali.meibo888.top/Article/details/gtvheqxkqa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigfzy.top/Article/details/gtglqknwob.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gtgubfhjcc.html

ANALYZE TABLE users;
来源：http://dali.yangfankeji.com/Article/details/gtrlmgmaar.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gtnunpfrbs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gtvqbwtefd.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gtwbzoenyo.html

SHOW INDEX FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gticnjgyvy.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpllrspl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gtizrezcje.html

[Q74] 强制使用索引
来源：http://dali.nanxinkj.top/Article/details/gtoavdkcvr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gtgkdmdjcu.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gthafdpsie.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtfbndgufh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daria6918.cn/Article/details/gtjebsqclh.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gtzzccxtog.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gtkxtfsrjr.html

[Q77] 时间加减
来源：http://dali.zhixingplan.top/Article/details/gtqliejssh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gtpkoodhdl.html

[Q78] 当前时间
来源：http://dali.dashuyun.cn/Article/details/gtwgfxubud.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cdnleiting.top/Article/details/gtccyvtmbs.html

[Q79] 字符串拼接
来源：http://dali.cashguo.top/Article/details/gtunsvsoth.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gtyeslwtba.html

[Q80] 字符串截取
来源：http://dali.pycfn.com/Article/details/gtgkldaccj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gtdadjvwlo.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtwoqaudol.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtqemwibvs.html

[Q82] 字符长度与字节长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsodibehd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtwtwhrtzu.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtysugadah.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtltakezmc.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gtuymfzmpm.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtlypdvuna.html

[Q85] 数值取整
来源：http://dali.vqdsnc.cn/Article/details/gtleghzrsv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gotoacloud.top/Article/details/gtabptiydu.html

[Q86] 读取 JSON 字段
来源：http://dali.cdnleiting.top/Article/details/gtinnodrou.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gtpuiupbjd.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gtfzfgbfjo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhengqikj.top/Article/details/gtrgfzttpn.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gthtyuxqck.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gtklpctvqa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtiqxavxvj.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gtrzzqbrwq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtvoxgfgic.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gttiskybeh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gtoonywipr.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtrnpabmiz.html

R. Bash 专题
来源：http://dali.c1oappe.top/Article/details/gtzqvnlpph.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtvzrqbvpb.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gtpginxyiu.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwpnckco.html

set -euo pipefail
来源：http://dali.316326.xyz/Article/details/gtdvqzmufu.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gtfvelgtyx.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gthxiqmulw.html

[R03] 只读变量
来源：http://dali.gzhubu.top/Article/details/gtubqtmbow.html

readonly PI=3.14
来源：http://dali.yonumen.top/Article/details/gtvyfmhztq.html

[R04] 位置参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvimolesv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gtleagsnrx.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gtpufrnwkj.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gtgtwbzvlm.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtkpfrnkzp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhvcighj.html

[R07] if 判断文件
来源：http://dali.ivvv.top/Article/details/gtckpnyeek.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gttayabmfy.html

[R08] 数值比较
来源：http://dali.tianlin.xyz/Article/details/gtqkavaxwq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gtuqlbocbt.html

[R09] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gtmqsfzcdf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuhffzna.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gtzcrulwwm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gtthszsxxj.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gtjtiemnux.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpnajhrm.html

start) echo "启动" ;;
来源：http://dali.yvedp.cn/Article/details/gtewisrypl.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gtslrpwewa.html

*)     echo "未知命令" ;;
来源：http://dali.pycfn.com/Article/details/gtrrymvrbi.html

esac
来源：http://dali.nanxinkj.top/Article/details/gtvyzocbnu.html

[R12] for 遍历文件
来源：http://dali.birdmap.top/Article/details/gtrompbziu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gtdzjiihzf.html

[R13] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gttelavsjl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtwinakudj.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gtzbzhkaso.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gteivsstsh.html

[R15] while 逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtasmqnkhj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtwlqxqwkj.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gtnmgdudwh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gtymembukd.html

[R17] 数组定义与取值
来源：http://dali.sxryk.cn/Article/details/gtqljasgjh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gtdkublajx.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gtnhdrnubr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xziqi.cn/Article/details/gtosrtweyo.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtnlovduje.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gtjebenwna.html

[R20] 关联数组（字典）
来源：http://dali.hnxiangtu.top/Article/details/gtuiczizlb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gtwpzudedt.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtxvmdwleq.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gtiiayjftn.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtlvhzioqt.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gtrrmvdqjv.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtvqsnyver.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gtnrppddho.html

[R24] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtvyhhobhw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ydzc1.top/Article/details/gtxelnbmmb.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gtymgkdofs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gthtvegyoc.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gtjhdfkuvm.html

now=$(date +%F); echo "$now"
来源：http://dali.meibo888.top/Article/details/gtoyynjxbz.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gttkydxtde.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gtelcokyeh.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gtuokahhfs.html

echo "scale=2; 10/3" | bc
来源：http://dali.havefunace.top/Article/details/gtoucsolzk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gtsjeknvbu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.quarkkingdee.top/Article/details/gtbjireros.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtgettikbt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.mhx1999.top/Article/details/gtuxlcqzih.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gtmegsxnro.html

f() { local x=1; echo "$x"; }
来源：http://dali.cdnleiting.top/Article/details/gtuqqdeaez.html

[R32] 参数个数校验
来源：http://dali.aizwys.cn/Article/details/gtkvddqkxj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtybmvdueh.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gtafogblqr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gtovoiabrg.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaucpwxpi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtnvlegtbe.html

[R35] 后台执行并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtmftcvpbv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtsgdocmab.html

[R36] 并发执行多个任务
来源：http://dali.feifeiyinyue.top/Article/details/gtoeczjrtu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yongpay.top/Article/details/gtdfeofvjv.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gtrclnawsv.html

files=$(ls -1)
来源：http://dali.jyoumei.cn/Article/details/gtadmpwhif.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gtwmcdsyzg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenjidiqi.icu/Article/details/gtotfpohcz.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtuqdrldda.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtvzyduxgq.html

[R40] 追加写日志
来源：http://dali.jlsjyb.cn/Article/details/gtnkokygrp.html

echo "log" >> out.log
来源：http://dali.hywenlv.cn/Article/details/gtpnbcbbvs.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gtbleabspc.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gttxmzyffm.html

[R42] 输入重定向
来源：http://dali.jinqigfzy.top/Article/details/gtotjnjcmh.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gtyerxvbkj.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvssoodhh.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtotwzhrtb.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gtezswmmbn.html

find . -mtime -7 -type f
来源：http://dali.jinqigfzy.top/Article/details/gtrzpnlfgr.html

[R45] 批量删除
来源：http://dali.jqgufenzy.top/Article/details/gtnusjansl.html

find . -name "*.tmp" -delete
来源：http://dali.jqgfzy.top/Article/details/gtqvxukgad.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gtzcdjlehi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gtwqmbssac.html

[R47] sed 单行替换
来源：http://dali.feifeiyinyue.top/Article/details/gtupelhpno.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gtwemydokh.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gtcaqaulbu.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtbzlxkzlv.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gtapuvwkil.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.svipenyu.cn/Article/details/gtaxhgtuvf.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gtpramwsjp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtnnrdkmuk.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gtckfcgcpt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gtgavoojaf.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gtcrfzyrja.html

wc -l a.txt
来源：http://dali.ehwqpu.com/Article/details/gtaxsqwlvk.html

[R53] 查看文件头与实时尾
来源：http://dali.hnxiangtu.top/Article/details/gtskfdsiay.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gtqnhsfrzx.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gtvdzmalfx.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gtsxjxjpqc.html

[R55] 压缩与解压
来源：http://dali.cheryme.top/Article/details/gtufwyzzyx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxuanxn.top/Article/details/gtgvvdoqjw.html

[R56] 远程拷贝
来源：http://dali.redwolf501.top/Article/details/gtnytldlyt.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gthjrsojpv.html

[R57] 远程执行命令
来源：http://dali.jyoumei.cn/Article/details/gtrdhtxnsw.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gtimqoqfiv.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gtycmszpfr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gtnibxbqzb.html

[R59] 发 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gtimqtgvsy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gtoniagdzk.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtkvtdjzdy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yanxiufei.cn/Article/details/gtceozlkkf.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gtqgxwoynt.html

df -h;  du -sh *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdofkgra.html

[R62] 找最占空间的文件
来源：http://dali.fzhhl.top/Article/details/gtjkqqrwfo.html

du -ah . | sort -rh | head -10
来源：http://dali.jianghu66.top/Article/details/gtmhrjgpig.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gtjyyyumwx.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gtwrbjkrji.html

[R64] 结束进程
来源：http://dali.zhengqikj.top/Article/details/gtvdnqrber.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gtpcammpcb.html

[R65] 查看端口占用
来源：http://dali.ivvv.top/Article/details/gtnnidlxjn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gtsehnkqde.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gtzdpklgxa.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gtgbcfnlqp.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gtutctqtwy.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gtzbfunkdy.html

[R68] 计算文件校验值
来源：http://dali.zhoulong.xyz/Article/details/gttvkgmior.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gtybrkxaxr.html

[R69] 生成随机密码
来源：http://dali.yuxming.cn/Article/details/gtcgaeojdn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gtbzrffdgy.html

[R70] 时间戳与互转
来源：http://dali.gogol.net.cn/Article/details/gtbyslyopn.html

date +%s;  date -d @1700000000
来源：http://dali.dashuyun.cn/Article/details/gtnikwgmon.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtnxomwygq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ydzc1.top/Article/details/gtnvenxcgw.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gttolgzacr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gthhldhqtr.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gtcwqqasos.html

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gttksqsqwq.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gtenzaaixh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gtxhpbffbl.html

[R75] 导出环境变量
来源：http://dali.jinqigufen.top/Article/details/gtmbuhtbhz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cqqwz.cn/Article/details/gtflttyfok.html

[R76] 使用临时文件
来源：http://dali.cqqwz.cn/Article/details/gtrycottwm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtssixxdpm.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gthmjouvqc.html

read -rp "请输入: " ans
来源：http://dali.sufxvd.cn/Article/details/gtyemagfah.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gtsfqdxuks.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtyarltkso.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfeipjqoz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jianghu66.top/Article/details/gtjrswquxt.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gtunldqmmc.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gtbpyxwhdl.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuxztmqr.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffifjabq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtyzxaeffv.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtsgchbzte.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gttiszuaeh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gtfcbxsomv.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gtmhycxwly.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gtteyltlui.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtzczxqbbt.html

int x; scanf("%d", &x);
来源：http://dali.andypj.xyz/Article/details/gtecmrsfko.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gtmmqwznbg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gtdccdrouo.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gtmtvvtdoh.html

strlen(s)
来源：http://dali.gaohongyu789.top/Article/details/gtdugisavf.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtgtimshvs.html

strcmp(a, b) == 0
来源：http://dali.guowangkeji.top/Article/details/gtqaifadci.html

[S07] C：数组遍历求和
来源：http://dali.hywenlv.cn/Article/details/gtmmooosix.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gtfkpgzigp.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gtohoffinc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jlsjyb.cn/Article/details/gtoayvulsw.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gtuzovqnls.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cdnleiting.top/Article/details/gtxzmqmlbo.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gtdkwcuijw.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtojoqxkeq.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtnxpznfdf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gtsvikdbar.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gttapggrgf.html

fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtfzkjcanj.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gtallgwhxg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtluqakalj.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gtrgjxvvtz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sweek.top/Article/details/gtvrvqiciz.html

[S14] C：枚举
来源：http://dali.sweek.top/Article/details/gtrmyyownw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gaohongyu789.top/Article/details/gtsgknwmgt.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gtitpriqom.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gtaxsezkks.html

[S16] C：位操作置位
来源：http://dali.gogol.net.cn/Article/details/gttwbgnywp.html

x |= (1 << 3);
来源：http://dali.vqdsnc.cn/Article/details/gtgdsdxfxb.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtgcddxucw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sxryk.cn/Article/details/gtrthftgnq.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gtfmxclwoq.html


<!-- 参考信息 -->