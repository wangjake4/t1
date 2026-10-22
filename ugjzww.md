代发 wailian999

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gtvpqzefgk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtorzjpkaj.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gtshbjmmfm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gttwnuxdid.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gtzcrxdtze.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gtptfreppe.html

[Q64] 提交事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnppfpmu.html

COMMIT;
来源：http://dali.fengsongda.top/Article/details/gtuyratncf.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gtiarcldxn.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gtdnzxmefk.html

[Q66] 行锁查询
来源：http://dali.haohaochexian.top/Article/details/gtfbnhpgou.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrhzsepl.html

[Q67] 设置隔离级别
来源：http://dali.xziqi.cn/Article/details/gtqslcxajt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gttknshfbp.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gtvqgnqxyw.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtsnxkqdyj.html

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gtbhewvhdw.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gtteihyhsf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cucudq.cn/Article/details/gtjvbylsta.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gtiwmdldvs.html

ANALYZE TABLE users;
来源：http://dali.shuidangran.top/Article/details/gtduptfosc.html

[Q71] 查看建表语句
来源：http://dali.cqqwz.cn/Article/details/gtxbkyoalv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtxnggkyyp.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gthvtrncqp.html

SHOW INDEX FROM users;
来源：http://dali.hywenlv.cn/Article/details/gthezclenu.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gtntdcutsn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gtisciotjh.html

[Q74] 强制使用索引
来源：http://dali.jlsjyb.cn/Article/details/gtooxmqduj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxcevwgj.html

[Q75] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gtpevhzifi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtfretdstl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gtkixfpquq.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gtfudrchiu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gtdniwxazh.html

[Q77] 时间加减
来源：http://dali.jyoumei.cn/Article/details/gttcxjwznq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gtvknhoojl.html

[Q78] 当前时间
来源：http://dali.hfpthk.cn/Article/details/gtlpozgoge.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cdnleiting.top/Article/details/gtrtihuqql.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtilodnucu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sweek.top/Article/details/gtshazvwdu.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gtbyvukgqv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.havefunace.top/Article/details/gtehjgbcyx.html

[Q81] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtlfbnjlxj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtqtemkfzy.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gtfrccnhie.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtnicagtjr.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtqyslebmu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtqvcwmflt.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gtvdmyvtdt.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtaqnfoncy.html

[Q85] 数值取整
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzvsqgke.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gtumzlcgcl.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gtocfjnnjv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gtfhkmchhf.html

[Q87] JSON 字段做条件
来源：http://dali.daria6918.cn/Article/details/gtiwugrblj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gtvdhnvtdr.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gtpbwpvjyj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.316326.xyz/Article/details/gtwtzuxqjo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfieqxfa.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gtfodrpisc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhengqikj.top/Article/details/gtuafuvewz.html

[Q90] 生成序号列
来源：http://dali.smart0.xyz/Article/details/gtiptlotcs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.redwolf501.top/Article/details/gtzjxpwajl.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtyrqbvqwl.html

R. Bash 专题
来源：http://dali.cashguo.top/Article/details/gtachbvttv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtchdhkukb.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gtungumpmd.html

#!/usr/bin/env bash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdhjnlpu.html

set -euo pipefail
来源：http://dali.ehwqpu.com/Article/details/gtsibeymfz.html

[R02] 变量赋值与使用
来源：http://dali.feifeiyinyue.top/Article/details/gtvkwjaigz.html

name="Tom"; echo "$name"
来源：http://dali.0kj1m.cn/Article/details/gthvgujyhm.html

[R03] 只读变量
来源：http://dali.cucudq.cn/Article/details/gtwsmgumbi.html

readonly PI=3.14
来源：http://dali.zycfv.cn/Article/details/gtftctmijl.html

[R04] 位置参数
来源：http://dali.hnxiangtu.top/Article/details/gtxcjowtyl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gtqjrojqcu.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gtrsldnttu.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gtzfbezudr.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gtzwkzulak.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtnmiguhuf.html

[R07] if 判断文件
来源：http://dali.chenzaomai.com/Article/details/gtoetptnmg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cdnleiting.top/Article/details/gtyfgvdbco.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gtgkcejqmx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gtpzsqvcrl.html

[R09] 字符串比较
来源：http://dali.iojbl.cn/Article/details/gtvhoawgel.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pycfn.com/Article/details/gtbabndqpk.html

[R10] 正则匹配
来源：http://dali.dianchejie.cn/Article/details/gtfqrmgohu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gtzkykbxyt.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gtncwjvlwx.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozidobtr.html

start) echo "启动" ;;
来源：http://dali.zhengqikj.top/Article/details/gtwpeqifvk.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gtkkukorkl.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtvosoeooa.html

esac
来源：http://dali.sxryk.cn/Article/details/gtiufpuwtq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gtyfvjalsm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gthhmrppbx.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gtrspplewr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtbrefzrdw.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gtqtqvyxec.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtsuahewvx.html

