代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtkfafljnj.html

[Q54] 清空表
来源：http://dali.jyoumei.cn/Article/details/gtbpxxclgz.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gtktxscsog.html

[Q55] 排名（并列占位）
来源：http://dali.tanke756.top/Article/details/gtymuuximg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fzhhl.top/Article/details/gtlwjijjlp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shangyingyoupin.top/Article/details/gtccaaqdim.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtymebohgv.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gtrldgvith.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtywhsvukj.html

[Q58] 累计求和
来源：http://dali.jianghu66.top/Article/details/gtmuqowkno.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtsgohwwtf.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gthkskoxdg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtgwcdfjxp.html

[Q60] 取上一行 / 下一行
来源：http://dali.guowangkeji.top/Article/details/gtrnqlfvpx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgufenzy.top/Article/details/gtxswqiary.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtisvqcjxm.html

[Q61] 移动平均
来源：http://dali.jinqigfzy.top/Article/details/gtlebjcxft.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtnqepfrjx.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gtmwbcrice.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtrzrijyeq.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gttzbqawdq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shangyingyoupin.top/Article/details/gtygxnghcj.html

[Q64] 提交事务
来源：http://dali.yj202588.top/Article/details/gthwbnfzyt.html

COMMIT;
来源：http://dali.cheryme.top/Article/details/gtzxqiqscn.html

[Q65] 回滚事务
来源：http://dali.iojbl.cn/Article/details/gtvnwnfola.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gtmpvaucak.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gticocllgp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gtjqaitmma.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gtpoofhrgv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yueranfly.top/Article/details/gtcppnjbfy.html

[Q68] 保存点
来源：http://dali.iojbl.cn/Article/details/gtgbhfypaf.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gtyiyhshrg.html

ROLLBACK TO sp1;
来源：http://dali.andypj.xyz/Article/details/gtowwlswrc.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszktxvfs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangshuangyany.cn/Article/details/gtgfjojpeu.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gtigidjjbr.html

ANALYZE TABLE users;
来源：http://dali.yonumen.top/Article/details/gtyphhouzf.html

[Q71] 查看建表语句
来源：http://dali.gaohongyu789.top/Article/details/gtgvqpamwt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxinkj.top/Article/details/gtmqchfbpw.html

[Q72] 查看索引
来源：http://dali.hywenlv.cn/Article/details/gtpzjcqqjx.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gtgwqydkeb.html

[Q73] 查看表状态
来源：http://dali.dianchejie.cn/Article/details/gtlywqnvqf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gtljbiyiuk.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtmpwxolzl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gotoacloud.top/Article/details/gtyfovsbou.html

[Q75] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtgtaujdhx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gtffoxdzky.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gtxhcmbnco.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gtovfdanmg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhoulong.xyz/Article/details/gtbkyptvqt.html

[Q77] 时间加减
来源：http://dali.gotoacloud.top/Article/details/gtdtcijxbr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhengqikj.top/Article/details/gtbmfwdaba.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gtrlglhnrf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmktscsoa.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gthzrwdfjm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yangfankeji.com/Article/details/gttvxmhzod.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gtoblzouur.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtqfjlpaoz.html

[Q81] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtshsfyxwv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gtkvbaboiw.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gtygqnhafc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtbhdkbors.html

[Q83] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtmzgdcfeu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtvorqzhth.html

[Q84] 去除首尾空格
来源：http://dali.yuxming.cn/Article/details/gtwfepfzuv.html

SELECT TRIM(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtgmoycead.html

[Q85] 数值取整
来源：http://dali.xylfe.cn/Article/details/gtpummoehc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258.top/Article/details/gtgtxjhmav.html

[Q86] 读取 JSON 字段
来源：http://dali.iojbl.cn/Article/details/gtihvwxitq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.iojbl.cn/Article/details/gtstmwsbkz.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gthfovdbih.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tian-w.cn/Article/details/gtasfjyzfn.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtiommervu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gthfmyiqos.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtmgwsckrh.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gtotxdrbzu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aizwys.cn/Article/details/gtrjybored.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gthbehygec.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifgpnvig.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmfhtnplu.html

R. Bash 专题
来源：http://dali.shzxlz.cn/Article/details/gtooacktth.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtzsyfaeag.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gtrtsuxflx.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gtuxgecknl.html

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gtkhuiuigu.html

[R02] 变量赋值与使用
来源：http://dali.bjfxy.top/Article/details/gtzfirqoho.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gttbaaaaqy.html

[R03] 只读变量
来源：http://dali.ybcxt.top/Article/details/gtpeekesez.html

readonly PI=3.14
来源：http://dali.yj20258888.top/Article/details/gtjeckgmtr.html

[R04] 位置参数
来源：http://dali.daxiang520.top/Article/details/gtmgoswyjc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.bjfxy.top/Article/details/gtoxyrbpmu.html

[R05] 参数默认值
来源：http://dali.jqgufenzy.top/Article/details/gtyarihksf.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gtbgvwjlyu.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gtlbsayxur.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtsquulkxl.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gtyohjbcsr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gtgtekwaec.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gtjlxjvllp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gtyaviynlh.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtvhfmlyvu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtmvwrcswq.html

[R10] 正则匹配
来源：http://dali.ivvv.top/Article/details/gtdtcncjdq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gtftxpnxve.html

[R11] case 多分支
来源：http://dali.tanke756.top/Article/details/gtppdpaqsj.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gtipyhsrtr.html

start) echo "启动" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtlqydqjxh.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtigdqzymo.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtsvwbzllk.html

