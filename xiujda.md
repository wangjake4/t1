代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yonumen.top/Article/details/gttsoxioag.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmcsyqqe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtoyjdgsbu.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gtxugjmwxq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.c1oappe.top/Article/details/gtmwuyokrx.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqsxkldw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtwpabuvxt.html

[Q59] 分组内累计
来源：http://dali.xinyue.icu/Article/details/gtybyuhvsx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtpcjpaoch.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258888.top/Article/details/gtomhqsngb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gtdlarqczh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtiemtkhmu.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gtjnlnardh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtzsxfgufc.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gtthoqqnok.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtnpexaipd.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrskxmdk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gzhubu.top/Article/details/gtwepauvpg.html

[Q64] 提交事务
来源：http://dali.xuanzx.com/Article/details/gtmpmfnqkc.html

COMMIT;
来源：http://dali.tanke756.top/Article/details/gtzsvtyfdi.html

[Q65] 回滚事务
来源：http://dali.gaohongyu789.top/Article/details/gtqsmxstfd.html

ROLLBACK;
来源：http://dali.vqdsnc.cn/Article/details/gtfjweqwwm.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gtngkwfydh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gtwnqlelyn.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gtdlgmqjte.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuetiantiany.cn/Article/details/gtvjodzfwa.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gtsveqzltc.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gttzyxnbmz.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gtqfovoyim.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gtutacoytl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gtiqxwimnt.html

[Q70] 更新统计信息
来源：http://dali.zhongyouzk.top/Article/details/gtcwfrnlac.html

ANALYZE TABLE users;
来源：http://dali.nwbrower.top/Article/details/gtloiqvwqu.html

[Q71] 查看建表语句
来源：http://dali.redwolf501.top/Article/details/gtutovecft.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gtmtelzzgt.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gtreelrxgw.html

SHOW INDEX FROM users;
来源：http://dali.redwolf501.top/Article/details/gtwdtelcpt.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gtejpeolke.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtbjcwgduu.html

[Q74] 强制使用索引
来源：http://dali.zhiwuduotai.top/Article/details/gtwzvykrsz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gtydjwlnsd.html

[Q75] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtrxhxomyt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixhgyuhn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gtgrvvbyhp.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gtwreweoyu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gtnrmzcibr.html

[Q77] 时间加减
来源：http://dali.xinyue.icu/Article/details/gtwupjeebp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yangfankeji.com/Article/details/gtyrqstpek.html

[Q78] 当前时间
来源：http://dali.smart0.xyz/Article/details/gthavgropa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gtnluylaqt.html

[Q79] 字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtvyshxaxh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gtrgiqbbjp.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gtwljcyhhp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtxltlngah.html

[Q81] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gtsotkvjdi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.iojbl.cn/Article/details/gthtznlegi.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gtmucbswtu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtgdopafbh.html

[Q83] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtmldwekgn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipndefon.html

[Q84] 去除首尾空格
来源：http://dali.zhixingplan.top/Article/details/gtkfqjboyj.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtjekhqtvp.html

[Q85] 数值取整
来源：http://dali.zhixingplan.top/Article/details/gtdlyeoehk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gtjiclycox.html

[Q86] 读取 JSON 字段
来源：http://dali.andypj.xyz/Article/details/gtfrkelaoi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jlsjyb.cn/Article/details/gtivpfoclz.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gtorudhpsa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.haohaochexian.top/Article/details/gtmigomgez.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gtcpivvumi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fzhhl.top/Article/details/gtvuwdkarf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gtqkbjahfq.html

[Q89] 判断表是否存在
来源：http://dali.hfpthk.cn/Article/details/gtyrlxxphr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shzxlz.cn/Article/details/gtncfjxhsc.html

[Q90] 生成序号列
来源：http://dali.pycfn.com/Article/details/gtpnromrig.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gtdbbvcmfl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtabbfjwdz.html

R. Bash 专题
来源：http://dali.yvedp.cn/Article/details/gtpvnfedgo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtoeucwtgf.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gtewhzoaux.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gtbrvfinxj.html

set -euo pipefail
来源：http://dali.gogol.net.cn/Article/details/gtjjsddslh.html

[R02] 变量赋值与使用
来源：http://dali.nwbrower.top/Article/details/gtcmgzpvxu.html

name="Tom"; echo "$name"
来源：http://dali.nanxinkj.top/Article/details/gtpwsstxos.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gtefnmhiiu.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtdfrpmsam.html

[R04] 位置参数
来源：http://dali.gotoacloud.top/Article/details/gtctnuooyg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cheryme.top/Article/details/gtzslurwrk.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gtuovznlgc.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gttbhinsfq.html

[R06] 判断命令是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtcosyvndi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gtqufwmkwm.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzqgwtab.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258.top/Article/details/gtnktwevpe.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gtvmergdzm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xziqi.cn/Article/details/gttlkvdtxu.html

[R09] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gtorjlumfr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gtoolbmrwh.html

[R10] 正则匹配
来源：http://dali.zhengqikj.top/Article/details/gturgjeepo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aibaodan.cn/Article/details/gtmxbfmmlm.html

