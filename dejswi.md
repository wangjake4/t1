代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtezsxwhqp.html

[Q60] 取上一行 / 下一行
来源：http://dali.tian-w.cn/Article/details/gtwusfemhs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gtivqlqhyi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtqvemfqki.html

[Q61] 移动平均
来源：http://dali.pycfn.com/Article/details/gtknnsmlvq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtyfskwkqo.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gtjqgtzrwi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtqjlfausk.html

[Q63] 开启事务
来源：http://dali.zycfv.cn/Article/details/gtvfjenvoc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gtwqlhetbz.html

[Q64] 提交事务
来源：http://dali.daria6918.cn/Article/details/gtzymnqdde.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gtfleeluwl.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gtgygngrju.html

ROLLBACK;
来源：http://dali.tian-w.cn/Article/details/gtpawqxwre.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gtyyoefklr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.0kj1m.cn/Article/details/gtvnhevggk.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gttfabjuzj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gtyfdyimbc.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gtdvlhtrbb.html

SAVEPOINT sp1;
来源：http://dali.mhx1999.top/Article/details/gttmlerxvz.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gtgvgwfpls.html

[Q69] 查看执行计划
来源：http://dali.cdnleiting.top/Article/details/gtcrwyjjmv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gtatiuhwzq.html

[Q70] 更新统计信息
来源：http://dali.mhx1999.top/Article/details/gtzxzjydkg.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gtxjaceovo.html

[Q71] 查看建表语句
来源：http://dali.yvedp.cn/Article/details/gthpomxusv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gtzpwyqkoi.html

[Q72] 查看索引
来源：http://dali.yj202588.top/Article/details/gtpftszipt.html

SHOW INDEX FROM users;
来源：http://dali.sxryk.cn/Article/details/gtzctedabq.html

[Q73] 查看表状态
来源：http://dali.xinyue.icu/Article/details/gtvvinasex.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gtthwydacs.html

[Q74] 强制使用索引
来源：http://dali.hnxiangtu.top/Article/details/gtjzehbxig.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gtqanzcvwc.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gtsihkeucj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtbirsnvog.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ydzc1.top/Article/details/gtwpprqpeb.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gtqhakifzu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yonumen.top/Article/details/gtjsqfmsdb.html

[Q77] 时间加减
来源：http://dali.hongshengwenyu.top/Article/details/gtmnxshckc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gtdqervohi.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gtllqtsejy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sysykeji.top/Article/details/gtdxzlwksb.html

[Q79] 字符串拼接
来源：http://dali.yuxming.cn/Article/details/gtosikxglz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangshuangyany.cn/Article/details/gtdonadpaf.html

[Q80] 字符串截取
来源：http://dali.tian-w.cn/Article/details/gtduuapljt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ivvv.top/Article/details/gtsgmrspme.html

[Q81] 字符串替换
来源：http://dali.birdmap.top/Article/details/gthnbamwhn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.c1oappe.top/Article/details/gtdyrycyiu.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gtedhbcboq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtsultmdre.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtrwwoucuj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkwakoru.html

[Q84] 去除首尾空格
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjihxsunz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtnfpqgkju.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gtsfubupgc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gtygwvarnc.html

[Q86] 读取 JSON 字段
来源：http://dali.haohaochexian.top/Article/details/gtgbekvtqs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nwbrower.top/Article/details/gtqgomenpc.html

[Q87] JSON 字段做条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzqjdfnb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gtadnwpoud.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gtvitdrlqz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gtsgjwbprl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gttixrsilg.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gtpccrplwd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.havefunace.top/Article/details/gtpcpwuszh.html

[Q90] 生成序号列
来源：http://dali.tian-w.cn/Article/details/gtxfgtofyu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gtydxeswqf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtsuynjesi.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gtvpaoiofl.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdfjisrga.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gtxvfxypkv.html

