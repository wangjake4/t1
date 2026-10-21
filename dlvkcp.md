代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cheryme.top/Article/details/gtooucvris.html

[Q58] 累计求和
来源：http://dali.sufxvd.cn/Article/details/gthmwsaxwd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtclhqbxuh.html

[Q59] 分组内累计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgskyyfv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtoakenvbb.html

[Q60] 取上一行 / 下一行
来源：http://dali.vqdsnc.cn/Article/details/gtxubcdkzx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenlongwang.top/Article/details/gtkbdjnnms.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtpfweujys.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gtswghcxwr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtuojlbolj.html

[Q62] 分组占比
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkacqqhvs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtiqxdvrzz.html

[Q63] 开启事务
来源：http://dali.sysykeji.top/Article/details/gthsohvydz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gtfopfptnz.html

[Q64] 提交事务
来源：http://dali.dashuyun.cn/Article/details/gtawciryft.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gtigbbznex.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gtlfkxmffh.html

ROLLBACK;
来源：http://dali.sxryk.cn/Article/details/gtsjlamvzs.html

[Q66] 行锁查询
来源：http://dali.jinqigfzy.top/Article/details/gtncbuwhxi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgufenzy.top/Article/details/gtiyokvufl.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gtychhlfgb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gtjxhtqvdw.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gtrnqntyzl.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gtfbcirntb.html

ROLLBACK TO sp1;
来源：http://dali.yueranfly.top/Article/details/gtoybvptvk.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gtvzlkqttu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gtcthuezjr.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gtzusrlxkk.html

ANALYZE TABLE users;
来源：http://dali.ivvv.top/Article/details/gtkhhtkmtb.html

[Q71] 查看建表语句
来源：http://dali.gogol.net.cn/Article/details/gtsyrdbyny.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangdashe.top/Article/details/gtsjzzuzkz.html

[Q72] 查看索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnrzfxfo.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtzojctfgr.html

[Q73] 查看表状态
来源：http://dali.pengpengdd.cyou/Article/details/gtwhwxqjso.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gtipptilgy.html

[Q74] 强制使用索引
来源：http://dali.guannengcc.top/Article/details/gtktfpells.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gtexiaodqg.html

[Q75] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtdvcloxfi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtztmockhp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tanke756.top/Article/details/gtyaedinwn.html

[Q76] 按天统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfgjphbm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gtlkawpmjj.html

[Q77] 时间加减
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrutviynz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gthnvzhtgu.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtltrkvafu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gaohongyu789.top/Article/details/gtrdeppomn.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtyltbiwee.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guannengcc.top/Article/details/gtttzthliw.html

[Q80] 字符串截取
来源：http://dali.yj20258888.top/Article/details/gtyaduhvtz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtddfqdpmd.html

[Q81] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtxkackuky.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gtblmkhlxv.html

[Q82] 字符长度与字节长度
来源：http://dali.hysaishi.cn/Article/details/gteabuowng.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtlmeyrgwx.html

[Q83] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtovumguah.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjkghguc.html

[Q84] 去除首尾空格
来源：http://dali.quarkkingdee.top/Article/details/gttsgrcssx.html

SELECT TRIM(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtkeppynqm.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gtggelpaem.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gtgmboihsa.html

[Q86] 读取 JSON 字段
来源：http://dali.tanke756.top/Article/details/gtkpuhwoax.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenjidiqi.icu/Article/details/gtofbppzrt.html

[Q87] JSON 字段做条件
来源：http://dali.c1oappe.top/Article/details/gtmjqloigd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cheryme.top/Article/details/gtglzglawu.html

[Q88] 行转列（条件聚合）
来源：http://dali.tian-w.cn/Article/details/gtqijcmncy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gtglmpaucg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtvopyxczc.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtwddgxdcp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gtzsoyewki.html

[Q90] 生成序号列
来源：http://dali.jqgufenzy.top/Article/details/gtxmbbxhzh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtghebbekm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtwljfpary.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gtetltffdb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtnchleogr.html

[R01] shebang 与严格模式
来源：http://dali.xinyue.icu/Article/details/gtabekusnr.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gtpwvfkzpd.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gtngqwwkct.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gtubncngjf.html

name="Tom"; echo "$name"
来源：http://dali.cheryme.top/Article/details/gtbbdnfxkz.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gtajmydhnb.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gtxslvqejm.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gtgqjptxfk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsifzjgqj.html

[R05] 参数默认值
来源：http://dali.nanxinkj.top/Article/details/gttfmxqsjy.html

name="${1:-default}"
来源：http://dali.fengsongda.top/Article/details/gtpxsxusqj.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gtewhgicwk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtkxklobka.html

[R07] if 判断文件
来源：http://dali.meibo888.top/Article/details/gtsdlebhep.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtjzazapng.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gtcpqavvrb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gtmrclzqwo.html

[R09] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtwospgzzu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ehwqpu.com/Article/details/gtdldbozef.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gtmtcmgpzi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gtpwcmrvvf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gttaucgeot.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gtinqcvuku.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gtbfdroqld.html

stop)  echo "停止" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtnujzkbpk.html

