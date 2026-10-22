代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtigqmgsia.html

[Q54] 清空表
来源：http://dali.svipenyu.cn/Article/details/gtounomfgc.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwupxkxoh.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyxsgmqt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtkvoevkjn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.andypj.xyz/Article/details/gtieirwaph.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrtfbstc.html

[Q57] 行号
来源：http://dali.zdqjudy.top/Article/details/gtfghwtlpq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.meibo888.top/Article/details/gtrhlfgqpq.html

[Q58] 累计求和
来源：http://dali.wangshuangyany.cn/Article/details/gtcypappjo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtaoidtgdk.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtvazeulij.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtuyvbnrdu.html

[Q60] 取上一行 / 下一行
来源：http://dali.shuidangran.top/Article/details/gtwmlclcor.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sweek.top/Article/details/gtpckoyzrm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtiiajwdwz.html

[Q61] 移动平均
来源：http://dali.cucudq.cn/Article/details/gtqoeajojz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtsegdnpjb.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtebxblcep.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtmcltmbkn.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gtzggtbrab.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.svipenyu.cn/Article/details/gtenkuhtlf.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtxepimwxw.html

COMMIT;
来源：http://dali.xuanzx.com/Article/details/gtyyynbcjk.html

[Q65] 回滚事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxnkbhvq.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gtsiilmyln.html

[Q66] 行锁查询
来源：http://dali.svipenyu.cn/Article/details/gtfzugahvq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sufxvd.cn/Article/details/gtdjpismus.html

[Q67] 设置隔离级别
来源：http://dali.hnxiangtu.top/Article/details/gtaubbjthm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gtncchatib.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtxpuhhuzg.html

SAVEPOINT sp1;
来源：http://dali.guowangkeji.top/Article/details/gtfktpjxmi.html

ROLLBACK TO sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtycladaau.html

[Q69] 查看执行计划
来源：http://dali.hammf.cn/Article/details/gtertbizif.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gtgtneuskr.html

[Q70] 更新统计信息
来源：http://dali.haohaochexian.top/Article/details/gtqnuzguwk.html

ANALYZE TABLE users;
来源：http://dali.gzhubu.top/Article/details/gtnqfsnzxf.html

[Q71] 查看建表语句
来源：http://dali.zycfv.cn/Article/details/gtshnahpke.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fzhhl.top/Article/details/gtoyqyxmxl.html

[Q72] 查看索引
来源：http://dali.hywenlv.cn/Article/details/gthpqoaiei.html

SHOW INDEX FROM users;
来源：http://dali.gzhubu.top/Article/details/gtzeilkfva.html

[Q73] 查看表状态
来源：http://dali.xinyue.icu/Article/details/gtzdhtvogx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.svipenyu.cn/Article/details/gtttiaijoy.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gtmygybheg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gtmixqxevu.html

[Q75] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gtxpfttiwd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtvvvepeff.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenlongwang.top/Article/details/gtyuziaqed.html

[Q76] 按天统计
来源：http://dali.zhoulong.xyz/Article/details/gtbujmxicx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhengqikj.top/Article/details/gtnhhxlvra.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gtlhxxcyca.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gtmkvhobfc.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuqbvztm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gtmkhelrmz.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtkjuidbrd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gtkdoaewui.html

[Q80] 字符串截取
来源：http://dali.jqgfzy.top/Article/details/gtaehixtgc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtcyjmcmdy.html

[Q81] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gtqsyktlkm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtwcvabzjb.html

[Q82] 字符长度与字节长度
来源：http://dali.aibaodan.cn/Article/details/gtfggaiixn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtjjyzselw.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtkmjvahji.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtznvamjyc.html

[Q84] 去除首尾空格
来源：http://dali.xylfe.cn/Article/details/gtnerfjxiu.html

SELECT TRIM(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtzonodxpv.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gtqcqjdxtb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fzhhl.top/Article/details/gtkeljrihu.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gtcsgiotzl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gtrtulxunx.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gtgjmnjsdq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ppjwa.cn/Article/details/gtrbridtcv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrwmhyvy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yongpay.top/Article/details/gtviprtlun.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gtxxiqrgoa.html

[Q89] 判断表是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtvpelmhzh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj202588.top/Article/details/gtdxvannmj.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gtcskrzzov.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigfzy.top/Article/details/gthswwycmv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtcaeksrqh.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtrfhmgufo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gteaiszsrv.html

[R01] shebang 与严格模式
来源：http://dali.cashguo.top/Article/details/gttvqbdcyh.html

#!/usr/bin/env bash
来源：http://dali.jinqigfzy.top/Article/details/gtnwruuqfn.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gtrrvuuzck.html

[R02] 变量赋值与使用
来源：http://dali.havefunace.top/Article/details/gtofragxzo.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gtwzfggjib.html

[R03] 只读变量
来源：http://dali.xuanzx.com/Article/details/gtnrwdrjgv.html

readonly PI=3.14
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumscfsbz.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gtrsrgleqf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dianchejie.cn/Article/details/gtitrnafff.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gtzlpwiyfc.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gtcfoehvnb.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gteuvfyosn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtafsicwss.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gtsvnbpnsw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfcucjsg.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gtnsnkvpim.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guowangkeji.top/Article/details/gtciivyxmk.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtzlnykjoy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gthkpigqrj.html

[R10] 正则匹配
来源：http://dali.mhx1999.top/Article/details/gttwgltrkb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gtfxfavpkc.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gtdgcwbjkt.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gtfbukrdur.html

start) echo "启动" ;;
来源：http://dali.hnqzz.top/Article/details/gtlvihlcjk.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gthfgaoczx.html

