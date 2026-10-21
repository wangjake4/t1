代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj202588.top/Article/details/gtwzgssgij.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gtixgaslso.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtjmurrrdr.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gtcpkeomaj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtncucehna.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gtgaozlrbb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxuanxn.top/Article/details/gtjbrxhnua.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtcrihgbwn.html

[Q61] 移动平均
来源：http://dali.fengsongda.top/Article/details/gtfmwhfzas.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtidzqgbym.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gtmifvdbdh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gttuzyeulp.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gtrlorrawz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cqqwz.cn/Article/details/gtobgqligk.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gtyxsevbcp.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjicgbpsu.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gtwoajvsdk.html

ROLLBACK;
来源：http://dali.xylfe.cn/Article/details/gtbuluerbd.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gtdkhwrpnq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aibaodan.cn/Article/details/gtseqkxjdh.html

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gtpdqfhkko.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ehwqpu.com/Article/details/gtorewmkfy.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gtdquslwie.html

SAVEPOINT sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtrdqyizra.html

ROLLBACK TO sp1;
来源：http://dali.jinqigfzy.top/Article/details/gteaszrhkp.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttniouwjp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gtxlhhhkzx.html

[Q70] 更新统计信息
来源：http://dali.pengpengdd.cyou/Article/details/gtkbrhliuf.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gtaglxfnnu.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gtusacbeav.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gtscphbbuv.html

[Q72] 查看索引
来源：http://dali.zhongyouzk.top/Article/details/gtbkgtkzlr.html

SHOW INDEX FROM users;
来源：http://dali.redwolf501.top/Article/details/gtyxqqaprw.html

[Q73] 查看表状态
来源：http://dali.yj20258.top/Article/details/gtkdycchlv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gtxnmlzwuv.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gtbnwlufls.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.iojbl.cn/Article/details/gtddyhfayl.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtskyzggfp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtawcgwalo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gtvoqrrexs.html

[Q76] 按天统计
来源：http://dali.redwolf501.top/Article/details/gthhdghwmz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gtqygkxrix.html

[Q77] 时间加减
来源：http://dali.xziqi.cn/Article/details/gtkpviwekg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zycfv.cn/Article/details/gtbflathvk.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gtfdevgwxo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gtuvltbmle.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtehfvsknp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxinkj.top/Article/details/gttbncqglw.html

[Q80] 字符串截取
来源：http://dali.jlsjyb.cn/Article/details/gtycdgqltd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtmjwagqyf.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtkvtjglsj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbconfgbo.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gtashbuvzq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gttypnfpmz.html

[Q83] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtvtmsqkyq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtsisghoey.html

[Q84] 去除首尾空格
来源：http://dali.nwbrower.top/Article/details/gtgxcqazgp.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtcopctanx.html

[Q85] 数值取整
来源：http://dali.fengsongda.top/Article/details/gtevvhtwvv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuetiantiany.cn/Article/details/gtlkuexpgj.html

[Q86] 读取 JSON 字段
来源：http://dali.chenlongwang.top/Article/details/gtimpmlvar.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yvedp.cn/Article/details/gttpeortlh.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gtdwlsokmh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gtgzexiivx.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gttjfobjut.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.snrcjt.cn/Article/details/gtslcstvol.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmazqefq.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gteukukeiv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gtljgbsniy.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gtmukejeoj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gtazdvntbg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvvbesxik.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gtavatzssq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtajuiyrzq.html

[R01] shebang 与严格模式
来源：http://dali.chenlongwang.top/Article/details/gtfdvwoecv.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gtavacmzxp.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofhvcnye.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtawaronvb.html

name="Tom"; echo "$name"
来源：http://dali.wangdashe.top/Article/details/gtuazlbxwv.html

[R03] 只读变量
来源：http://dali.guannengcc.top/Article/details/gttrtzivju.html

readonly PI=3.14
来源：http://dali.jqgfzy.top/Article/details/gtranyzrjj.html