*)     echo "未知命令" ;;
来源：http://dali.cucudq.cn/Article/details/gtvpmjshzh.html

esac
来源：http://dali.gogol.net.cn/Article/details/gtjayvruyx.html

[R12] for 遍历文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpyzyfib.html

for f in *.txt; do echo "$f"; done
来源：http://dali.kuanghao11.cn/Article/details/gtrtddbnfc.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gtmreqqils.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtxmegamml.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gtvfgirehc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtyhfzjvmc.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtqngazdnc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gtzeprejfu.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gtjpiftloz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiohbxsy.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gtctemndje.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrojvclb.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gtlsauxudq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gtkdnbvidi.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtpuybxhwg.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gtitisnhrn.html

[R20] 关联数组（字典）
来源：http://dali.hnxiangtu.top/Article/details/gtouzkyzwi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtionaxtiv.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtghpwzzys.html

echo "${#s}"
来源：http://dali.wangdashe.top/Article/details/gtinwcnhpp.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtlpqlxfju.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gtycibjqmg.html

[R23] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gtcluvtzrh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cqqwz.cn/Article/details/gtbfvmfphe.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtqlcjtzwz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtlpgmgjhs.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gtvyxgncvh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gtuqueylky.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtlglhwojg.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gtlqnwmowf.html

[R27] 算术展开
来源：http://dali.dashuyun.cn/Article/details/gtmjjvulik.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gtlsxajfhr.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlfsnodf.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gtguxstoov.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gtfanjloqe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jyoumei.cn/Article/details/gtdeqobibn.html

[R30] 函数返回状态码
来源：http://dali.ivvv.top/Article/details/gtdmdvetyw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gtmuzkfuva.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtysorxzxx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gtozusemas.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gtcnkhabdk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtpmntrghs.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtcykmomww.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258888.top/Article/details/gtnnaptkve.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtfiwmqtkt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsntvwnrp.html

[R35] 后台执行并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtdinyrsps.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gtcsztglvk.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gttsmnwiuc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gtilidxggd.html

[R37] 把输出赋给变量
来源：http://dali.smart0.xyz/Article/details/gtjslkdcws.html

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gtimirtcdw.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gtmccoqxbk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtqdaojpbo.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcfqtfcd.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gtampssjbh.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gtkisrksqt.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gtatnfdsit.html

[R41] 丢弃输出
来源：http://dali.9152youxi.cn/Article/details/gtdvlfhuua.html

cmd >/dev/null 2>&1
来源：http://dali.yvedp.cn/Article/details/gtcgxvifyi.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gtdpkouffk.html

wc -l < a.txt
来源：http://dali.xinyue.icu/Article/details/gtcwuisyoi.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gtpgtgpsmw.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gtmhbljrnu.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gtiomdcqdi.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtvwzmbcyp.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtpmkagqro.html

find . -name "*.tmp" -delete
来源：http://dali.0kj1m.cn/Article/details/gtykubqigb.html

[R46] 递归替换文件内容
来源：http://dali.hysaishi.cn/Article/details/gtgldcsbnq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbvjwfvy.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gtmgbpcgxp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtyaujtdna.html

[R48] awk 取指定列
来源：http://dali.yj20258888.top/Article/details/gtdterdlic.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtduyjioyj.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gtdtitemad.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigfzy.top/Article/details/gtomiabxjo.html

[R50] awk 求和
来源：http://dali.shangyingyoupin.top/Article/details/gtfmnuripq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtuzntdeic.html

[R51] 排序去重取前几
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnumgwlgb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tian-w.cn/Article/details/gtsxihvzoh.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gtzpoqhqqo.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtwvrsyhvo.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gtlcvlfrle.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gtttougjsk.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gtokjmvika.html

diff a.txt b.txt
来源：http://dali.nwbrower.top/Article/details/gtbewwswnj.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gtthxdqwsu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gtaewpavtz.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gtocxxvtnr.html

scp file user@host:/path/
来源：http://dali.pengpengdd.cyou/Article/details/gtpxbiowge.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gtzjtehomn.html

ssh user@host 'uptime'
来源：http://dali.hysaishi.cn/Article/details/gtjnzgmqjx.html

[R58] 下载文件
来源：http://dali.yj202588.top/Article/details/gtxzosbobb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gtlvhhldnl.html

[R59] 发 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtzcejuiig.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenjidiqi.icu/Article/details/gtjdknvadl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtizcrmefx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmmzcwwk.html

[R61] 磁盘占用
来源：http://dali.aizwys.cn/Article/details/gtzshlsuvb.html

