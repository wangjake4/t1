代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtxzjsnkpq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gtagpkqyzt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtibbgulam.html

[Q57] 行号
来源：http://dali.jqgfzy.top/Article/details/gtqmffzwvz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtyvdawohu.html

[Q58] 累计求和
来源：http://dali.birdmap.top/Article/details/gthpvllxwm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtgrjiwtnk.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gtmzzwqwqg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtorczkcrm.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gtdstizktx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hfpthk.cn/Article/details/gtatphnqbd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtbozxmmcf.html

[Q61] 移动平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtontbowzu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtzfryfpwj.html

[Q62] 分组占比
来源：http://dali.ppjwa.cn/Article/details/gtbhenpbbo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtnjxxmnjx.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gtdesvihsm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gttdviritn.html

[Q64] 提交事务
来源：http://dali.haohaochexian.top/Article/details/gthiidtwtj.html

COMMIT;
来源：http://dali.haohaochexian.top/Article/details/gtzzihexjg.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gteeevopmr.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gtnwitdqrv.html

[Q66] 行锁查询
来源：http://dali.sysykeji.top/Article/details/gtidildrqg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj202588.top/Article/details/gtcquadtar.html

[Q67] 设置隔离级别
来源：http://dali.tian-w.cn/Article/details/gtbbsjfjnv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinuflixw.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gtvogvfglq.html

SAVEPOINT sp1;
来源：http://dali.dashuyun.cn/Article/details/gtuehkjvgg.html

ROLLBACK TO sp1;
来源：http://dali.yvedp.cn/Article/details/gtflmpjzbh.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gtqizfnfkg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.snrcjt.cn/Article/details/gtpavqfoen.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gtvovhmaux.html

ANALYZE TABLE users;
来源：http://dali.gogol.net.cn/Article/details/gtwxcmmbpb.html

[Q71] 查看建表语句
来源：http://dali.xuetiantiany.cn/Article/details/gthfcvqjso.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gtrrvnbkjc.html

[Q72] 查看索引
来源：http://dali.xziqi.cn/Article/details/gtidaeymge.html

SHOW INDEX FROM users;
来源：http://dali.cashguo.top/Article/details/gttsxdqpzc.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gtoqduseic.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gtljgzxdup.html

[Q74] 强制使用索引
来源：http://dali.jianghu66.top/Article/details/gtbrpajkaw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hongshengwenyu.top/Article/details/gtvjwtvotr.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtoteuaqxt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtrqaockoq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwkqiuue.html

[Q76] 按天统计
来源：http://dali.ehwqpu.com/Article/details/gtxvulfgzr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gtbpalypik.html

[Q77] 时间加减
来源：http://dali.yuanzhike.top/Article/details/gtyrdyyswq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gtjrvkhrbe.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtjatdjktk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gtuwbhqmwg.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtuvxseese.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.vqdsnc.cn/Article/details/gtljhzljut.html

[Q80] 字符串截取
来源：http://dali.havefunace.top/Article/details/gtllwegtxa.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtlvnjsfui.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtqdszhciy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtxcffkttx.html

[Q82] 字符长度与字节长度
来源：http://dali.yj202588.top/Article/details/gtcrrizdfs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtrfjeeyhl.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtlllsrnbx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtspziagfq.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtntgniibl.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gthfbzelxg.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gtelsprpjr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenjidiqi.icu/Article/details/gtvzczersb.html

[Q86] 读取 JSON 字段
来源：http://dali.bjfxy.top/Article/details/gtevigjjwr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnckbfpzv.html

[Q87] JSON 字段做条件
来源：http://dali.zhengqikj.top/Article/details/gtkgbqpyky.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gtydrmzbgb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymfpvlxt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gttkdatznt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gttyanyuzd.html

[Q89] 判断表是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtnryyzufj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gtbxqzzjlz.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gtjjcdimld.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj202588.top/Article/details/gtxwmobbqa.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtaykdepmc.html

R. Bash 专题
来源：http://dali.ppjwa.cn/Article/details/gtywjotblv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmyjfejkb.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gtdsphzuda.html

