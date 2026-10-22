代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtpkqvlrdc.html

[Q50] 批量更新
来源：http://dali.jianghu66.top/Article/details/gtphdfzxam.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gtvalqsvgv.html

[Q51] 用子查询更新
来源：http://dali.sysykeji.top/Article/details/gtzbmwksan.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gtewanvktp.html

[Q52] 删除指定行
来源：http://dali.hfpthk.cn/Article/details/gtyqnjqkbz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtontzuggx.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gtbibcfita.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtfavtidhd.html

[Q54] 清空表
来源：http://dali.cqqwz.cn/Article/details/gtnmpvjfph.html

TRUNCATE TABLE logs;
来源：http://dali.jlsjyb.cn/Article/details/gtdtafjtfu.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gtdyblgase.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fzhhl.top/Article/details/gtnevqyugw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxuanxn.top/Article/details/gtbvrtctet.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtkhaobvfs.html

[Q57] 行号
来源：http://dali.sysykeji.top/Article/details/gtrsykgkxt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gtltfvddme.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gtgvnlhipz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtskibvdbj.html

[Q59] 分组内累计
来源：http://dali.yj20258.top/Article/details/gtkfphihrl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtltvgepoy.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gtyyrhykvu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aizwys.cn/Article/details/gtqmkrachs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.316326.xyz/Article/details/gtjatxrwcz.html

[Q61] 移动平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlgsaybe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtwizsonoz.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gtejhgbqec.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtnbfhsake.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gtvxrwxega.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sufxvd.cn/Article/details/gtljmepkog.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gtomajjufe.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gtjiypwntk.html

[Q65] 回滚事务
来源：http://dali.fengsongda.top/Article/details/gttiljdfzf.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gtocfgqzos.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gtnfplaacd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shzxlz.cn/Article/details/gtfocsptxz.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gtwerqacti.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gtthdinfus.html

[Q68] 保存点
来源：http://dali.zhengqikj.top/Article/details/gttcanzfqe.html

SAVEPOINT sp1;
来源：http://dali.ivvv.top/Article/details/gtdpjhfdzv.html

ROLLBACK TO sp1;
来源：http://dali.chenlongwang.top/Article/details/gtylqshdus.html

[Q69] 查看执行计划
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlybphef.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gtezpfzxok.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gtarswqwol.html

ANALYZE TABLE users;
来源：http://dali.gaohongyu789.top/Article/details/gttckacecd.html

[Q71] 查看建表语句
来源：http://dali.cdnleiting.top/Article/details/gtmxgnxegu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.feifeiyinyue.top/Article/details/gtylvjoffh.html

[Q72] 查看索引
来源：http://dali.ybcxt.top/Article/details/gtinypuieq.html

SHOW INDEX FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtabhwqwpp.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gtopdzgbgp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.mhx1999.top/Article/details/gtokjlkcde.html

[Q74] 强制使用索引
来源：http://dali.gogol.net.cn/Article/details/gttxctrcaz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gtraxadfzd.html

[Q75] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gtugmvdufx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtfucvudib.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gtyipgllnr.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gtifbcyxkq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuekulxg.html

[Q77] 时间加减
来源：http://dali.yj20258888.top/Article/details/gtqjctoodu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gtrtqghcqn.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gteyopsjyt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.mhx1999.top/Article/details/gtnddlahpz.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtcmeaedah.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.bjfxy.top/Article/details/gtmubomcpm.html

[Q80] 字符串截取
来源：http://dali.quarkkingdee.top/Article/details/gtcgrufefz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtgjatxrla.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtnjzsntzq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtkthdagvp.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gthjljnjfe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtcpllhpgc.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtvbwvgrzd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtpusvroqq.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gthfsvgbxq.html

SELECT TRIM(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtufdfvonq.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gtcrcalghx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guannengcc.top/Article/details/gthbnrhxik.html

[Q86] 读取 JSON 字段
来源：http://dali.yuanzhike.top/Article/details/gtjfydxxph.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.havefunace.top/Article/details/gtvqqyqqhp.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gtvtmgqmmv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.haohaochexian.top/Article/details/gtkiddxiop.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtykefkdff.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gttapjfzay.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtwonyilry.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gtitfcpoba.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnqzz.top/Article/details/gtguyxegsx.html

[Q90] 生成序号列
来源：http://dali.ehwqpu.com/Article/details/gtekauulci.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtryoxyjef.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzgvychhg.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtzfixeqog.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttyooopnm.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtevujiwpm.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gtyuopgmlq.html

set -euo pipefail
来源：http://dali.316326.xyz/Article/details/gtegihepoh.html

[R02] 变量赋值与使用
来源：http://dali.haohaochexian.top/Article/details/gtgzlefqnn.html

name="Tom"; echo "$name"
来源：http://dali.ybcxt.top/Article/details/gtrvjxaolj.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gtafexfqvy.html

readonly PI=3.14
来源：http://dali.hywenlv.cn/Article/details/gtqynjsdqp.html

[R04] 位置参数
来源：http://dali.hammf.cn/Article/details/gtwxfpkstt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gtqsxxgswq.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gtzixjnzth.html

name="${1:-default}"
来源：http://dali.cucudq.cn/Article/details/gtwpzffghm.html

[R06] 判断命令是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtousmiqhh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtminxhgmv.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gtofnbumxj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtwrxmgfaa.html

[R08] 数值比较
来源：http://dali.cdnleiting.top/Article/details/gtmnodrgxn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gtaujssrig.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtgypmfuoz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.c1oappe.top/Article/details/gtlfxqjafz.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gtddwldcnc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gtrxvlllvg.html

[R11] case 多分支
来源：http://dali.jyoumei.cn/Article/details/gtofhhepct.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gtfdvvvdrx.html

start) echo "启动" ;;
来源：http://dali.sufxvd.cn/Article/details/gtoxucnpbd.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gtnyakmjuu.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gtbtkebsbs.html