*)     echo "未知命令" ;;
来源：http://dali.hywenlv.cn/Article/details/gtilnctvfd.html

esac
来源：http://dali.nwbrower.top/Article/details/gtaojgmpns.html

[R12] for 遍历文件
来源：http://dali.shangyingyoupin.top/Article/details/gtzichtusq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gtifwzazkt.html

[R13] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gtxxjdhlnv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gtymgvhnpd.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gtixyywwde.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtxdojfpkf.html

[R15] while 逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtqwtgppng.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtxrygfevu.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gtxuameoya.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtqchwtvrf.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdqelazl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aibaodan.cn/Article/details/gtltmrfgqg.html

[R18] 遍历数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeerpchw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daxiang520.top/Article/details/gtyciugzat.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtldacxzcj.html

echo "${#arr[@]}"
来源：http://dali.jinqigfzy.top/Article/details/gtbmblmexc.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gtnsutqokx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenzaomai.com/Article/details/gtpyfhocrf.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtnqtggfbq.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gtunnckzwf.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gtitnlecqz.html

echo "${s:0:5}"
来源：http://dali.jinqigfzy.top/Article/details/gtclxwifkb.html

[R23] 字符串替换
来源：http://dali.sweek.top/Article/details/gtuvzyxdgr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gtdnxfpiqf.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtympvrxmz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gtkmriolic.html

[R25] 去后缀 / 去前缀
来源：http://dali.meibo888.top/Article/details/gtbsazqezo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.svipenyu.cn/Article/details/gtgirgqlte.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gtvlxdbchi.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gtompxoder.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gtqlkhhlqu.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gtyygxqhwr.html

[R28] 浮点运算
来源：http://dali.tian-w.cn/Article/details/gteegvcckq.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtjfrofmtn.html

[R29] 定义函数
来源：http://dali.yonumen.top/Article/details/gtzgrmzgfu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gtosijdufm.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gtmjsmxfwi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtjyrkbmoa.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gtajiaxlfk.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gteonxasfn.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gtxaxtxqak.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtdohftaql.html

[R33] 捕获错误并提示行号
来源：http://dali.sysykeji.top/Article/details/gtaazvxzuu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dashuyun.cn/Article/details/gtuwdqkawf.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gtycngsgnd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtomcxqlum.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtjsgffpms.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtdilxqcel.html

[R36] 并发执行多个任务
来源：http://dali.andypj.xyz/Article/details/gtbtmepjjc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gtvillyukz.html

[R37] 把输出赋给变量
来源：http://dali.0kj1m.cn/Article/details/gtjpreancg.html