#!/usr/bin/env bash
来源：http://dali.nwbrower.top/Article/details/gtctxqakoi.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gtobrmnbjh.html

[R02] 变量赋值与使用
来源：http://dali.zhoulong.xyz/Article/details/gtexhjmkzl.html

name="Tom"; echo "$name"
来源：http://dali.yuanzhike.top/Article/details/gtaamkowqc.html

[R03] 只读变量
来源：http://dali.zhiwuduotai.top/Article/details/gteyuxmhfa.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gtkrwubkdm.html

[R04] 位置参数
来源：http://dali.redwolf501.top/Article/details/gtvdxuiejp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ydzc1.top/Article/details/gteoecbfdy.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gtojocdgtn.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtomkwzyrb.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gtvtfozndi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gtooghwvnc.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gtipkawnqr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gtfccbvxhz.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gtrlhfehcc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gtcosktdwz.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtitwpzudq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gtdvxabwsh.html

[R10] 正则匹配
来源：http://dali.ivvv.top/Article/details/gtaadbsles.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tanke756.top/Article/details/gtsxxovocu.html

[R11] case 多分支
来源：http://dali.feifeiyinyue.top/Article/details/gtxdluczmu.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gttcjaqzrd.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gtxfonnnpr.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gtqqiuzups.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtogeehjqh.html

esac
来源：http://dali.aizwys.cn/Article/details/gtsbmnllcq.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gtjidmjanh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.316326.xyz/Article/details/gtbngugakq.html

[R13] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gtkycbhqxu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtagqdyigy.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gtdbiqnaua.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtlpbpuvhb.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtqqfwtafx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gtqdfxtvnb.html

[R16] until 等待条件
来源：http://dali.zycfv.cn/Article/details/gtorqexrfd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtysifjskj.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gtztzbbewb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gthrxkzzeq.html

[R18] 遍历数组
来源：http://dali.daxiang520.top/Article/details/gtcbmtywyf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jyoumei.cn/Article/details/gtiqlmldbf.html

[R19] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtpkrzyssb.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gtzxwywktl.html

[R20] 关联数组（字典）
来源：http://dali.chenlongwang.top/Article/details/gtkdnfzscu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gtrcnurmhu.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtsteydmhc.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gtgrhvdxzx.html

[R22] 截取子串
来源：http://dali.hnqzz.top/Article/details/gthphjusew.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gtkaycyzie.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtckjijqpl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtbpuilwuk.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtoafrjxzb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gtkjicdvtz.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gtyrfgviop.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gtvszevxjy.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtfuzruqoq.html

now=$(date +%F); echo "$now"
来源：http://dali.shuidangran.top/Article/details/gtnccfrprl.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gtiucptpai.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gtisjwhkks.html

[R28] 浮点运算
来源：http://dali.zhengqikj.top/Article/details/gtgmymzzbp.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gtyeemypap.html

[R29] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtxbunjyvf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gttfojyqvq.html

[R30] 函数返回状态码
来源：http://dali.chenzaomai.com/Article/details/gtzkunhugj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gteomhmnnb.html

[R31] 局部变量
来源：http://dali.gotoacloud.top/Article/details/gthdxpceye.html

f() { local x=1; echo "$x"; }
来源：http://dali.xinyue.icu/Article/details/gtiwlripbf.html

[R32] 参数个数校验
来源：http://dali.nanxuanxn.top/Article/details/gtvrlbgicx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtvtuvsyfa.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gtqprxajyu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangtech.top/Article/details/gtinnyuico.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gtxkcuhkkj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtmrjgizyd.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gtlqoxspyq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jianghu66.top/Article/details/gtgknuqdcz.html

[R36] 并发执行多个任务
来源：http://dali.hongshengwenyu.top/Article/details/gtemhafqkj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangshuangyany.cn/Article/details/gtlcxvzgmd.html

[R37] 把输出赋给变量
来源：http://dali.nanxuanxn.top/Article/details/gtcgdrrdai.html