[R04] 位置参数
来源：http://dali.cashguo.top/Article/details/gteiraopdf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtqeceznpi.html

[R05] 参数默认值
来源：http://dali.cqqwz.cn/Article/details/gtigbzdgrv.html

name="${1:-default}"
来源：http://dali.dianchejie.cn/Article/details/gtrlqjnegi.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gteqekfvgu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtwketxrlj.html

[R07] if 判断文件
来源：http://dali.sxryk.cn/Article/details/gtwvqwmepj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtqkddshsw.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gtxotdualt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gtawqjahpb.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtprxminsb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gtjcdlggdb.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gtcbcwiyvs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ehwqpu.com/Article/details/gtilxpdhuj.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gtzepwtwos.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gtcvattcex.html

start) echo "启动" ;;
来源：http://dali.sweek.top/Article/details/gtzpbiowrw.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtbrfuzxem.html

*)     echo "未知命令" ;;
来源：http://dali.ehwqpu.com/Article/details/gtlwresacu.html

esac
来源：http://dali.cucudq.cn/Article/details/gtaqfkthwy.html

[R12] for 遍历文件
来源：http://dali.andypj.xyz/Article/details/gtmkheonla.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigfzy.top/Article/details/gtppsiaarw.html

[R13] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjorqtymu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtpuvuqvor.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gteizfdrih.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtcifpxshg.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtrdgzqfvb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gtgbmdsqrs.html

[R16] until 等待条件
来源：http://dali.zhixingplan.top/Article/details/gtgskqraxm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtektzdylt.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gttxwylhbs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gthzdztbrh.html

[R18] 遍历数组
来源：http://dali.haohaochexian.top/Article/details/gtndbnzfxg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenzaomai.com/Article/details/gticzhlgtc.html

[R19] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gtrhdalocx.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gtnkimtfvl.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gtfamziqaf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gtzptfvfxb.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtroikuzsc.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gtuzodoxjh.html

[R22] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtjksumgwi.html

echo "${s:0:5}"
来源：http://dali.jinqigfzy.top/Article/details/gtmcbfgqww.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtglkrdyyg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.bjfxy.top/Article/details/gtgtajktdz.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtftxusone.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daxiang520.top/Article/details/gtequruhsn.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenjidiqi.icu/Article/details/gtbexdzrmk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gtollzohwj.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtnmxxavgw.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gtlqvmryuu.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtrfxwgldw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gtfmqhbdgk.html

[R28] 浮点运算
来源：http://dali.jianghu66.top/Article/details/gtnttuusmh.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gtnxxikrui.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtlgladnvp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xylfe.cn/Article/details/gtmoibnuns.html

[R30] 函数返回状态码
来源：http://dali.zhixingplan.top/Article/details/gtvtpszflq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gthdkxaaln.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbfwuxgs.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gtrxrggulp.html

[R32] 参数个数校验
来源：http://dali.aizwys.cn/Article/details/gtzqeuotgu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtqrwxeqzt.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gtbzonhfbj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gtquksroho.html

[R34] 退出时清理
来源：http://dali.yuanzhike.top/Article/details/gtrsvctqln.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gteevyeojd.html

[R35] 后台执行并等待
来源：http://dali.zdqjudy.top/Article/details/gtbcybwuoc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gtanuhljtf.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gtqudwfdph.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hfpthk.cn/Article/details/gtdmcqvfbg.html

[R37] 把输出赋给变量
来源：http://dali.tianlin.xyz/Article/details/gtiwrtnngf.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfvxrszx.html

[R38] 管道串联
来源：http://dali.c1oappe.top/Article/details/gtdacpfner.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gtsfeapfzc.html

[R39] 重定向标准输出与错误
来源：http://dali.wangshuangyany.cn/Article/details/gtmlgbqbne.html

cmd > out.log 2>&1
来源：http://dali.daxiang520.top/Article/details/gtszhkgmdc.html

