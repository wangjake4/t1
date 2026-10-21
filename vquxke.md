代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtlqvszwwv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzzgseqv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtsycdxhkq.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gtkhsatfhc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ivvv.top/Article/details/gtxtopwhpj.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gtcgzhpwmj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtploqkseu.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gtipqqnlvu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtjxfkujkp.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnqzz.top/Article/details/gthnokgnfk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gtmxnksiff.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtgarjxxhx.html

[Q61] 移动平均
来源：http://dali.feifeiyinyue.top/Article/details/gtzyeqejsw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtgvyqnrxb.html

[Q62] 分组占比
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfzcnhqs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtzhwrnste.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gtutjmcmzv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuanzhike.top/Article/details/gthmcrqwxs.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtfcwgusjo.html

COMMIT;
来源：http://dali.bjfxy.top/Article/details/gtkoqjubqo.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gtkjopweas.html

ROLLBACK;
来源：http://dali.gotoacloud.top/Article/details/gtmdgivwzg.html

[Q66] 行锁查询
来源：http://dali.daxiang520.top/Article/details/gtvdlbfoyw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtfwhrsnws.html

[Q67] 设置隔离级别
来源：http://dali.hnxiangtu.top/Article/details/gtpkqtsnvu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gtabpcwakp.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gtfdovatvm.html

SAVEPOINT sp1;
来源：http://dali.xinyue.icu/Article/details/gtnobdnojn.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gtagnjwfob.html

[Q69] 查看执行计划
来源：http://dali.jiagoushi.top/Article/details/gtxdcnbnff.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gtdxtobfyk.html

[Q70] 更新统计信息
来源：http://dali.yj20258888.top/Article/details/gtxknkngnj.html

ANALYZE TABLE users;
来源：http://dali.yj202588.top/Article/details/gtfbsbcxoc.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gtpekagwba.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gtitfmqkis.html

[Q72] 查看索引
来源：http://dali.havefunace.top/Article/details/gttawirlja.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtmlxwczeg.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gtufsouzbi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gtrkxrqnuj.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gtxtoddomr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gtvkpxycoq.html

[Q75] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtbjyfwnhg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtqarlogql.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aizwys.cn/Article/details/gtjyvaurwc.html

[Q76] 按天统计
来源：http://dali.gotoacloud.top/Article/details/gtwynwkywq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gtxaqrtmmg.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gtpybasvmb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gtsxsittdn.html

[Q78] 当前时间
来源：http://dali.guowangkeji.top/Article/details/gtkajvbsgn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gtudhpxxmp.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gteemuovek.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xziqi.cn/Article/details/gtsecsklem.html

[Q80] 字符串截取
来源：http://dali.yj20258.top/Article/details/gtubbtjzst.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtwlfifwxu.html

[Q81] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtaftjlilb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtasfergws.html

[Q82] 字符长度与字节长度
来源：http://dali.gaohongyu789.top/Article/details/gtvczfbkit.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtqhnxscau.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtmtsahmpl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtozfvubla.html

[Q84] 去除首尾空格
来源：http://dali.aizwys.cn/Article/details/gtxnigcwae.html

SELECT TRIM(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtkbwnxhvu.html

[Q85] 数值取整
来源：http://dali.ppjwa.cn/Article/details/gtcthjdnyp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenjidiqi.icu/Article/details/gtpzdbsdaj.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gtnirvkmfd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gtiomzmfgb.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gtrlurgtny.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sxryk.cn/Article/details/gtmizwwapk.html

[Q88] 行转列（条件聚合）
来源：http://dali.cucudq.cn/Article/details/gttofpkdqv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gtgmltvyhb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtragpvnzs.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gtridqwwhx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtalsxulkp.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gtdomodmfe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkxukrle.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtqhxeiacw.html

R. Bash 专题
来源：http://dali.fzhhl.top/Article/details/gthumvlovn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtnnhskcmn.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenpobqrg.html

#!/usr/bin/env bash
来源：http://dali.haohaochexian.top/Article/details/gtjtnaaapg.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gtwmkwvqnl.html

[R02] 变量赋值与使用
来源：http://dali.jlsjyb.cn/Article/details/gtfuwfthwx.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gtxclcmyid.html

[R03] 只读变量
来源：http://dali.gogol.net.cn/Article/details/gtwngzslpk.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gtdkwuldyw.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gtbkjfzazk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gtvgktfbjy.html

[R05] 参数默认值
来源：http://dali.ydzc1.top/Article/details/gttjddbqov.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gtjwffbdgu.html

[R06] 判断命令是否存在
来源：http://dali.tanke756.top/Article/details/gtvmfmfvxk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtvcihyjgw.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gtmerxgqxr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtxfugmksk.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gtundwffmh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.havefunace.top/Article/details/gtvicchebk.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gtjmbgbcok.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cucudq.cn/Article/details/gtgzczqlwc.html

[R10] 正则匹配
来源：http://dali.snrcjt.cn/Article/details/gtnrojtwez.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtlduegrjn.html

[R11] case 多分支
来源：http://dali.hongshengwenyu.top/Article/details/gtvwawgvcz.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtxltwvuhr.html

start) echo "启动" ;;
来源：http://dali.yuanzhike.top/Article/details/gtnackorvt.html