#!/usr/bin/env bash
来源：http://dali.hnxiangtu.top/Article/details/gtylzpzwab.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyztdhmvp.html

[R02] 变量赋值与使用
来源：http://dali.yueranfly.top/Article/details/gtgvqnwojs.html

name="Tom"; echo "$name"
来源：http://dali.xinyue.icu/Article/details/gttjfpqofe.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gtonklobzp.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gtthxeuuoz.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gttqcqkajw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gogol.net.cn/Article/details/gtpgehcojg.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gtlsqqdqsw.html

name="${1:-default}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtncfxrahq.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gtnaiyxcmw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gtxutynnxy.html

[R07] if 判断文件
来源：http://dali.316326.xyz/Article/details/gthuleufnw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gttpajdtck.html

[R08] 数值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdbincdc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gtmtfrbnvb.html

[R09] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtmbjhrjwh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsczicag.html

[R10] 正则匹配
来源：http://dali.hnxiangtu.top/Article/details/gtqhvhjktp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gtcamgkpof.html

[R11] case 多分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwradbnu.html

case "$1" in
来源：http://dali.yongpay.top/Article/details/gtxukdyrwg.html

start) echo "启动" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtoxatxsdg.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gtqxymfvyb.html

*)     echo "未知命令" ;;
来源：http://dali.hysaishi.cn/Article/details/gtferaxrbt.html

esac
来源：http://dali.9152youxi.cn/Article/details/gtsqdixqnx.html

[R12] for 遍历文件
来源：http://dali.fengsongda.top/Article/details/gtkohaknqc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.kuanghao11.cn/Article/details/gtgcjgldve.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gtrchudkgs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtkslvgsxa.html

[R14] C 风格 for
来源：http://dali.ydzc1.top/Article/details/gtqxxzyhnw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtuvdgllvn.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtleefwmbt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gtbikdemnt.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gtvnvgfxio.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gtruwviofy.html

[R17] 数组定义与取值
来源：http://dali.zhoulong.xyz/Article/details/gtdqpqdvyr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtrajbxmdv.html

[R18] 遍历数组
来源：http://dali.yanxiufei.cn/Article/details/gtpiawnyqe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtteermpis.html

[R19] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtvyouzxnl.html

echo "${#arr[@]}"
来源：http://dali.sweek.top/Article/details/gtofzpjvme.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gtyrqzorln.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtxubuezyk.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gtdglasasy.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gtemdyseju.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtmaowlkrq.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gtijbirfgd.html

[R23] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtxtxdhcrx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gtortfbula.html

[R24] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtofwghdue.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtpqelnwhw.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gtpywnbfjn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjsjrrgv.html

[R26] 命令替换
来源：http://dali.gzhubu.top/Article/details/gtejtnxdyu.html

now=$(date +%F); echo "$now"
来源：http://dali.yj202588.top/Article/details/gtdokabnpt.html

[R27] 算术展开
来源：http://dali.quarkkingdee.top/Article/details/gtqemlccgm.html

echo $((1 + 2 * 3))
来源：http://dali.fengsongda.top/Article/details/gtvhpcxlgq.html

[R28] 浮点运算
来源：http://dali.ppjwa.cn/Article/details/gtmfvjlbym.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gtqbqaaems.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gtjitskizh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gtvnadinzx.html

[R30] 函数返回状态码
来源：http://dali.yuxming.cn/Article/details/gtkabwjjas.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sysykeji.top/Article/details/gtipsspewg.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gtgaqusdqv.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gtnguvlbwm.html

[R32] 参数个数校验
来源：http://dali.dashuyun.cn/Article/details/gtvdtnqpau.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtbckkujit.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gtvrbqztlc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gtveyrleli.html

[R34] 退出时清理
来源：http://dali.zhiwuduotai.top/Article/details/gtjfrcedjp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtbkemxahl.html

[R35] 后台执行并等待
来源：http://dali.nwbrower.top/Article/details/gtmsmulojl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.haohaochexian.top/Article/details/gtlnhvstgv.html