esac
来源：http://dali.guannengcc.top/Article/details/gtmbnwcaex.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtablzwbzn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtdwnqjpnt.html

[R13] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gtyzurlgfn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtbwtyvvtc.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gtuuenjyqf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtslicfxbe.html

[R15] while 逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtzvllancc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.mhx1999.top/Article/details/gtoxwyevls.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gtqraeqpwz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtfnbtgiht.html

[R17] 数组定义与取值
来源：http://dali.tanke756.top/Article/details/gtgjigmwky.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ppjwa.cn/Article/details/gtkvmmzled.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gtajvhlzzp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.quarkkingdee.top/Article/details/gtdxjlrsqm.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtdfezqkbh.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gtunqheoxz.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gtbukconhi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gtbcqacfhx.html

[R21] 字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtdxpzwuop.html

echo "${#s}"
来源：http://dali.hongshengwenyu.top/Article/details/gttucqnzun.html

[R22] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtkcjhznaf.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gteptcodwv.html

[R23] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gthzmdoruf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gtfofasevo.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtfxvlobnj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcqyjefz.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gtaprlyows.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuanzhike.top/Article/details/gtpvfznlpm.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gtkaxwjfua.html

now=$(date +%F); echo "$now"
来源：http://dali.zhengqikj.top/Article/details/gtumhnyken.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtjvpaztaj.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gtjerokjlv.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gthhmahxoo.html

echo "scale=2; 10/3" | bc
来源：http://dali.yangfankeji.com/Article/details/gtcxurpjyk.html

[R29] 定义函数
来源：http://dali.ydzc1.top/Article/details/gttkuhfbfe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zycfv.cn/Article/details/gtgmalneen.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gtbndbanao.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yongpay.top/Article/details/gtutzrahze.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gtxwycwqkl.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuetiantiany.cn/Article/details/gthojkuxsm.html

[R32] 参数个数校验
来源：http://dali.yj20258.top/Article/details/gtqueevzts.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgvpwjwet.html

[R33] 捕获错误并提示行号
来源：http://dali.sweek.top/Article/details/gtvgfweofn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gttynarquq.html

[R34] 退出时清理
来源：http://dali.shzxlz.cn/Article/details/gtqoohlwfl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gtgvigfkxv.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtwfeinqio.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sysykeji.top/Article/details/gtadjfpntl.html

[R36] 并发执行多个任务
来源：http://dali.nanxinkj.top/Article/details/gtknfuiean.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhixingplan.top/Article/details/gtbiyikzbf.html

[R37] 把输出赋给变量
来源：http://dali.hnxiangtu.top/Article/details/gtokciysgd.html

files=$(ls -1)
来源：http://dali.smart0.xyz/Article/details/gtofgluoby.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gtfawedttj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenjidiqi.icu/Article/details/gtzxzfupge.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmseqory.html

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gticluxfgv.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gtlzcrbguj.html

echo "log" >> out.log
来源：http://dali.tianlin.xyz/Article/details/gthzrebbsx.html

[R41] 丢弃输出
来源：http://dali.sysykeji.top/Article/details/gtdoeuftjj.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtnmqcwdtw.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gtsukcaxzu.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gtebwtljct.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gtkdfsuznv.html

find . -name "*.log" -type f
来源：http://dali.yongpay.top/Article/details/gtuobapykg.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gtcbqlsdbx.html

find . -mtime -7 -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtqfdjgtkr.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gtrwkfcqus.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gtzbwktrof.html

[R46] 递归替换文件内容
来源：http://dali.guowangkeji.top/Article/details/gteefkabnb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sweek.top/Article/details/gtbggpefws.html

[R47] sed 单行替换
来源：http://dali.jiagoushi.top/Article/details/gtrcfspvad.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtmdpzskcb.html

[R48] awk 取指定列
来源：http://dali.jyoumei.cn/Article/details/gtedhdtoxw.html

awk '{print $1, $3}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtviiaojsc.html

[R49] awk 带条件
来源：http://dali.snrcjt.cn/Article/details/gtwmktqugj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gtqazdfqba.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gtnhnpyoaf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtpmzibxro.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gtsvdsquwz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aizwys.cn/Article/details/gtpodxfiyd.html

[R52] 统计行数
来源：http://dali.ppjwa.cn/Article/details/gthjwhhpot.html