stop)  echo "停止" ;;
来源：http://dali.gotoacloud.top/Article/details/gtheyrznjf.html

*)     echo "未知命令" ;;
来源：http://dali.0kj1m.cn/Article/details/gtzvsflzff.html

esac
来源：http://dali.hongshengwenyu.top/Article/details/gtfuswfpxs.html

[R12] for 遍历文件
来源：http://dali.nwbrower.top/Article/details/gthawxsfla.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gtsrrgldoc.html

[R13] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gtvpwunkal.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtervkxhsa.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gtszozhivy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtwroeodsy.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtmenwljpb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelhdqsnn.html

[R16] until 等待条件
来源：http://dali.yangfankeji.com/Article/details/gtwnqqbfgc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtshhtrfcv.html

[R17] 数组定义与取值
来源：http://dali.sysykeji.top/Article/details/gtsotxvbtz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwakitmc.html

[R18] 遍历数组
来源：http://dali.iojbl.cn/Article/details/gtgxcphkkd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gtpnismztz.html

[R19] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gtqjosmqsi.html

echo "${#arr[@]}"
来源：http://dali.yanxiufei.cn/Article/details/gtkprztwdt.html

[R20] 关联数组（字典）
来源：http://dali.yj20258.top/Article/details/gtrxwtiaxb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gtncyrxxjx.html

[R21] 字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtcvrstrjr.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gtpztxjlts.html

[R22] 截取子串
来源：http://dali.zycfv.cn/Article/details/gtzxxsjozl.html

echo "${s:0:5}"
来源：http://dali.zycfv.cn/Article/details/gtnssujfaf.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjgconjm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gtwjroshqb.html

[R24] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gthfezlnlh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gtfagdshki.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gtpxzjxoai.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cashguo.top/Article/details/gtaaugnddr.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gtdqspnnop.html

now=$(date +%F); echo "$now"
来源：http://dali.yanxiufei.cn/Article/details/gtnejgtfca.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtspphqjsq.html

echo $((1 + 2 * 3))
来源：http://dali.sxryk.cn/Article/details/gtwzhicuiq.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gthwjkxmso.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gtymmdqxlp.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gtkbmivcjz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gtojtmvovv.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gtanqeqcms.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hywenlv.cn/Article/details/gtohybglnv.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gtnaiebnov.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gtxvnusmqm.html

[R32] 参数个数校验
来源：http://dali.pycfn.com/Article/details/gtfcjmwqyx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtgaalypsu.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gtrdfdomsr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.kuanghao11.cn/Article/details/gtzqhgtefw.html

[R34] 退出时清理
来源：http://dali.haohaochexian.top/Article/details/gtlmzuoayo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtxjkdohfe.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtqdgythvr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gtypbpvxoo.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzmefmfa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gtikuaqyzy.html

[R37] 把输出赋给变量
来源：http://dali.zhengqikj.top/Article/details/gtnuforjbz.html

files=$(ls -1)
来源：http://dali.gogol.net.cn/Article/details/gtqybgshej.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gtqansmtlq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gtkhkmdyjx.html

[R39] 重定向标准输出与错误
来源：http://dali.aibaodan.cn/Article/details/gtmxedjffo.html

cmd > out.log 2>&1
来源：http://dali.fengsongda.top/Article/details/gtbdqbetpz.html

[R40] 追加写日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtomnzkgpn.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gtuivgutbg.html

[R41] 丢弃输出
来源：http://dali.zycfv.cn/Article/details/gtngxywetd.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gtccaaknvw.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gtvawngokk.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrxktvjw.html

[R43] 按名字查找文件
来源：http://dali.mhx1999.top/Article/details/gtbdvusnjq.html

find . -name "*.log" -type f
来源：http://dali.pycfn.com/Article/details/gtseojrraz.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gtmtbjndzc.html

find . -mtime -7 -type f
来源：http://dali.guannengcc.top/Article/details/gtekqjhwiu.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtuonoydnc.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gtyxelzojz.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gtccfskcqs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yanxiufei.cn/Article/details/gtinicaeby.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gtlirzzfcb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sweek.top/Article/details/gtkbyrqzuk.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gtyqgkfqil.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtbbudfcfm.html

[R49] awk 带条件
来源：http://dali.hfpthk.cn/Article/details/gtezffwxmi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhengqikj.top/Article/details/gtmncpbshc.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gtvajfkybd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtdwgqgbyu.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtplkxiadm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.0kj1m.cn/Article/details/gtyywrkmjp.html

[R52] 统计行数
来源：http://dali.yvedp.cn/Article/details/gtyieruvnu.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gtbodahkoe.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gtjkcofzol.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftljmfuf.html

[R54] 比较两个文件
来源：http://dali.ppjwa.cn/Article/details/gtkypahaaz.html