esac
来源：http://dali.yj20258.top/Article/details/gtmyrmdbtk.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gtmvylaehc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gtbdlvxfzp.html

[R13] for 计数循环
来源：http://dali.hammf.cn/Article/details/gtjlcapdqh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtohwkinej.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gtlroanplk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhrajlkx.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtxulyxqhc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtcazwwscu.html

[R16] until 等待条件
来源：http://dali.havefunace.top/Article/details/gtoajejses.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtpccgekiy.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gtymmnjmgu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tianlin.xyz/Article/details/gtkcviubrr.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gtaakgeeto.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gtbjrduxoe.html

[R19] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtykovrdxp.html

echo "${#arr[@]}"
来源：http://dali.shzxlz.cn/Article/details/gtoixfmdpe.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtjzdnrhfa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gtgujespbq.html

[R21] 字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtuapsfulz.html

echo "${#s}"
来源：http://dali.wangdashe.top/Article/details/gtcqofarth.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtvpqlseuv.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvunctctf.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtlubyzffw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangshuangyany.cn/Article/details/gtirlnyihp.html

[R24] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtcweitfvw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gtxjqlfjot.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gtridmzntj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yanxiufei.cn/Article/details/gtbpklqjnh.html

[R26] 命令替换
来源：http://dali.yuanzhike.top/Article/details/gtilleebkk.html

now=$(date +%F); echo "$now"
来源：http://dali.hnxiangtu.top/Article/details/gtcfhdcwtz.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gtfzemhgyp.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gtdpjfuago.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiniwlvi.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gthpfzzlfk.html

[R29] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtfqkphcpk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fengsongda.top/Article/details/gtlikovnia.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gtvrwpozxl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yongpay.top/Article/details/gtturfjfpo.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtecbjkcvp.html

