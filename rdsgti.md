代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtinsrvcie.html

[Q50] 批量更新
来源：http://dali.fengsongda.top/Article/details/gtuukxqpeq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yonumen.top/Article/details/gtquziywqk.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gtbscmwihl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hammf.cn/Article/details/gtsmptpnye.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gtrtndfoho.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gtihbkbpls.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gtfxjydnar.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zycfv.cn/Article/details/gttmzcywxa.html

[Q54] 清空表
来源：http://dali.yangfankeji.com/Article/details/gtqehmumrr.html

TRUNCATE TABLE logs;
来源：http://dali.jlsjyb.cn/Article/details/gtiuevwful.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtfivkrlgx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvcpqsbm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gtofusrfqp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtxiglfsvo.html

[Q57] 行号
来源：http://dali.nanxuanxn.top/Article/details/gtankfjter.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtwfeptunh.html

[Q58] 累计求和
来源：http://dali.yueranfly.top/Article/details/gtfmuntosd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtraxncfcw.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gtwblqzyja.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtqxqehcyp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhoulong.xyz/Article/details/gtcejxydzy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gtfvromocj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfbfmtmb.html

[Q61] 移动平均
来源：http://dali.haohaochexian.top/Article/details/gtkyqgzopy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtzbuduxal.html

[Q62] 分组占比
来源：http://dali.yuanzhike.top/Article/details/gtsgyyvfeq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gthxegkdlh.html

[Q63] 开启事务
来源：http://dali.ehwqpu.com/Article/details/gtyzglohfs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gtljkhaouu.html

[Q64] 提交事务
来源：http://dali.sxryk.cn/Article/details/gtlfezrfkd.html

COMMIT;
来源：http://dali.chenlongwang.top/Article/details/gtiqmsnvop.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtgeoqkncs.html

ROLLBACK;
来源：http://dali.hongshengwenyu.top/Article/details/gtpwkfqhfa.html

[Q66] 行锁查询
来源：http://dali.pycfn.com/Article/details/gtcafhtbbz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gtsmwxzuwu.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gttoycgbki.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258888.top/Article/details/gtbjphphzm.html

[Q68] 保存点
来源：http://dali.yvedp.cn/Article/details/gtbgqnpuzy.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gtajkvbwju.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gtkawqnmxc.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gtsmsxxizu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigfzy.top/Article/details/gtybtrvwhg.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gtuesnabgc.html

ANALYZE TABLE users;
来源：http://dali.wangshuangyany.cn/Article/details/gtlcffderr.html

[Q71] 查看建表语句
来源：http://dali.tianlin.xyz/Article/details/gtdkmfwoav.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tian-w.cn/Article/details/gtvmowomhu.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gthlpdckyx.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gtczzsrjae.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gtqipntywk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ybcxt.top/Article/details/gtxjsxbaot.html

[Q74] 强制使用索引
来源：http://dali.cucudq.cn/Article/details/gtrwrsxzwn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gtpnvwifhl.html

[Q75] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwnyvosd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtlfkegjex.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xziqi.cn/Article/details/gtsmlhzmjz.html

[Q76] 按天统计
来源：http://dali.zhoulong.xyz/Article/details/gtmiavdifh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gtctlrjglh.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gtnzembnpt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhongyouzk.top/Article/details/gtwmmrcihw.html

[Q78] 当前时间
来源：http://dali.bjfxy.top/Article/details/gtnlrmdkxo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangtech.top/Article/details/gtibwavesu.html

[Q79] 字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtvspxzgyt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jlsjyb.cn/Article/details/gtiyhozwpl.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gtlqgbwwtx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtoiqweqqr.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtkxpunbpn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtnnzelskr.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gtznaxtzez.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtndymfxbz.html

[Q83] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtxzvhykqh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtmsydsnnu.html

[Q84] 去除首尾空格
来源：http://dali.zhoulong.xyz/Article/details/gtirszarfx.html