diff a.txt b.txt
来源：http://dali.iojbl.cn/Article/details/gtslgwjvmd.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gtwbivhfxk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gtkfswsrwl.html

[R56] 远程拷贝
来源：http://dali.dianchejie.cn/Article/details/gtonuftmxj.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gtcgzzsugm.html

[R57] 远程执行命令
来源：http://dali.ivvv.top/Article/details/gtwhnkpuyj.html

ssh user@host 'uptime'
来源：http://dali.hongshengwenyu.top/Article/details/gtamfncgsh.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gthvdtctlz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gtqjdpuzux.html

[R59] 发 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtwfmunfex.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gtcyyhmcrc.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtdviaxhpa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gtsftjaoqw.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gtuaskposq.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gtxsxgymdu.html

[R62] 找最占空间的文件
来源：http://dali.jinqigufen.top/Article/details/gtkkjmgonr.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyclhlty.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gtgxaejode.html

free -h;  ps aux | grep nginx
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkgfdnri.html

[R64] 结束进程
来源：http://dali.hywenlv.cn/Article/details/gttywjdpiz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gtswjkviur.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gtadhudcyc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuxming.cn/Article/details/gtowtzqzdq.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtimrlmiks.html

crontab -e;  crontab -l
来源：http://dali.dianchejie.cn/Article/details/gtwwbegrac.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gttbiouzff.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gtcyklfelv.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gtkwnallyv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gtexnksjsl.html

[R69] 生成随机密码
来源：http://dali.meibo888.top/Article/details/gtctcouwhi.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtjcbtlspm.html

[R70] 时间戳与互转
来源：http://dali.snrcjt.cn/Article/details/gtaswjgoss.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gtfifgficf.html

[R71] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtwclhrpsm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtmxyuaezj.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gtbcbwileh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtslxccvnm.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gtqwjnhpyp.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gtqsvyhigi.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gtjdiluxvi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gtnmqlclna.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gtpnslipcb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gtgbqslzeu.html

[R76] 使用临时文件
来源：http://dali.yueranfly.top/Article/details/gtdqxforyp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtqmocarbl.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gtgysyjuuk.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gtivewrzss.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gthkknnkne.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gtmjjscche.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gtrxbcjsxm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gtrcyoxexf.html

[R80] 查看脚本执行耗时
来源：http://dali.jlsjyb.cn/Article/details/gthorxqzsz.html

time ./run.sh
来源：http://dali.bjfxy.top/Article/details/gtkzdthecu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvmfcrnyb.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gtcyfzzcrf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtqvqwemjy.html

[S01] C：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtaepeygwh.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gtjtzuswgz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzfkvmrxt.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gtxdnooihv.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangshuangyany.cn/Article/details/gtqgewcfgt.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gtezucngra.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gtpedkogqj.html

[S04] C：字符串复制
来源：http://dali.sweek.top/Article/details/gtmxapjayh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtbkrbzkmf.html

[S05] C：字符串长度
来源：http://dali.meibo888.top/Article/details/gtkdaxxgdc.html

strlen(s)
来源：http://dali.jqgufenzy.top/Article/details/gtlydthxzg.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtnvkqlteg.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gtvsecwakj.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gtupsnzlyj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gtbdxdcwcx.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxuanxn.top/Article/details/gtfjzwgcur.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gtmdabnjhv.html

[S09] C：结构体定义与初始化
来源：http://dali.yuxming.cn/Article/details/gthbqmhrkd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.svipenyu.cn/Article/details/gtvjkxnzra.html

[S10] C：指针与解引用
来源：http://dali.dianchejie.cn/Article/details/gtgcgfyqum.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258888.top/Article/details/gtbakaqnbw.html

[S11] C：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtnewklnqr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gtblucxutm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuxming.cn/Article/details/gtafratggb.html

fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtisyxchci.html

[S12] C：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduzoakkl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gttrhvqdpq.html

[S13] C：宏定义
来源：http://dali.cdnleiting.top/Article/details/gtjovjymqa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gtnnkyfnei.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gtoyuodyqu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuanzhike.top/Article/details/gtmwafsggs.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtyrfaplor.html

(double) a / b
来源：http://dali.nanxinkj.top/Article/details/gtginnxfnn.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gtahwtkokv.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gtfcklnxeo.html

[S17] C：安全拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtnpnqhoua.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gtruufgogd.html

[S18] C：命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtuoelscjv.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtjakgwtck.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gtfryhaaly.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtqricdsox.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gteysoajpl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtfbgtdxec.html

[S21] C：字符类别判断
来源：http://dali.fzhhl.top/Article/details/gtfqlvglyu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yonumen.top/Article/details/gtkuyqvyim.html

[S22] C：字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuncnhloz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gtizgzwvut.html

[S23] C：随机数
来源：http://dali.jlsjyb.cn/Article/details/gtalyhpwma.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gtnlxhdznz.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gtstlcubfh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtekxexnum.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtnyhgakvs.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gthxtfbsvm.html

[S26] C：内存清零
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnruqhqf.html


<!-- 参考信息 -->