[R40] 追加写日志
来源：http://dali.zdqjudy.top/Article/details/gtecyshnkq.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gtljvgskgu.html

[R41] 丢弃输出
来源：http://dali.ybcxt.top/Article/details/gtzeyaeeyv.html

cmd >/dev/null 2>&1
来源：http://dali.daria6918.cn/Article/details/gtxiqxcrdl.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gtgdctgdrw.html

wc -l < a.txt
来源：http://dali.zdqjudy.top/Article/details/gtrktkmzsz.html

[R43] 按名字查找文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghdijiog.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gtxychhepl.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gtzgksmpjd.html

find . -mtime -7 -type f
来源：http://dali.xinyue.icu/Article/details/gtqfqifrei.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gtbfcawawb.html

find . -name "*.tmp" -delete
来源：http://dali.chenlongwang.top/Article/details/gtzuqsluhn.html

[R46] 递归替换文件内容
来源：http://dali.shuidangran.top/Article/details/gtajfddwwb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gtnjbnllrn.html

[R47] sed 单行替换
来源：http://dali.aibaodan.cn/Article/details/gtchatfayh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xylfe.cn/Article/details/gteeqsdwso.html

[R48] awk 取指定列
来源：http://dali.ivvv.top/Article/details/gtolbtrtec.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gtiorqluao.html

[R49] awk 带条件
来源：http://dali.daxiang520.top/Article/details/gtgdjjpdye.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gtqjzxsrho.html

[R50] awk 求和
来源：http://dali.dianchejie.cn/Article/details/gtcwozjlzl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofcelilc.html

[R51] 排序去重取前几
来源：http://dali.sysykeji.top/Article/details/gtexbewpnm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gthufmwrat.html

[R52] 统计行数
来源：http://dali.cashguo.top/Article/details/gtmlbwcdxz.html

wc -l a.txt
来源：http://dali.tanke756.top/Article/details/gtnakwxrjz.html

[R53] 查看文件头与实时尾
来源：http://dali.feifeiyinyue.top/Article/details/gtqkplcdaa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gtrxwwodcw.html

[R54] 比较两个文件
来源：http://dali.wangshuangyany.cn/Article/details/gtdefihkpr.html

diff a.txt b.txt
来源：http://dali.nwbrower.top/Article/details/gtbubxcjry.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gttlehhbvg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gtprxmaayn.html

[R56] 远程拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtwurzzqpy.html

scp file user@host:/path/
来源：http://dali.gogol.net.cn/Article/details/gtnnmjtkeq.html

[R57] 远程执行命令
来源：http://dali.zhengqikj.top/Article/details/gtwnxvxxzx.html

ssh user@host 'uptime'
来源：http://dali.feifeiyinyue.top/Article/details/gtfozwhabn.html

[R58] 下载文件
来源：http://dali.chenzaomai.com/Article/details/gtzqshvfaf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gtgmtbhsmo.html

[R59] 发 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtwzsqagxw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjumdpxzg.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtlycmfjqc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gtlxhmaqgj.html

[R61] 磁盘占用
来源：http://dali.shangyingyoupin.top/Article/details/gtnufhkigl.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gtcjxferew.html

[R62] 找最占空间的文件
来源：http://dali.guowangkeji.top/Article/details/gtrizidthq.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gtcnlycizx.html

[R63] 内存与进程
来源：http://dali.yuanzhike.top/Article/details/gtqxiiathi.html

free -h;  ps aux | grep nginx
来源：http://dali.dianchejie.cn/Article/details/gtxcipkmom.html

[R64] 结束进程
来源：http://dali.hammf.cn/Article/details/gtrcpkqioa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnwdgbkj.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtkvbviuzr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gtkuecvqzn.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gtcvtjghef.html

crontab -e;  crontab -l
来源：http://dali.guowangkeji.top/Article/details/gtbeuqiusv.html