SELECT TRIM(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtzvlykhsb.html

[Q85] 数值取整
来源：http://dali.xziqi.cn/Article/details/gttpdskaix.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ehwqpu.com/Article/details/gtldbcotqs.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gtvskgdvlr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cucudq.cn/Article/details/gtovonxzeg.html

[Q87] JSON 字段做条件
来源：http://dali.zdqjudy.top/Article/details/gtvaresgel.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhengqikj.top/Article/details/gtwskotiay.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gthmpecyji.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sufxvd.cn/Article/details/gtdegwfksb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.mhx1999.top/Article/details/gtvgprvczt.html

[Q89] 判断表是否存在
来源：http://dali.sweek.top/Article/details/gtvxcyijui.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yongpay.top/Article/details/gtftedlocr.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gtyuaxvkvb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guowangkeji.top/Article/details/gtixuhqhyb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqxdlvvrk.html

R. Bash 专题
来源：http://dali.daxiang520.top/Article/details/gtvanpxtmj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtwvuifpqz.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxzgpkxj.html

#!/usr/bin/env bash
来源：http://dali.sxryk.cn/Article/details/gtsllfwvfq.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gtjigthigx.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gtfwotgpzp.html

name="Tom"; echo "$name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndcauzhy.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gtsnhgkysw.html

readonly PI=3.14
来源：http://dali.hnxiangtu.top/Article/details/gtoezvhbku.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gtktbkctiq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtivudmrad.html

[R05] 参数默认值
来源：http://dali.ydzc1.top/Article/details/gtouegjfst.html

name="${1:-default}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnaelgpfg.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjfrblud.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtmnbkztgj.html

[R07] if 判断文件
来源：http://dali.dashuyun.cn/Article/details/gtvwqoaccy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guannengcc.top/Article/details/gtwiqkymap.html

[R08] 数值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupmeoaaq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gtjmscglbq.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtdwbojjfv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gtfderzytc.html

[R10] 正则匹配
来源：http://dali.yvedp.cn/Article/details/gtxbzvhsnr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtmvnxjohr.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gtaxjdxgur.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gtsgqtkjrx.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtblngnyoh.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gthqzksqyq.html

*)     echo "未知命令" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtubastooo.html

esac
来源：http://dali.xziqi.cn/Article/details/gtksaruucx.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gtxzapwnst.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tianlin.xyz/Article/details/gtndyrecmc.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtsokljcie.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtnieienjj.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gtdiimdinj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtdjkrgaee.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gtpsffehfx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jianghu66.top/Article/details/gttcyvvqby.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtnnmtupbx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtyntjcpdz.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbggomfni.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gtqhnzkixp.html

[R18] 遍历数组
来源：http://dali.daxiang520.top/Article/details/gtwppekqjs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrwpytor.html

[R19] 数组长度
来源：http://dali.yj20258888.top/Article/details/gtbdoesyza.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gtuufgcnwn.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gtodvxfufg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gtfgshafxp.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtpwausffn.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gtcsrsgivp.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gttslwewym.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gtxxkjncck.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtxnlnybmk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fengsongda.top/Article/details/gtfdoygtqy.html

[R24] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtuygpirju.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gtyvjrlqtj.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gtauzqwbts.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gtlhcybtyh.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gtzdrvqnkm.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258.top/Article/details/gthlfgdqvp.html

[R27] 算术展开
来源：http://dali.guannengcc.top/Article/details/gtlnfaidku.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigfzy.top/Article/details/gtkffcbeli.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gtyichbobh.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gttkcigdix.html

[R29] 定义函数
来源：http://dali.yvedp.cn/Article/details/gtkdbvtkou.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gtjvnbosba.html

[R30] 函数返回状态码
来源：http://dali.tianlin.xyz/Article/details/gtspfryzet.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgfzy.top/Article/details/gtaihabuql.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gttgugtsfs.html

f() { local x=1; echo "$x"; }
来源：http://dali.tianlin.xyz/Article/details/gtywhhdasg.html

[R32] 参数个数校验
来源：http://dali.jlsjyb.cn/Article/details/gttkldtsld.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gtlnlpmjco.html

[R33] 捕获错误并提示行号
来源：http://dali.kuanghao11.cn/Article/details/gtwwbyiyxy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gtkekrlmzn.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gtowabncev.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtoyirmklj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtdoqfrlzw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gtfwatgowh.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gtldpiprta.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gtiznmdcrp.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gtnjvjxkgb.html