[R15] while 逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtkybceglr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxuanxn.top/Article/details/gtdqifehpq.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gtwhozkzgh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtnbbvlvyx.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gtritdppmo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258888.top/Article/details/gtmivdlozj.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gtodzrgscg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gtqucyhqoh.html

[R19] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuusphts.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gtnofitnte.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gtpdalqcqe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtligsyqks.html

[R21] 字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtqcjqvkjf.html

echo "${#s}"
来源：http://dali.tian-w.cn/Article/details/gtqlypbwoe.html

[R22] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtwiewxann.html

echo "${s:0:5}"
来源：http://dali.hongshengwenyu.top/Article/details/gtfqegnpca.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtfllyjncs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtdytiwqkp.html

[R24] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtorzlmjsb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.bjfxy.top/Article/details/gtdguygejg.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gtxgvlxdcg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.redwolf501.top/Article/details/gtczzcfmxo.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gtevwspxrx.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gtvepwuruw.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gthlygrgdt.html

echo $((1 + 2 * 3))
来源：http://dali.c1oappe.top/Article/details/gtvafsrrxs.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gtyovmaudi.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgpqsbog.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtgdgupncp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gtrsexwdam.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtrqiqncej.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gtkhutwdap.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtpyrfevsv.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtovanukhw.html

[R32] 参数个数校验
来源：http://dali.zycfv.cn/Article/details/gtwhjeewyy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtrxodowmn.html

[R33] 捕获错误并提示行号
来源：http://dali.yj202588.top/Article/details/gtkuauuqgm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gtbmprljui.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gtfascroms.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtrbaanzko.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gtwlkjnwnm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gtqjhoraoi.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gtgzhcquta.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gthpcyzvgu.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gtsgunodsd.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gtbhvuhmpc.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gttzytlnfj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gtmlfqzjif.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gtppgqwgsj.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gtzaewrzgr.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gtpkvsgbme.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gtcddlaabp.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gtcwpmzxpw.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gtscoabjpf.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gtpwppcdzl.html

wc -l < a.txt
来源：http://dali.xziqi.cn/Article/details/gtxlrbkjpm.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gtzsrnjkll.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gtfwuajwpf.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gtlofpvnfz.html

find . -mtime -7 -type f
来源：http://dali.yueranfly.top/Article/details/gtydqkloim.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gtybotptsm.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gtcdehwjtc.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gttqaxncku.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cucudq.cn/Article/details/gtglmjtqdy.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gtljangzwo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmjkjsbw.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gtclxlsgkz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtomnhgpcj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gtpruaafiz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.svipenyu.cn/Article/details/gttuuprtui.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gtlpwpeedn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtjqofyims.html

[R51] 排序去重取前几
来源：http://dali.gaohongyu789.top/Article/details/gtzzeizcsd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gtmiozwgyw.html

[R52] 统计行数
来源：http://dali.redwolf501.top/Article/details/gtyebuqdpv.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gtkctcoohf.html

[R53] 查看文件头与实时尾
来源：http://dali.yueranfly.top/Article/details/gtsyrmbonr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.kuanghao11.cn/Article/details/gticuifpqb.html

[R54] 比较两个文件
来源：http://dali.jiagoushi.top/Article/details/gtqoochgmd.html

diff a.txt b.txt
来源：http://dali.gogol.net.cn/Article/details/gtqltgghlt.html

[R55] 压缩与解压
来源：http://dali.cashguo.top/Article/details/gtzjczdbcj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.snrcjt.cn/Article/details/gtpnjqfqac.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gtxudvnyrr.html

scp file user@host:/path/
来源：http://dali.havefunace.top/Article/details/gtcwvvewxt.html

[R57] 远程执行命令
来源：http://dali.zhiwuduotai.top/Article/details/gtqphuxpxe.html

ssh user@host 'uptime'
来源：http://dali.pengpengdd.cyou/Article/details/gttkhuufmh.html

[R58] 下载文件
来源：http://dali.ybcxt.top/Article/details/gtdnlfvdiy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gtysdrxfdc.html

[R59] 发 POST JSON
来源：http://dali.havefunace.top/Article/details/gtqejelduc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gthntyicdf.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gttqlbnoei.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gtevvktpgt.html

[R61] 磁盘占用
来源：http://dali.yongpay.top/Article/details/gthncnbopr.html

df -h;  du -sh *
来源：http://dali.pengpengdd.cyou/Article/details/gtjamsaoqf.html

[R62] 找最占空间的文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppaxliji.html

du -ah . | sort -rh | head -10
来源：http://dali.chenjidiqi.icu/Article/details/gtacazzqvk.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtonxrjhjh.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gtrrwcasdc.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gtdintbvju.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gtvtqfobzw.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gtbuzicefy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxeqvcftn.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxqbfmbg.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gtrevirkmu.html