[R67] 生成随机十六进制串
来源：http://dali.yuanzhike.top/Article/details/gtbjdrqfgj.html

openssl rand -hex 16
来源：http://dali.havefunace.top/Article/details/gtlwljbcfo.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gtnszxcntu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtkljlczxz.html

[R69] 生成随机密码
来源：http://dali.hongshengwenyu.top/Article/details/gtyndgalyz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zdqjudy.top/Article/details/gtvimcnajy.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmymjuxjo.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gttgxhtndw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtzvipnqfs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gtoslsvkaj.html

[R72] 等待端口就绪
来源：http://dali.pengpengdd.cyou/Article/details/gtjpecxihm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gtnxmqwnao.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gtupzqskif.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gtqdprraql.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gtdfanehtr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258.top/Article/details/gtnftzkmcv.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrvxqrcp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtpztkrsio.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gtjihxemdt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gteymxwoez.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gtrpdjewvc.html

read -rp "请输入: " ans
来源：http://dali.yueranfly.top/Article/details/gtupdcjyaj.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gttiwywlpw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tian-w.cn/Article/details/gtvplxwvxp.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gtumxoqkrl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhongyouzk.top/Article/details/gtueoxkwkc.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gtpyfeilsn.html

time ./run.sh
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdkdmuei.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtccxmsnyd.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gtlktonpfv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqgzjvzvj.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gtlghhffbj.html

#include <stdio.h>
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnmblyfe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.snrcjt.cn/Article/details/gtnvcthnhh.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gtwmklikcg.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtvryxylqd.html

[S03] C：读入整数
来源：http://dali.ivvv.top/Article/details/gturnrlufn.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gtbnuzjqep.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gttjtifsgi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gtozmtzjxw.html

[S05] C：字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtehnvxxte.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gtpykxcewm.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtojtidkaz.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gtvodkvqqu.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtihmzxpaa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gtwwyoqkte.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gtdtvhqwjp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gtkducfybc.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gtffiwmiyu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gtfqahmxhg.html

[S10] C：指针与解引用
来源：http://dali.sxryk.cn/Article/details/gtduuehkzb.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gtfiujyojo.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtpoqdqood.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gtlfrxndlf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sxryk.cn/Article/details/gtnnurwpgs.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtxhzkhari.html

[S12] C：写文件
来源：http://dali.c1oappe.top/Article/details/gtegtnests.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtgeablhea.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gtxyuoxctt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gtyrtqoyrm.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gtfcpqgcap.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jlsjyb.cn/Article/details/gtcvxkjrjz.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gtogvjrptt.html

(double) a / b
来源：http://dali.chenzaomai.com/Article/details/gtmhkqieqz.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gttpcscbnn.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gtfzxfxrdm.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtszexwvla.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gtkxyqpwyt.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfplcgdbi.html

int main(int argc, char **argv)
来源：http://dali.wangdashe.top/Article/details/gtnticmrld.html

[S19] C：快速排序
来源：http://dali.hnqzz.top/Article/details/gtoysofokt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gtogtnayan.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gtaultstpf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtpblblrfp.html

[S21] C：字符类别判断
来源：http://dali.yuanzhike.top/Article/details/gtftkynobi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gtcbkixhkq.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtfrvojtxi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.bjfxy.top/Article/details/gtaxzlccri.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gtuaowqimt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gtlmtrknso.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gtgiobejxl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gtygyleriq.html

[S25] C：内存拷贝
来源：http://dali.hfpthk.cn/Article/details/gtzpfemwrg.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gtpnnlbuht.html

[S26] C：内存清零
来源：http://dali.quarkkingdee.top/Article/details/gtmylrnuko.html

memset(a, 0, sizeof a);
来源：http://dali.dashuyun.cn/Article/details/gttlczuniz.html

[S27] C：定义常量
来源：http://dali.hnqzz.top/Article/details/gtepduwvzd.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gttlcltsbr.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gtylpaeovg.html


<!-- 参考信息 -->