files=$(ls -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtofjxdopz.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gtsgqkwues.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gtgwbkhuhq.html

[R39] 重定向标准输出与错误
来源：http://dali.pycfn.com/Article/details/gtptmnjcdz.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gtgaedebtv.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gtnqbjqwia.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gtraehpqpp.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gtjhrgzoom.html

cmd >/dev/null 2>&1
来源：http://dali.fzhhl.top/Article/details/gtnkbahqhz.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gtuabohkqd.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gteywoezdv.html

[R43] 按名字查找文件
来源：http://dali.pengpengdd.cyou/Article/details/gtipyijyep.html

find . -name "*.log" -type f
来源：http://dali.yueranfly.top/Article/details/gttdkdnybz.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gtceulggwq.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gtspydsooo.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gtbvkpyxyb.html

find . -name "*.tmp" -delete
来源：http://dali.hnqzz.top/Article/details/gtewqxvzhh.html

[R46] 递归替换文件内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuocglnv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gtsmfqbzez.html

[R47] sed 单行替换
来源：http://dali.cheryme.top/Article/details/gtwrdhubdt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtdkfuotdl.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gtymcrwufo.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtviuvjjld.html

[R49] awk 带条件
来源：http://dali.yj202588.top/Article/details/gtsdygxftq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sweek.top/Article/details/gtgsastezv.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gtzlgldycu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtvdudzyed.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gtderuftpg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhongyouzk.top/Article/details/gtppfersca.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gtgtcjoqwb.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtxguzwjfy.html

[R53] 查看文件头与实时尾
来源：http://dali.daria6918.cn/Article/details/gtkghmddif.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pycfn.com/Article/details/gtrlxwhjvg.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gtailcacig.html

diff a.txt b.txt
来源：http://dali.hywenlv.cn/Article/details/gtnmashplj.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabknafjn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gtrvuvuzdh.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtypdwfnwz.html

scp file user@host:/path/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiiqhoxji.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gtdvpytyfa.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gtthwypfwo.html

[R58] 下载文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbljcyao.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gtlsewynss.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtgkmdbmsw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gtwgtnxmyw.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrolwunyp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pycfn.com/Article/details/gtyyjglbib.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gtkrorwkfg.html

df -h;  du -sh *
来源：http://dali.sysykeji.top/Article/details/gtiwbyylrd.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gtwcqtooar.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gtpovpjsyg.html

[R63] 内存与进程
来源：http://dali.yongpay.top/Article/details/gthdzyjaqr.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gtccdghjuc.html

[R64] 结束进程
来源：http://dali.jiagoushi.top/Article/details/gtojezcykl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gthfrscxsd.html

[R65] 查看端口占用
来源：http://dali.hysaishi.cn/Article/details/gtcwqlcobk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gtqjxnwipg.html

[R66] 定时任务
来源：http://dali.jiagoushi.top/Article/details/gtqjxyhjxt.html

crontab -e;  crontab -l
来源：http://dali.andypj.xyz/Article/details/gtpcusxywu.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gtdwcvsrvw.html

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gtbsbanjpp.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtzszgfcwg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtqzzounhz.html

[R69] 生成随机密码
来源：http://dali.jiagoushi.top/Article/details/gtjryvivhu.html

head -c 16 /dev/urandom | base64
来源：http://dali.iojbl.cn/Article/details/gtzbcehzvi.html

[R70] 时间戳与互转
来源：http://dali.jinqigufen.top/Article/details/gtsdugsbdq.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtqvoncxzn.html

[R71] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtpznktifc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gtruggexzl.html

[R72] 等待端口就绪
来源：http://dali.hongshengwenyu.top/Article/details/gtlyrfdaih.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtymlwcsfz.html

[R73] 分割大日志
来源：http://dali.shzxlz.cn/Article/details/gtmwjdjjav.html

split -l 1000 big.log part_
来源：http://dali.zycfv.cn/Article/details/gtudnnznmf.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gthxyseegg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gtekldhxnz.html

[R75] 导出环境变量
来源：http://dali.yvedp.cn/Article/details/gtfvxjtheq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gtqblrrpcv.html

[R76] 使用临时文件
来源：http://dali.kuanghao11.cn/Article/details/gttjzererr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtazkbwmet.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gtpvfnxkvs.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gtdpumshzr.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvqditmh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yongpay.top/Article/details/gtolecvyhs.html

[R79] 解析命令行选项
来源：http://dali.yuanzhike.top/Article/details/gtxzdawgyr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gtqrvplpsw.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gtqbfyauju.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gtuggashph.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtsawzluyg.html

S. C / C++ 专题
来源：http://dali.jinqigfzy.top/Article/details/gtxcllomql.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtnruoqesm.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtpwygaysz.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gtkfcwtoyc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtazufrwgh.html

[S02] C：变量与格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtvluatwzk.html

int a = 10; printf("%d\n", a);
来源：http://dali.ivvv.top/Article/details/gtalchfabk.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gtduqtwwyt.html

int x; scanf("%d", &x);
来源：http://dali.jiagoushi.top/Article/details/gtsppyxbqr.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gtvgoctxtm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtpmbnhxrn.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gthaemvmcj.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gtpwuwhjfv.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gtrnpzdzzg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gtmpmhkyvx.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gttkhfcsjy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gttstnpvzp.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gtjsdrmigj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gtiirpedgv.html

[S09] C：结构体定义与初始化
来源：http://dali.svipenyu.cn/Article/details/gtlofersqc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gtvcjzgaex.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gthrxhkypm.html

int *p = &a;  *p = 5;
来源：http://dali.hnqzz.top/Article/details/gtopqajvar.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtiiqdgyjn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.c1oappe.top/Article/details/gtrewnkubg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtfwvavcca.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtmhdprmuy.html

[S12] C：写文件
来源：http://dali.ydzc1.top/Article/details/gtdkdpqurg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.birdmap.top/Article/details/gtjilmjzhe.html

[S13] C：宏定义
来源：http://dali.cucudq.cn/Article/details/gtmcxrkrep.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gtgqslyjpw.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtyglvavab.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenzaomai.com/Article/details/gtkxjsfrck.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gtnxbftnyc.html

(double) a / b
来源：http://dali.dashuyun.cn/Article/details/gtgandnrjc.html

[S16] C：位操作置位
来源：http://dali.sufxvd.cn/Article/details/gtzleorohw.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gtzavmdjvj.html

[S17] C：安全拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtrydbacgj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnqzz.top/Article/details/gtxikgvzse.html

[S18] C：命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtwcgztcae.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gtldphinbl.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gtfudayygf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtzvtdwcgt.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gtktjvuvay.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gturmrcdcf.html

[S21] C：字符类别判断
来源：http://dali.ehwqpu.com/Article/details/gtertsydkz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tianlin.xyz/Article/details/gtjeyiquuk.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtravoarcx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtfxnxtour.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gtsgbrohty.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxuanxn.top/Article/details/gtofbkrqcx.html

[S24] C：获取本地时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonxvqdtk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daria6918.cn/Article/details/gtmtzyqfcq.html

[S25] C：内存拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdzoumub.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gtnxsejzxr.html

[S26] C：内存清零
来源：http://dali.316326.xyz/Article/details/gtezwpkktf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gtgrntssqh.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gtkewkqbgr.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtmdrfjkab.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrndawye.html

static int counter = 0;
来源：http://dali.yvedp.cn/Article/details/gtgccrcgez.html

[S29] C：变参函数
来源：http://dali.316326.xyz/Article/details/gtabthvopg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgufenzy.top/Article/details/gtjkwekqgo.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gtgbytfssn.html


<!-- 参考信息 -->