[R67] 生成随机十六进制串
来源：http://dali.yj202588.top/Article/details/gtgupruzdc.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gtxqlvfyur.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gttysyzgxy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tian-w.cn/Article/details/gtpsmyktdr.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gtvqwvlaqj.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gtquwhctwx.html

[R70] 时间戳与互转
来源：http://dali.yangfankeji.com/Article/details/gtycgjyhvk.html

date +%s;  date -d @1700000000
来源：http://dali.ivvv.top/Article/details/gtkpltyvnn.html

[R71] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gtajpazaxr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gtfbaczkxg.html

[R72] 等待端口就绪
来源：http://dali.jinqigfzy.top/Article/details/gtnyyrzuhh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gttlqncpiw.html

[R73] 分割大日志
来源：http://dali.daria6918.cn/Article/details/gtosernkmt.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gtoisqreqx.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmecnxguq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszjmnvwa.html

[R75] 导出环境变量
来源：http://dali.jiagoushi.top/Article/details/gtwhylwnsg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gtwmuipnpz.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gtoaiqybnh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gtsxigtolu.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gtokqnnusg.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gtuiewqzvg.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gtmsdwmhsb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gtajkjcban.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gtsqgdilvu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tanke756.top/Article/details/gtdoftbgub.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gtygxsrjyt.html

time ./run.sh
来源：http://dali.bjfxy.top/Article/details/gthmkbdrzt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtsegbcvqx.html

S. C / C++ 专题
来源：http://dali.yongpay.top/Article/details/gtisrgdgkk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjkwmbgef.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gtgshzfjgw.html

#include <stdio.h>
来源：http://dali.nanxinkj.top/Article/details/gttwfezqtx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.316326.xyz/Article/details/gtdulyhpnw.html

[S02] C：变量与格式化输出
来源：http://dali.tian-w.cn/Article/details/gtmcvjmggu.html

int a = 10; printf("%d\n", a);
来源：http://dali.cucudq.cn/Article/details/gtlexatixe.html

[S03] C：读入整数
来源：http://dali.yj20258.top/Article/details/gtwchjohes.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gtbaxtcgkn.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gthjsgkukq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tianlin.xyz/Article/details/gtunajnteu.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtauewezwu.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gtnjjbvabj.html

[S06] C：字符串比较
来源：http://dali.birdmap.top/Article/details/gtenkbonhx.html

strcmp(a, b) == 0
来源：http://dali.ehwqpu.com/Article/details/gtuaciqdyo.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gtaoqrlbtj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cqqwz.cn/Article/details/gtiazqrzfe.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gtegmxtqvb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gtwjzwqabs.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gtidyebjku.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigufen.top/Article/details/gtijhykhmh.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtpeezaznb.html

int *p = &a;  *p = 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtdovgeevs.html

[S11] C：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtfrinxzhf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.vqdsnc.cn/Article/details/gtxltsuogd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.bjfxy.top/Article/details/gtcqgelikd.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gterkswvsy.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gtyfyzonfv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrrqpdci.html

[S13] C：宏定义
来源：http://dali.kuanghao11.cn/Article/details/gtyzbzoadr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gtavrkches.html

[S14] C：枚举
来源：http://dali.sysykeji.top/Article/details/gtfzorquyq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nwbrower.top/Article/details/gtsysnqlfi.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gtpgslobdy.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gtgagtwclk.html

[S16] C：位操作置位
来源：http://dali.jianghu66.top/Article/details/gtatkqodtx.html

x |= (1 << 3);
来源：http://dali.yuanzhike.top/Article/details/gtpdyrgmtv.html

[S17] C：安全拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakfmgvyq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtkkrphvgs.html

[S18] C：命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtcifeqlpd.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhzqsstw.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gtrdkbdzle.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtnyctvjil.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gticszhlos.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtnsdlpbap.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gtwfbolcsq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gtgoweqkoh.html

[S22] C：字符串转数字
来源：http://dali.xinyue.icu/Article/details/gtgpujwfdc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gtnwftdgmo.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gtvgbmtqfw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gtkzqnhdbi.html

[S24] C：获取本地时间
来源：http://dali.havefunace.top/Article/details/gtwnnqsjaw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gtfglwnhpx.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gttuwxuege.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gtvudezave.html

[S26] C：内存清零
来源：http://dali.zhengqikj.top/Article/details/gtehejmlaa.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gtedauzlmj.html

[S27] C：定义常量
来源：http://dali.shanyushiyangtech.top/Article/details/gthyaxwwfp.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gthelxxvmy.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gtbzvillqz.html

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gtfagtjfdg.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gtidmgjufp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gtwngfjywg.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gtpqrqokpj.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtavxxfgze.html

#define X_H
来源：http://dali.316326.xyz/Article/details/gtgxhyrxdg.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gtknvzhozz.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtuywlxdqe.html


<!-- 参考信息 -->