[R36] 并发执行多个任务
来源：http://dali.ivvv.top/Article/details/gtopykcxnf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cashguo.top/Article/details/gtrclpocdb.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gtkummgabp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gtcejdfmxv.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gtoyegfzka.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtusesqrjj.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrydprxc.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gtacddwvzt.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtrtmuaymv.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gtaafzdbbm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gtovlezqht.html

cmd >/dev/null 2>&1
来源：http://dali.yj202588.top/Article/details/gtwvavsrpx.html

[R42] 输入重定向
来源：http://dali.haohaochexian.top/Article/details/gtishgtliy.html

wc -l < a.txt
来源：http://dali.cheryme.top/Article/details/gtouwevvwf.html

[R43] 按名字查找文件
来源：http://dali.jqgufenzy.top/Article/details/gtwwlelucx.html

find . -name "*.log" -type f
来源：http://dali.yuxming.cn/Article/details/gtzjsxglyb.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gtrhibpldk.html

find . -mtime -7 -type f
来源：http://dali.nanxuanxn.top/Article/details/gtwpsatquf.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gtavlhbybo.html

find . -name "*.tmp" -delete
来源：http://dali.snrcjt.cn/Article/details/gtxfyvjvkp.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gtftjdvlam.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gtdjwakzrx.html

[R47] sed 单行替换
来源：http://dali.feifeiyinyue.top/Article/details/gtwmvcjaiu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtksqwfwsx.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gthtxfflkz.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtqartublq.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtadnclsif.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gttqkvxwyp.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdwzlpqn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtnkocqqvb.html

[R51] 排序去重取前几
来源：http://dali.zhiwuduotai.top/Article/details/gtrfvrkwjf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tanke756.top/Article/details/gtpjcpyvlf.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gtfudrkjua.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gtgrdhzmal.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gtttjbrsjv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gtstiisbzh.html

[R54] 比较两个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtyssydbtx.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gtwiqxhovx.html

[R55] 压缩与解压
来源：http://dali.xinyue.icu/Article/details/gtotryhfoo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.kuanghao11.cn/Article/details/gtajmkyoxj.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gtxyyatggu.html

scp file user@host:/path/
来源：http://dali.jinqigfzy.top/Article/details/gtsyxkxmkx.html

[R57] 远程执行命令
来源：http://dali.havefunace.top/Article/details/gtvjtodday.html

ssh user@host 'uptime'
来源：http://dali.aizwys.cn/Article/details/gtoskskgaw.html

[R58] 下载文件
来源：http://dali.chenzaomai.com/Article/details/gtwvumjbxl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtyredeynt.html

[R59] 发 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtsduoakkx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtczscdojk.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gthwnqduly.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pycfn.com/Article/details/gttqexlckr.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gtsjooiqog.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gtppunhcuj.html

[R62] 找最占空间的文件
来源：http://dali.bjfxy.top/Article/details/gtkgsgidzd.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gttlxfhpur.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gtptoouxhw.html

free -h;  ps aux | grep nginx
来源：http://dali.sysykeji.top/Article/details/gtpnklsihe.html

[R64] 结束进程
来源：http://dali.svipenyu.cn/Article/details/gtnbqjqelb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gtqkolbhkf.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gtpqirzhtg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.vqdsnc.cn/Article/details/gtisbpxrpj.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtxtgggeln.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gtfjuqmaeq.html

[R67] 生成随机十六进制串
来源：http://dali.zhixingplan.top/Article/details/gtmrjrsurq.html

openssl rand -hex 16
来源：http://dali.zhongyouzk.top/Article/details/gtrwntlijh.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gtkalmglrw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sysykeji.top/Article/details/gtnejmztcs.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gtzujuqvon.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gthcmvvzln.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gtfupynwwq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gtotuiuolr.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtnekjhrax.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ivvv.top/Article/details/gtxmnkbqaq.html

[R72] 等待端口就绪
来源：http://dali.cdnleiting.top/Article/details/gtzeybgtbb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtwsprjpcq.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gtmyzwthxj.html