[R11] case 多分支
来源：http://dali.ehwqpu.com/Article/details/gtrbpvcjgl.html

case "$1" in
来源：http://dali.cheryme.top/Article/details/gtbxmdkstw.html

start) echo "启动" ;;
来源：http://dali.316326.xyz/Article/details/gtrftccmas.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtiygfeffn.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gtajwowufv.html

esac
来源：http://dali.andypj.xyz/Article/details/gtxrhhpzqu.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gtqiowqzws.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqobleud.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gtsfgwxuhh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gthratrkko.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gtvszpcjji.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtyelgzdtc.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gthwchmcwj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gtaehbyvye.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoymkvuga.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtyvtydsmy.html

[R17] 数组定义与取值
来源：http://dali.xylfe.cn/Article/details/gtdfxdxbxs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gtygtzdaee.html

[R18] 遍历数组
来源：http://dali.daria6918.cn/Article/details/gtldvyeiyn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gtrgeayanb.html

[R19] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtilzolzqp.html

echo "${#arr[@]}"
来源：http://dali.iojbl.cn/Article/details/gtctjxegls.html

[R20] 关联数组（字典）
来源：http://dali.chenjidiqi.icu/Article/details/gtaspfxvbo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gthoxsuwct.html

[R21] 字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtfbnppvzf.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gtyscgkukt.html

[R22] 截取子串
来源：http://dali.fengsongda.top/Article/details/gtqbyjagfs.html

echo "${s:0:5}"
来源：http://dali.ehwqpu.com/Article/details/gtyutklhvu.html

[R23] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gthvfqyryk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gtjmxbbfzf.html

[R24] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtkudonjvv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hongshengwenyu.top/Article/details/gttunmcbsu.html

[R25] 去后缀 / 去前缀
来源：http://dali.gotoacloud.top/Article/details/gtzqgzpcls.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gtcrfiuzsv.html

[R26] 命令替换
来源：http://dali.bjfxy.top/Article/details/gtewzdqtgg.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gtbmatfoqt.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gtufhmvziv.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gtfumsmxnb.html

[R28] 浮点运算
来源：http://dali.xziqi.cn/Article/details/gtwmcorpow.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gtcuijycrx.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtettwtuwd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gtefvvghom.html

[R30] 函数返回状态码
来源：http://dali.jqgfzy.top/Article/details/gtvuvgzuix.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gtovuhxxoc.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gtxketabbi.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gtvnqynrki.html

[R32] 参数个数校验
来源：http://dali.shangyingyoupin.top/Article/details/gtfhavlmre.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gthnobrbnf.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gtuzqafxpg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtcrppakur.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gtlvficsbl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtbnpfwohq.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gtqdnwokdo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhixingplan.top/Article/details/gtacfdysyl.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gtekjewpec.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pengpengdd.cyou/Article/details/gtefnnexke.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gtssajvmph.html

files=$(ls -1)
来源：http://dali.ydzc1.top/Article/details/gtqbjsgyuo.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gtgytxbojd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gtuspcfpom.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gtzgwwczoq.html

cmd > out.log 2>&1
来源：http://dali.cucudq.cn/Article/details/gtrgzwjyth.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gtusrxbajt.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gtjnuwzuge.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gtzajjlaed.html

cmd >/dev/null 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtzyxhpxxm.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gtbnwzhksk.html

wc -l < a.txt
来源：http://dali.chenlongwang.top/Article/details/gtbxrjnnfk.html

[R43] 按名字查找文件
来源：http://dali.yonumen.top/Article/details/gtwgxvluig.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gtbtunsarq.html

[R44] 按修改时间查找
来源：http://dali.yj202588.top/Article/details/gtsgjbjuom.html

find . -mtime -7 -type f
来源：http://dali.redwolf501.top/Article/details/gtqwhphifv.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gtooyznvnb.html

find . -name "*.tmp" -delete
来源：http://dali.wangdashe.top/Article/details/gtgwkrnxer.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gtbcfugfqb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cheryme.top/Article/details/gtleqisvbi.html

[R47] sed 单行替换
来源：http://dali.jiagoushi.top/Article/details/gttrplhipw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtxxrrtcxj.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtsvgxxnfw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtvnbwwlhf.html

[R49] awk 带条件
来源：http://dali.nanxinkj.top/Article/details/gtmbarkrdo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hywenlv.cn/Article/details/gtxcifzlrn.html

[R50] awk 求和
来源：http://dali.gzhubu.top/Article/details/gtziygyrst.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtgkeyjygt.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gtvbxhrfdm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cashguo.top/Article/details/gtwmfppgkm.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gtmrvyexdc.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gtrdjtqjkb.html

[R53] 查看文件头与实时尾
来源：http://dali.ybcxt.top/Article/details/gtrvpwnfhf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gtsbjtodgm.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gtyxpnxetk.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gteuygufsv.html

[R55] 压缩与解压
来源：http://dali.ydzc1.top/Article/details/gttuemndne.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtdejnsvgx.html

[R56] 远程拷贝
来源：http://dali.zhengqikj.top/Article/details/gtxnekdtku.html