f() { local x=1; echo "$x"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuknfupku.html

[R32] 参数个数校验
来源：http://dali.cheryme.top/Article/details/gtilbryxez.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gthuumntqe.html

[R33] 捕获错误并提示行号
来源：http://dali.chenzaomai.com/Article/details/gtjnwwkyde.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gtkkmrejdn.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gtlwlbixek.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtinbeqemc.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gtsredsihv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhixingplan.top/Article/details/gtaqeyfixp.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gtjhhkhvdq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtsjvvwuto.html

[R37] 把输出赋给变量
来源：http://dali.jianghu66.top/Article/details/gtelnkhobu.html

files=$(ls -1)
来源：http://dali.gaohongyu789.top/Article/details/gtyaswrsaj.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwsihcwd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhoulong.xyz/Article/details/gtlieqmvtk.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gtxrbjomct.html

cmd > out.log 2>&1
来源：http://dali.tian-w.cn/Article/details/gtjeojiush.html

[R40] 追加写日志
来源：http://dali.wangdashe.top/Article/details/gtnzwlwbdj.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gtcjjcbcdr.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gtvgnoxnaf.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtgcexkpia.html

[R42] 输入重定向
来源：http://dali.smart0.xyz/Article/details/gtkkuqptiy.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtszskmxlt.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gtdrchbyul.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gttfcrjjmt.html

[R44] 按修改时间查找
来源：http://dali.tianlin.xyz/Article/details/gtusyhgtyw.html

find . -mtime -7 -type f
来源：http://dali.yj20258888.top/Article/details/gtmrcuipic.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykoathqy.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gtqjevjhkv.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gtyqbcexzi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gtguckdbut.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gtxiymyzzj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtauqhfcad.html

[R48] awk 取指定列
来源：http://dali.aibaodan.cn/Article/details/gtyejsdqvv.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtvbskfdwu.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvryhrlg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dashuyun.cn/Article/details/gtmwzpwkzp.html

[R50] awk 求和
来源：http://dali.cashguo.top/Article/details/gtnatajesj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gtnsuycjbe.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gtilerbfpy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gtszonbdii.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gttuqpvjvu.html

wc -l a.txt
来源：http://dali.yj202588.top/Article/details/gtblyzlvfo.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gtbquuclfs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pengpengdd.cyou/Article/details/gtprnwqbav.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gtljiyuboq.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gtevzlopds.html

[R55] 压缩与解压
来源：http://dali.ivvv.top/Article/details/gtokrinuvl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhengqikj.top/Article/details/gthibmffla.html

[R56] 远程拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrigefvv.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gtgnxjlixf.html

[R57] 远程执行命令
来源：http://dali.wangdashe.top/Article/details/gtwxpahfbc.html

ssh user@host 'uptime'
来源：http://dali.sysykeji.top/Article/details/gtqmbltrds.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gtwnvrklkf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gtcfbcotek.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtfbhjjzzw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guowangkeji.top/Article/details/gtjuwmhqxx.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtemnjmguv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gtjcnddhot.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gtkihstrdr.html

df -h;  du -sh *
来源：http://dali.pengpengdd.cyou/Article/details/gtriybxnfz.html

[R62] 找最占空间的文件
来源：http://dali.guannengcc.top/Article/details/gtoyjinqyt.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gthbsbvabp.html

[R63] 内存与进程
来源：http://dali.bjfxy.top/Article/details/gtvrzpojva.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gtgpqikleo.html

[R64] 结束进程
来源：http://dali.pycfn.com/Article/details/gtxdycpdot.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gtovbwosma.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuurwimd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gtrnuedahy.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gtlfgrbofx.html

crontab -e;  crontab -l
来源：http://dali.chenzaomai.com/Article/details/gtvgopdkpk.html

[R67] 生成随机十六进制串
来源：http://dali.yuanzhike.top/Article/details/gtbscvdduh.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gtswqdfyza.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gtsxtjvvmc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtlitbeybf.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gtsfkhemsp.html

head -c 16 /dev/urandom | base64
来源：http://dali.yueranfly.top/Article/details/gtzchybqih.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxcbxwqf.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gtedqdeucw.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtvhbwjytk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gthhuixeot.html

[R72] 等待端口就绪
来源：http://dali.gogol.net.cn/Article/details/gtuncvpxkd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtwwhzthnx.html

[R73] 分割大日志
来源：http://dali.zhongyouzk.top/Article/details/gttrevgqpz.html

split -l 1000 big.log part_
来源：http://dali.zycfv.cn/Article/details/gtwvehmasm.html

[R74] 批量重命名
来源：http://dali.yonumen.top/Article/details/gtvfhvpiid.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtgksilqba.html

[R75] 导出环境变量
来源：http://dali.hnqzz.top/Article/details/gtbkdnfxde.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hfpthk.cn/Article/details/gtcjbweyth.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gtijmgyukh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtwlkaifbc.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gteymwclrr.html

read -rp "请输入: " ans
来源：http://dali.shuidangran.top/Article/details/gtajnaybuw.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gtobtzhgvg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtrlmcpyos.html

[R79] 解析命令行选项
来源：http://dali.jiagoushi.top/Article/details/gtwjgbutzw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gteijikvxv.html

[R80] 查看脚本执行耗时
来源：http://dali.ppjwa.cn/Article/details/gtjvhpzggp.html

time ./run.sh
来源：http://dali.cqqwz.cn/Article/details/gtapwzqvnu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtlugyprlj.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gtisiydzrd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkfajuyfz.html

[S01] C：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtvmtpgrxq.html

#include <stdio.h>
来源：http://dali.yonumen.top/Article/details/gtfewxcadp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gtzebilaef.html

[S02] C：变量与格式化输出
来源：http://dali.shuidangran.top/Article/details/gtnvzlbthu.html

int a = 10; printf("%d\n", a);
来源：http://dali.jiagoushi.top/Article/details/gtluqxaazv.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gtzmegeilu.html

int x; scanf("%d", &x);
来源：http://dali.jiagoushi.top/Article/details/gtjgltlvrz.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gtnahdofha.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gtvprpqcva.html

[S05] C：字符串长度
来源：http://dali.jinqigufen.top/Article/details/gtlgvsnsyn.html

strlen(s)
来源：http://dali.iojbl.cn/Article/details/gtqulqdgwx.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtsdogxnyt.html

strcmp(a, b) == 0
来源：http://dali.yonumen.top/Article/details/gtudbqdgxz.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gtudgwzqlz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gtuspqibvf.html

[S08] C：动态内存分配与释放
来源：http://dali.andypj.xyz/Article/details/gtiedmkidc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pengpengdd.cyou/Article/details/gtelawyuxc.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gtsqmzgwud.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gotoacloud.top/Article/details/gtkdevcvzw.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gtxkxdpxei.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gtlezabrix.html

[S11] C：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtnifmwflv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gtwjzsevje.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtljnplyvg.html

fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtbvxfnzqk.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gtjutwhapy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gtslccgqeq.html

[S13] C：宏定义
来源：http://dali.fengsongda.top/Article/details/gtwysjlikn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangdashe.top/Article/details/gtcatijwbf.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gtcydknozf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258.top/Article/details/gtcgnkprfw.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gtdqagwkaj.html

(double) a / b
来源：http://dali.sysykeji.top/Article/details/gtqoyuxfyu.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gtldrpjqdy.html

x |= (1 << 3);
来源：http://dali.xylfe.cn/Article/details/gthxknnlfq.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebjijlux.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gtvmfcraom.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gtgehbslls.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsdtpvbp.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gtocjgdydm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtdafudubk.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gtbtlvwdvy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtflxdouww.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtmtzsijfl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcfbudfs.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmxfjhwh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gtmlsduvvg.html

[S23] C：随机数
来源：http://dali.316326.xyz/Article/details/gtpmlpqgue.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gttjpvukbd.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gtrhamgpyy.html


<!-- 参考信息 -->