split -l 1000 big.log part_
来源：http://dali.havefunace.top/Article/details/gtpqylfxzp.html

[R74] 批量重命名
来源：http://dali.jqgfzy.top/Article/details/gtmbcvnzen.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtprmmnlfu.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtlpmjdgiw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyaxnkrau.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gtvycwzthh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gtyxursomd.html

[R77] 读取用户输入
来源：http://dali.sufxvd.cn/Article/details/gtafzanpzi.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gteuogmref.html

[R78] 交互式菜单
来源：http://dali.kuanghao11.cn/Article/details/gtgaekjhsv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlnymyeb.html

[R79] 解析命令行选项
来源：http://dali.yueranfly.top/Article/details/gttjrdcato.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gtdbnmzyuh.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtsoobquyx.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gtaqduflad.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtjylvahmb.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gtmhaneycp.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtladcwdgd.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtwmcvykzw.html

#include <stdio.h>
来源：http://dali.cdnleiting.top/Article/details/gtckilkvcf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pycfn.com/Article/details/gtkoklejsf.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtsmnqtjcb.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigufen.top/Article/details/gtyrcmtlpj.html

[S03] C：读入整数
来源：http://dali.sxryk.cn/Article/details/gtsuchhxny.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gtjnflkzkh.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuouffwjn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gtboywnguw.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gtitftpohg.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gtlasvbpfm.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gtvxvgzxvb.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gtsnkjusyu.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gtokotcmci.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangshuangyany.cn/Article/details/gtwipaqltu.html

[S08] C：动态内存分配与释放
来源：http://dali.feifeiyinyue.top/Article/details/gtlkcchnup.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gtckluvjoe.html

[S09] C：结构体定义与初始化
来源：http://dali.smart0.xyz/Article/details/gtqscucxcw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtjobsmjps.html

[S10] C：指针与解引用
来源：http://dali.gaohongyu789.top/Article/details/gtwvyiixqe.html

int *p = &a;  *p = 5;
来源：http://dali.jqgufenzy.top/Article/details/gtadpwiiqw.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtpwqajfpa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtustvxwlb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtdwjcibpx.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtvaxsnqyd.html

[S12] C：写文件
来源：http://dali.hammf.cn/Article/details/gtoawdfkfl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtvceibrib.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gtsvowkllb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gtgmirjaks.html

[S14] C：枚举
来源：http://dali.tian-w.cn/Article/details/gtxpkhysty.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gtnrbwzlmb.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gtgidevbcs.html

(double) a / b
来源：http://dali.zhixingplan.top/Article/details/gtxbvndjmb.html

[S16] C：位操作置位
来源：http://dali.yj20258888.top/Article/details/gtvhsyjfwj.html

x |= (1 << 3);
来源：http://dali.yvedp.cn/Article/details/gtsjrptakx.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtxotdkdgp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.snrcjt.cn/Article/details/gtwqlzrrhv.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtuelrolwc.html

int main(int argc, char **argv)
来源：http://dali.meibo888.top/Article/details/gtvblpjtmv.html

[S19] C：快速排序
来源：http://dali.cucudq.cn/Article/details/gtnessxobv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtnvbkmyhu.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvoxlcix.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtyawsyjgj.html

[S21] C：字符类别判断
来源：http://dali.jianghu66.top/Article/details/gtfjxzeocd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gtzjupxlsj.html

[S22] C：字符串转数字
来源：http://dali.sweek.top/Article/details/gtotkifnqe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gtvqqtvjom.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gtqasostyr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtzidmsrid.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gtjxwsesuq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nwbrower.top/Article/details/gtspizezgw.html

[S25] C：内存拷贝
来源：http://dali.zhixingplan.top/Article/details/gtpwarzfhn.html

memcpy(dst, src, n);
来源：http://dali.kuanghao11.cn/Article/details/gtrzelwkqe.html

[S26] C：内存清零
来源：http://dali.xylfe.cn/Article/details/gtnxcarrsb.html


<!-- 参考信息 -->