df -h;  du -sh *
来源：http://dali.jinqigfzy.top/Article/details/gtkyathjus.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gtlkxpxppf.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gtokpadatb.html

[R63] 内存与进程
来源：http://dali.jlsjyb.cn/Article/details/gtrofdrasa.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gtdlaxunsq.html

[R64] 结束进程
来源：http://dali.jqgfzy.top/Article/details/gtgzyfgqfj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gtlvssppxm.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gtejeggvjw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuanmpugf.html

[R66] 定时任务
来源：http://dali.mhx1999.top/Article/details/gtyofpmxaf.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gtpgdexoxc.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gtbbkymulb.html

openssl rand -hex 16
来源：http://dali.cdnleiting.top/Article/details/gttjrvrymz.html

[R68] 计算文件校验值
来源：http://dali.chenzaomai.com/Article/details/gtxgwzpzhu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.iojbl.cn/Article/details/gtvnrosclh.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gtxlypyxel.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gtuxswodmq.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gtvqlqzfrb.html

date +%s;  date -d @1700000000
来源：http://dali.nanxuanxn.top/Article/details/gtqvrdenvd.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtzazspnrs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgufenzy.top/Article/details/gtsojzgiep.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gtnxwelrde.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtsowurbli.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtwsqjdyek.html

split -l 1000 big.log part_
来源：http://dali.hnqzz.top/Article/details/gtssbjusol.html

[R74] 批量重命名
来源：http://dali.bjfxy.top/Article/details/gtuklhmpps.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnxiangtu.top/Article/details/gtrwesqrse.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsznebwg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gtellkxgmi.html

[R76] 使用临时文件
来源：http://dali.pycfn.com/Article/details/gtcntiwgof.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaszyiqpd.html

[R77] 读取用户输入
来源：http://dali.gotoacloud.top/Article/details/gtulchkxrh.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gtalvvbxhg.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiefcpgif.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gtdnmtjjek.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gteyathllk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gtgxdufoxz.html

[R80] 查看脚本执行耗时
来源：http://dali.316326.xyz/Article/details/gtjbnrhtyn.html

time ./run.sh
来源：http://dali.yj20258.top/Article/details/gtttnmifds.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmwxeibsg.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gtwgcpwasg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlxqdlawu.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgcplmiy.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gtsdkninxg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gtxxvhktys.html

[S02] C：变量与格式化输出
来源：http://dali.ydzc1.top/Article/details/gtywtiidid.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gtocezyrvp.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gtrvvmoyqg.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjppudbk.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtjjmwfjiy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gtuaachnox.html

[S05] C：字符串长度
来源：http://dali.yj20258888.top/Article/details/gtgnaipala.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gtgnjidpfn.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtguqjgnfo.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gtxmdyywes.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtarkhhrtc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gtfmfgqzeb.html

[S08] C：动态内存分配与释放
来源：http://dali.vqdsnc.cn/Article/details/gtnhxulogv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daxiang520.top/Article/details/gtttnvmogx.html

[S09] C：结构体定义与初始化
来源：http://dali.svipenyu.cn/Article/details/gtrstmadeu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gtzokpgamz.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtfyxdxnww.html

int *p = &a;  *p = 5;
来源：http://dali.cqqwz.cn/Article/details/gtgozwmsjz.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtxzuonzuq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenjidiqi.icu/Article/details/gtxlchrmtq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtsxibnbny.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gthrtvqqkw.html

[S12] C：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtkqdjakmy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gtccozomdh.html

[S13] C：宏定义
来源：http://dali.yvedp.cn/Article/details/gtsyzdgtgn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gtqpxndwht.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtsfhuieyo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gtahrzuaho.html

[S15] C：类型转换
来源：http://dali.bjfxy.top/Article/details/gtssopglqe.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gtcykfyamo.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gtdduiicyu.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gtssozlxuy.html

[S17] C：安全拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtfmpbhksq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gtphpuxlcq.html

[S18] C：命令行参数
来源：http://dali.c1oappe.top/Article/details/gtxpsgzkcd.html

int main(int argc, char **argv)
来源：http://dali.jqgfzy.top/Article/details/gttloufhnz.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtucfoyfyn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtqumqmrzk.html

[S20] C：二分查找
来源：http://dali.dianchejie.cn/Article/details/gtxuautgvk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtoruzdghw.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gtjklwbjef.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cqqwz.cn/Article/details/gtbcoplymo.html

[S22] C：字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gtfjakkzoy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gtvtaoskpv.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gtikvupffn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gtpsswsqwt.html

[S24] C：获取本地时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpmsuctr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cheryme.top/Article/details/gtcirxwmvb.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gtaddvlssv.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gtilaionjh.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gtjexmghdo.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gtdhqcfmqd.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gtaepsuvul.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtucmrmdhl.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gtcpsnytde.html


<!-- 参考信息 -->