files=$(ls -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtzbiqfvfm.html

[R38] 管道串联
来源：http://dali.aizwys.cn/Article/details/gtiwaisshp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gtyqiukocm.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gtpvlwjyfj.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtrkufouse.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdkiying.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gtvcpfwfhq.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gtikqcxapp.html

cmd >/dev/null 2>&1
来源：http://dali.yj202588.top/Article/details/gtyjtqnhmv.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gtlfthnsks.html

wc -l < a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtccecjyxf.html

[R43] 按名字查找文件
来源：http://dali.xziqi.cn/Article/details/gtaqtbgyhh.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gtxiyhnlff.html

[R44] 按修改时间查找
来源：http://dali.yonumen.top/Article/details/gtxmnoztxw.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gtkomuvlii.html

[R45] 批量删除
来源：http://dali.hfpthk.cn/Article/details/gtinrpysor.html

find . -name "*.tmp" -delete
来源：http://dali.guannengcc.top/Article/details/gtakwdfysb.html

[R46] 递归替换文件内容
来源：http://dali.sufxvd.cn/Article/details/gtzkthjozq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxinkj.top/Article/details/gtpxjgfbnn.html

[R47] sed 单行替换
来源：http://dali.guowangkeji.top/Article/details/gtwxtgdpet.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtgkgreufn.html

[R48] awk 取指定列
来源：http://dali.dashuyun.cn/Article/details/gtvyrbrhxg.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtlnpebxfd.html

[R49] awk 带条件
来源：http://dali.nanxinkj.top/Article/details/gtchnfyeaz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.9152youxi.cn/Article/details/gtngwxvryu.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gtxxpapwdm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtzimkrdbg.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gtlhjgyyne.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gtjxzmugan.html

[R52] 统计行数
来源：http://dali.wangshuangyany.cn/Article/details/gtwrepxjmk.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gtlahinetv.html

[R53] 查看文件头与实时尾
来源：http://dali.hywenlv.cn/Article/details/gtzpzvirgs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gthoiyzret.html

[R54] 比较两个文件
来源：http://dali.aizwys.cn/Article/details/gthyqvleia.html

diff a.txt b.txt
来源：http://dali.hfpthk.cn/Article/details/gtlhxyakzl.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gtdgouibzr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuxming.cn/Article/details/gtgpgyuadv.html

[R56] 远程拷贝
来源：http://dali.gogol.net.cn/Article/details/gtatikvncc.html

scp file user@host:/path/
来源：http://dali.iojbl.cn/Article/details/gtlhdwzyap.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gthhuwtvoo.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gttpdykpdz.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtniyzhgxf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gtkiqpdxsw.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtaktwiujv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gttqkvdpcj.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gtyrmvhjkn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfhjvinj.html

[R61] 磁盘占用
来源：http://dali.sweek.top/Article/details/gtrwfozqjt.html

df -h;  du -sh *
来源：http://dali.pengpengdd.cyou/Article/details/gtwzhqgxke.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gtgncqrjre.html

du -ah . | sort -rh | head -10
来源：http://dali.tianlin.xyz/Article/details/gtveyuafdq.html

[R63] 内存与进程
来源：http://dali.zhongyouzk.top/Article/details/gtvgehwwes.html

free -h;  ps aux | grep nginx
来源：http://dali.vqdsnc.cn/Article/details/gtbfygcata.html

[R64] 结束进程
来源：http://dali.wangshuangyany.cn/Article/details/gtkkhbvyjv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.redwolf501.top/Article/details/gtozomwtfl.html

[R65] 查看端口占用
来源：http://dali.yj20258888.top/Article/details/gtnnuwtibf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gtedpbxjep.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gttixfhdlh.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gtupclqcze.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gtiafznzku.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gtpnlqgdcy.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gtzaddxyec.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.0kj1m.cn/Article/details/gtdpdblcar.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gtxggyjxri.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gtqyjnxsay.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gtohcdaywj.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gtwsincqdu.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtjhvzhejm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtwmpwejou.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtxwvnrtvu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtppjlqyld.html

[R73] 分割大日志
来源：http://dali.hammf.cn/Article/details/gtnsoucxto.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gtikarexyt.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gtgngtmeqe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtmltykuls.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gtbcezbbim.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ivvv.top/Article/details/gteftqclyb.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gtwzjsjcfj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gtwfldrnmr.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gtjzbfxpbl.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtqxhqyctq.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gtyhxeviwi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gtxlirxvql.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gtwdqzyfhb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shzxlz.cn/Article/details/gtbilcrrqt.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gtwmuscykb.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gtqkirsyvv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtbcjonufm.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gthgznvpzb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtnnlutjla.html

[S01] C：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtotzwaxwk.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gtecwtapfh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgufenzy.top/Article/details/gtkgpkakvu.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtilmfzvur.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuanzx.com/Article/details/gthnkgjfll.html

[S03] C：读入整数
来源：http://dali.sufxvd.cn/Article/details/gtyuvmxvmu.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtdajjddeu.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gtnhsabrjt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yonumen.top/Article/details/gtxgjqvcia.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gthzoxonkc.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gtoqrfwidg.html

[S06] C：字符串比较
来源：http://dali.havefunace.top/Article/details/gtrwuvqhke.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gtbkirojic.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gtzdlhtons.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gzhubu.top/Article/details/gteymvdqoh.html

[S08] C：动态内存分配与释放
来源：http://dali.aizwys.cn/Article/details/gtaamtmygs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gtpqmmappb.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gtrvkrzsdi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gtxkehzinx.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gthwiodaav.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gtdydaxoyg.html

[S11] C：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtpjapuqrz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gtekwwmwsv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gtbbtehsvh.html

fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtcpgseepu.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtuwrmpgxe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtirwcgviw.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gtljifhvsn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yvedp.cn/Article/details/gtpqjrgcgr.html

[S14] C：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbqkrasa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gtjcsllqul.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gtmchizajb.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gtmhbykfsm.html

[S16] C：位操作置位
来源：http://dali.redwolf501.top/Article/details/gtkipgdvnx.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gtzzrdopis.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtukeyhrzw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gtzskyjfcm.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gtxdijgkqb.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gtutxgiqta.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gttczxkhnc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtrfsjrgat.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gtqknnfkog.html


<!-- 参考信息 -->