wc -l a.txt
来源：http://dali.nanxinkj.top/Article/details/gtakhqpnzk.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gtryqefenj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pycfn.com/Article/details/gtvviqlqaq.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcelmzwf.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gtorfvsifq.html

[R55] 压缩与解压
来源：http://dali.xziqi.cn/Article/details/gthpxpnhek.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gteetspvbt.html

[R56] 远程拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtsiamxwze.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gtvwwucinl.html

[R57] 远程执行命令
来源：http://dali.zdqjudy.top/Article/details/gtvennfkaf.html

ssh user@host 'uptime'
来源：http://dali.dashuyun.cn/Article/details/gtwskjrijv.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gtniwhfqdg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gtgaharynp.html

[R59] 发 POST JSON
来源：http://dali.zycfv.cn/Article/details/gtomytiesc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jlsjyb.cn/Article/details/gtddphomwf.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtkzlkjrdq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zdqjudy.top/Article/details/gtrhuhaiel.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gtocgwmoeg.html

df -h;  du -sh *
来源：http://dali.jinqigufen.top/Article/details/gtzdketsmq.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwcdetbf.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gturogkyca.html

[R63] 内存与进程
来源：http://dali.gaohongyu789.top/Article/details/gtkwynhydr.html

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gtfseervjg.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gtujmtgghy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gtcsxsylge.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gtwmrkqhez.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gtysfqihwl.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gtbcgfnxqm.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlksywggn.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gtpvjorznh.html

openssl rand -hex 16
来源：http://dali.aizwys.cn/Article/details/gtvvujbbgc.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gtfojnhanx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjruerag.html

[R69] 生成随机密码
来源：http://dali.gotoacloud.top/Article/details/gtbbnigqta.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gttuchbbrk.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gtgrssaxgg.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gtvsxyvpyz.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtvqaqyndr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gtxvitshli.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gtycsamrsd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtugmxoyol.html

[R73] 分割大日志
来源：http://dali.redwolf501.top/Article/details/gtrcbwusqp.html

split -l 1000 big.log part_
来源：http://dali.sysykeji.top/Article/details/gtladtqwif.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gtpzafoogp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gttqsrmwnr.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gtfuaersvq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gtvrxdgqxm.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gtbvaxbfin.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtabczlrgi.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gtxvpohoka.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gtmhmhugru.html

[R78] 交互式菜单
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsutvpdld.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoscfwij.html

[R79] 解析命令行选项
来源：http://dali.yanxiufei.cn/Article/details/gtnlwfkhnk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xinyue.icu/Article/details/gtyxkqvypo.html

[R80] 查看脚本执行耗时
来源：http://dali.sysykeji.top/Article/details/gtyzyqtlzu.html

time ./run.sh
来源：http://dali.redwolf501.top/Article/details/gtdqydxubg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtgxtsbbol.html

S. C / C++ 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtjzzqlmgs.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtzrfsaeuh.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtwlmmdyni.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gtohtnnqty.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.c1oappe.top/Article/details/gtiqgslqrj.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtzghenevm.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj202588.top/Article/details/gttnvnytdd.html

[S03] C：读入整数
来源：http://dali.andypj.xyz/Article/details/gtbdyfabir.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gtzhfomhvd.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpjfgpkn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqszmahuw.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtxfeosndf.html

strlen(s)
来源：http://dali.yangfankeji.com/Article/details/gtnadyxiwp.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtgrhliuqg.html

strcmp(a, b) == 0
来源：http://dali.hammf.cn/Article/details/gthmqlbmdl.html

[S07] C：数组遍历求和
来源：http://dali.cdnleiting.top/Article/details/gthcuwzvik.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gtrnxnzvqc.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gtgtjybpim.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cucudq.cn/Article/details/gtyioyuzsf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gtjpvtbmpp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtjiocntyi.html

[S10] C：指针与解引用
来源：http://dali.cashguo.top/Article/details/gtujxcckyd.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gtregxnlqf.html

[S11] C：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtrsujuaxb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gtguyiacao.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gtcaddzpfe.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtkwwsvcar.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gtalvyerqy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gtbwvhnyaq.html

[S13] C：宏定义
来源：http://dali.tian-w.cn/Article/details/gtlpahgexr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cdnleiting.top/Article/details/gtujnjbqop.html

[S14] C：枚举
来源：http://dali.wangdashe.top/Article/details/gtyekipskb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258888.top/Article/details/gtdusbhuuc.html

[S15] C：类型转换
来源：http://dali.cheryme.top/Article/details/gtkvmphsjx.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gtvuzkiiwm.html

[S16] C：位操作置位
来源：http://dali.zhengqikj.top/Article/details/gtkrspiorp.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gtvvggcmwl.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtsaszqkjj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gtrihqdonm.html

[S18] C：命令行参数
来源：http://dali.zhengqikj.top/Article/details/gtevstiwtm.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gtgeocgqqq.html

[S19] C：快速排序
来源：http://dali.jinqigufen.top/Article/details/gtsikchbmr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtunoxzjby.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gtgpifxtia.html


<!-- 参考信息 -->