scp file user@host:/path/
来源：http://dali.cashguo.top/Article/details/gtctgfrvah.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gtmqobcrte.html

ssh user@host 'uptime'
来源：http://dali.yj202588.top/Article/details/gtbiovkakd.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gtqdryyykj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ppjwa.cn/Article/details/gtxxvwvgia.html

[R59] 发 POST JSON
来源：http://dali.yj20258.top/Article/details/gtqriirjxn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj202588.top/Article/details/gtacimhmzs.html

[R60] 只看 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtibbdbncy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gtbvnjvpyk.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gtzjbztzsq.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gteckwmfsj.html

[R62] 找最占空间的文件
来源：http://dali.yj20258.top/Article/details/gtnsifizwq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gtodlafvik.html

[R63] 内存与进程
来源：http://dali.yueranfly.top/Article/details/gtinmifmgt.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gtwlrrrmyx.html

[R64] 结束进程
来源：http://dali.yuanzhike.top/Article/details/gtiyimafaz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gtnjtrpeag.html

[R65] 查看端口占用
来源：http://dali.shangyingyoupin.top/Article/details/gtkwqagbvo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yongpay.top/Article/details/gtjlaqfrva.html

[R66] 定时任务
来源：http://dali.jianghu66.top/Article/details/gtwjiymoex.html

crontab -e;  crontab -l
来源：http://dali.redwolf501.top/Article/details/gtgfwsilza.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gtkeljbhke.html

openssl rand -hex 16
来源：http://dali.ybcxt.top/Article/details/gtsmeefmfa.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gtjikizebj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cdnleiting.top/Article/details/gtgctjvywk.html

[R69] 生成随机密码
来源：http://dali.316326.xyz/Article/details/gtktfsucyv.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gtsdlofuji.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gtvvyvzbfh.html

date +%s;  date -d @1700000000
来源：http://dali.tanke756.top/Article/details/gtjzzplsac.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gthbzhhklk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gtcgxvmbrn.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gtpekldwvj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gthdypfqso.html

[R73] 分割大日志
来源：http://dali.havefunace.top/Article/details/gtwkkdonxf.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gtnepzqozq.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gtgbvpmjxr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tanke756.top/Article/details/gtoskabffx.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtafjkwkrs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ydzc1.top/Article/details/gtnlzxumfp.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gtmyanswvd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvnrlzfm.html

[R77] 读取用户输入
来源：http://dali.yanxiufei.cn/Article/details/gtvjgkyotc.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtmuaamkww.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gtbmjdowsr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gtymfrdkjr.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gtdwebzonp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gthmdtswcr.html

[R80] 查看脚本执行耗时
来源：http://dali.redwolf501.top/Article/details/gtvjvfpmjq.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gtltlkewvv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtylyxsttn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gtlansvnhr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtwvjuochr.html

[S01] C：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtscgkpqsv.html

#include <stdio.h>
来源：http://dali.tanke756.top/Article/details/gtbfhjytli.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.316326.xyz/Article/details/gtxreinrth.html

[S02] C：变量与格式化输出
来源：http://dali.cheryme.top/Article/details/gtqopcrsca.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gtiihkagfa.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbftekvyi.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gtagehjspk.html

[S04] C：字符串复制
来源：http://dali.chenzaomai.com/Article/details/gtvbwabhbh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xylfe.cn/Article/details/gtcmcfxmfo.html

[S05] C：字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtbgvztemv.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gttgtgnxwp.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gteiydwzta.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gthkboxjtt.html

[S07] C：数组遍历求和
来源：http://dali.chenjidiqi.icu/Article/details/gtzppntcdw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pycfn.com/Article/details/gtaojycnrq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gtlcryyxhp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gtjidkpwlr.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtsjnjnfgy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shangyingyoupin.top/Article/details/gtnauykzxs.html

[S10] C：指针与解引用
来源：http://dali.andypj.xyz/Article/details/gthlfkjzps.html

int *p = &a;  *p = 5;
来源：http://dali.daxiang520.top/Article/details/gtndzfubsv.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtvoqexsvi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gtsjflxahr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gtfwgowdbo.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtykhhxfqf.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmwymjff.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtfseyviec.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gtqfsvrdab.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gtuyhckbll.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gtkfoaiyyo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxinkj.top/Article/details/gtsxrjllhb.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gtzdcmvdly.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gtreqgudph.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gtjuzkkyhd.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gtvmhlfzlo.html

[S17] C：安全拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtdcmmjdif.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gtvguzxtvt.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gttijiizjt.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gtzpvaumpm.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtzbznnjmq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtvfrnzhwr.html

[S20] C：二分查找
来源：http://dali.chenlongwang.top/Article/details/gtysupdwpm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gteyrskzth.html

[S21] C：字符类别判断
来源：http://dali.jianghu66.top/Article/details/gtviewyptd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sufxvd.cn/Article/details/gtywfkllma.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gtriumjhgl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gtqthwzuan.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gtnfdcbufp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gtlpbauodz.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gtsexgyuwc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gtrpnrwnoq.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtbpcrmfbr.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gtweuhuxrr.html

[S26] C：内存清零
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlorlwltv.html


<!-- 参考信息 -->