files=$(ls -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtknwcagfz.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gtcmvdvjbi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258888.top/Article/details/gtymwicwci.html

[R39] 重定向标准输出与错误
来源：http://dali.sysykeji.top/Article/details/gtgowconog.html

cmd > out.log 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtqdzhotmd.html

[R40] 追加写日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibetbbvr.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtkesdkjul.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gtxpjfzgak.html

cmd >/dev/null 2>&1
来源：http://dali.xziqi.cn/Article/details/gtcjkbuxdv.html

[R42] 输入重定向
来源：http://dali.sysykeji.top/Article/details/gtrjflxbtz.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gttlqbmogy.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gtknwmhlch.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gtkewajnuk.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gthpxtysrz.html

find . -mtime -7 -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtbirpzklw.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gtkojpydqd.html

find . -name "*.tmp" -delete
来源：http://dali.cdnleiting.top/Article/details/gtmkjuacqt.html

[R46] 递归替换文件内容
来源：http://dali.sweek.top/Article/details/gtvymlxphb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuanzx.com/Article/details/gtamjpxith.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gtteivssch.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxeyruje.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gthwmeecsw.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtsbfqcvvc.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gtxuhkviik.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gtplamjcvm.html

[R50] awk 求和
来源：http://dali.vqdsnc.cn/Article/details/gtodsycqkg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtdyiqyjnl.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gtbqrddafh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jlsjyb.cn/Article/details/gtwhusvgps.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gtzghxupnb.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gtcinvjfhr.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gtdnxvquhd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gtelhtczlk.html

[R54] 比较两个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijzgxnrl.html

diff a.txt b.txt
来源：http://dali.jqgfzy.top/Article/details/gtpnxkxxzr.html

[R55] 压缩与解压
来源：http://dali.zhoulong.xyz/Article/details/gtovjbvgjs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gtdosajaep.html

[R56] 远程拷贝
来源：http://dali.xylfe.cn/Article/details/gtzkkdztwz.html

scp file user@host:/path/
来源：http://dali.aibaodan.cn/Article/details/gtnozyqigs.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gtievnwktr.html

ssh user@host 'uptime'
来源：http://dali.yj20258.top/Article/details/gtpudsmral.html

[R58] 下载文件
来源：http://dali.jiagoushi.top/Article/details/gtrmvtjkea.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhoulong.xyz/Article/details/gtczuumxek.html

[R59] 发 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtjqdezdwp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gtrkyoprzz.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtafmmuawl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gthahqxcej.html

[R61] 磁盘占用
来源：http://dali.jianghu66.top/Article/details/gtmicureow.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gtnkwsbmuk.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gttbfechkg.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtbxsmkomy.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gtnifepvjj.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gtotgdvway.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gtdtsslxvu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gtbnasgphm.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gtktzbwaig.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gtpikmvevm.html

[R66] 定时任务
来源：http://dali.guowangkeji.top/Article/details/gttlsvcrdy.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gtrjackeas.html

[R67] 生成随机十六进制串
来源：http://dali.haohaochexian.top/Article/details/gtgipwozfu.html

openssl rand -hex 16
来源：http://dali.c1oappe.top/Article/details/gttlcoujcg.html

[R68] 计算文件校验值
来源：http://dali.haohaochexian.top/Article/details/gtkprtfotb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gtkiqxnifz.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gtrvifeqjh.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxhimotm.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gtxmsejcwu.html

date +%s;  date -d @1700000000
来源：http://dali.vqdsnc.cn/Article/details/gtpumosspz.html

[R71] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtslyrnafi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cdnleiting.top/Article/details/gtkpsprwdf.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gtzezpczbe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtqefrrjjn.html

[R73] 分割大日志
来源：http://dali.smart0.xyz/Article/details/gtihljibjr.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqhojces.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkpadnpr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cqqwz.cn/Article/details/gtcgdmyklh.html

[R75] 导出环境变量
来源：http://dali.chenzaomai.com/Article/details/gtytpycodw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ivvv.top/Article/details/gttwkeozic.html

[R76] 使用临时文件
来源：http://dali.jianghu66.top/Article/details/gtdndxqitq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtauipkmyc.html

[R77] 读取用户输入
来源：http://dali.cdnleiting.top/Article/details/gtpmhinrik.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gtguzsucrw.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gtutlvijsi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gtnlperrpn.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gtgvaidlom.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.c1oappe.top/Article/details/gtajyozdmi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gtkdkxmqow.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gtbojmlyci.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkclybezf.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gtnnfhtfwg.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjwewtkjq.html

[S01] C：Hello World
来源：http://dali.havefunace.top/Article/details/gtuvtqqswq.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gthlphcmcp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangdashe.top/Article/details/gtvdqsquin.html

[S02] C：变量与格式化输出
来源：http://dali.xuanzx.com/Article/details/gtkgolpgxi.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gtxcummrpv.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gtkijfkqmw.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gtpsjlhqju.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gtmegxcibo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtnhtmymte.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtrclmfdgy.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gtrxajgzyq.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtbfbshimt.html

strcmp(a, b) == 0
来源：http://dali.wangdashe.top/Article/details/gtvgdqavka.html

[S07] C：数组遍历求和
来源：http://dali.yueranfly.top/Article/details/gtnhptcvuo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tianlin.xyz/Article/details/gtxyhmufvb.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gtbhwynzfu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtafosdcjf.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gtqawpfdge.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gttnkvvnnq.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtbreuvxdc.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gthqtspusr.html

[S11] C：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtexlalfex.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gtuuijcjee.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gtwziescpx.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtnyupdrgf.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gtzfukkjhu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtmknscqnf.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gtwfubrhgm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.kuanghao11.cn/Article/details/gtzcjzjkms.html

[S14] C：枚举
来源：http://dali.yj20258.top/Article/details/gtjjftqkri.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yueranfly.top/Article/details/gtapgcgbbw.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gtlabduxls.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gtnfkuknxe.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gtuezqibks.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gttxfgnsup.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtbhgxcgnn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gtgigemyoa.html

[S18] C：命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtakeeszpv.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gtxmbvltzw.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtxwtjsgqp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gtfgbgkfts.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gtnaqkjltz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtrgwdfuaw.html

[S21] C：字符类别判断
来源：http://dali.jlsjyb.cn/Article/details/gtnaceojyp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gtzmfxmqba.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gthreonoov.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gogol.net.cn/Article/details/gtbmissgkz.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgddnzvs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aizwys.cn/Article/details/gtfgfvnfno.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gtsslkvktm.html


<!-- 参考信息 -->