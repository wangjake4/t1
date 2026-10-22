代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gtmbqhelxw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gtkdmwatpv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gttjwulbrm.html

[Q57] 行号
来源：http://dali.iojbl.cn/Article/details/gtgmlmvpay.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtzqfytrdu.html

[Q58] 累计求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhhalfqk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gttnozircq.html

[Q59] 分组内累计
来源：http://dali.hysaishi.cn/Article/details/gtmacdpswd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtchtuwsjq.html

[Q60] 取上一行 / 下一行
来源：http://dali.dianchejie.cn/Article/details/gtfbndjzyr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gtkumgocgx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtzylymijt.html

[Q61] 移动平均
来源：http://dali.daria6918.cn/Article/details/gtarmrtdkq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtsxhjmfwq.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gtahmplmsh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtemnsfwla.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gttzpywpue.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xylfe.cn/Article/details/gtkflxezkv.html

[Q64] 提交事务
来源：http://dali.birdmap.top/Article/details/gtkwemfioh.html

COMMIT;
来源：http://dali.gaohongyu789.top/Article/details/gtikbcnydh.html

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptdeumuq.html

ROLLBACK;
来源：http://dali.dashuyun.cn/Article/details/gtkqvyiufi.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gtksdyvrta.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.316326.xyz/Article/details/gtwlcpflpp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gtzrunmfsr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gthhhvsmrw.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gtknnyxrns.html

SAVEPOINT sp1;
来源：http://dali.9152youxi.cn/Article/details/gtcnllnplo.html

ROLLBACK TO sp1;
来源：http://dali.xinyue.icu/Article/details/gtbszphrvr.html

[Q69] 查看执行计划
来源：http://dali.guowangkeji.top/Article/details/gtwkxsgfsy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jlsjyb.cn/Article/details/gtriqslltz.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvjcufoe.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gtbswnvqew.html

[Q71] 查看建表语句
来源：http://dali.jlsjyb.cn/Article/details/gtwpotckke.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tian-w.cn/Article/details/gttlddtenq.html

[Q72] 查看索引
来源：http://dali.nanxuanxn.top/Article/details/gtohdmfzkk.html

SHOW INDEX FROM users;
来源：http://dali.jyoumei.cn/Article/details/gteynpdlsb.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gtyavvyzfn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yonumen.top/Article/details/gtzekerfet.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gtalrjwzbb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gtybilrkvz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtyvubaagc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtcocwijpb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfycrwhdm.html

[Q76] 按天统计
来源：http://dali.yangfankeji.com/Article/details/gtsvrrywuq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gtchdugsch.html

[Q77] 时间加减
来源：http://dali.sxryk.cn/Article/details/gtcbqqelqi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gtpnrlpann.html

[Q78] 当前时间
来源：http://dali.shuidangran.top/Article/details/gtdaaqrgee.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sysykeji.top/Article/details/gtqddkescx.html

[Q79] 字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtaaujgskn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hongshengwenyu.top/Article/details/gtvllmqkqx.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gtdmxuzbgi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtcchtgkmj.html

[Q81] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtdrsaeged.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvtzwtab.html

[Q82] 字符长度与字节长度
来源：http://dali.hywenlv.cn/Article/details/gtwonesztw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtfjeonwba.html

[Q83] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtkpsayfji.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtgbszbgvk.html

[Q84] 去除首尾空格
来源：http://dali.chenjidiqi.icu/Article/details/gtcrgwszvr.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtfmrdstkv.html

[Q85] 数值取整
来源：http://dali.yanxiufei.cn/Article/details/gtajjytkzl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gttkpopbfi.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gtpghxdtfr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gtdxysltfc.html

[Q87] JSON 字段做条件
来源：http://dali.yonumen.top/Article/details/gtwikktuhf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gthzxxgutr.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmxioobf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangshuangyany.cn/Article/details/gtymkvwqqg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtystfgmdg.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gtwofctefo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xziqi.cn/Article/details/gtoygzrriq.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gtawjnpsdv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtojzwkehf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtkkkrkbxa.html

R. Bash 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtmddmfnzc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtadmrdzef.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gteefeehky.html

#!/usr/bin/env bash
来源：http://dali.havefunace.top/Article/details/gtviroxeiw.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gtsclomzrx.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gtgbqjskjy.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gthkxqvhox.html

[R03] 只读变量
来源：http://dali.aibaodan.cn/Article/details/gttsflldja.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtejfhvwbp.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gtkigdegza.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gtfecwtupb.html

[R05] 参数默认值
来源：http://dali.hnqzz.top/Article/details/gtsizsqusd.html

name="${1:-default}"
来源：http://dali.wangdashe.top/Article/details/gtjnrjihdi.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gtsoogkfut.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtoyuspech.html

[R07] if 判断文件
来源：http://dali.hongshengwenyu.top/Article/details/gtqbkihqvk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shzxlz.cn/Article/details/gtbmggnfci.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtzxdqrabn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sweek.top/Article/details/gtsqkxflxi.html

[R09] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtytixhznh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtlrlicvoh.html

[R10] 正则匹配
来源：http://dali.dianchejie.cn/Article/details/gtsqtaddvk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhengqikj.top/Article/details/gtwvwpasnd.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gtyzufpmct.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gtemykjqfk.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtlqxihpxg.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtoxqackic.html

*)     echo "未知命令" ;;
来源：http://dali.daria6918.cn/Article/details/gtwujbryjj.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gtsnhliaio.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gtdjzpkxec.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gogol.net.cn/Article/details/gtgzedytgs.html

[R13] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtobddopwc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gterhasydh.html

[R14] C 风格 for
来源：http://dali.chenjidiqi.icu/Article/details/gtrkekmyuj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gteprjrlgh.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gthtwoymft.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtskydgpxo.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gtzqacueoo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwaleypt.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gtcrrvrwuu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gtwlknbuzm.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdybrhhzc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gtxlwxytfm.html

[R19] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gthlnroevt.html

echo "${#arr[@]}"
来源：http://dali.jinqigfzy.top/Article/details/gthipsflqx.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gtynsqwntz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hysaishi.cn/Article/details/gtnbtbzrhl.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gtzxdfryat.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gtcmlqdwbu.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtogwfwksk.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gtolfqgqmh.html

[R23] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtrfuagxme.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gtyrhkghwe.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtxokfnahw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtpuiudkyh.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gtivibuqfg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guowangkeji.top/Article/details/gtclluiguk.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtknjphoea.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gtvjdflmld.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gtbsnovggj.html

echo $((1 + 2 * 3))
来源：http://dali.jlsjyb.cn/Article/details/gtubsedrdv.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gtxpcwynml.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gtowcogrwf.html

[R29] 定义函数
来源：http://dali.yonumen.top/Article/details/gtaaphwfle.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhongyouzk.top/Article/details/gtktspwual.html

[R30] 函数返回状态码
来源：http://dali.gogol.net.cn/Article/details/gtfspejspg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gtwxsgnorc.html

[R31] 局部变量
来源：http://dali.havefunace.top/Article/details/gtuolxhzfx.html

f() { local x=1; echo "$x"; }
来源：http://dali.guowangkeji.top/Article/details/gtcucttwnv.html

[R32] 参数个数校验
来源：http://dali.xziqi.cn/Article/details/gtojptufsm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtvyjhryrm.html

[R33] 捕获错误并提示行号
来源：http://dali.haohaochexian.top/Article/details/gtvokicssh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.c1oappe.top/Article/details/gtsrveafov.html

[R34] 退出时清理
来源：http://dali.zhiwuduotai.top/Article/details/gtlwigdooh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbptsiujh.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gtpdqnqgik.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.smart0.xyz/Article/details/gtjxcapiyr.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gtrzlfzdhg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cqqwz.cn/Article/details/gtuwypoxer.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhqpfcaz.html

files=$(ls -1)
来源：http://dali.chenzaomai.com/Article/details/gtxgvnfazk.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwfheqjb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gtaazvujfs.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gtqwktwwdk.html

cmd > out.log 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtqjzhuuym.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gtcwbkxgie.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gtbjbkrstk.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtwiqpnkdq.html

cmd >/dev/null 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtrjdqjctd.html

[R42] 输入重定向
来源：http://dali.jyoumei.cn/Article/details/gtcxsjrqrk.html

wc -l < a.txt
来源：http://dali.yueranfly.top/Article/details/gtllbxynem.html

[R43] 按名字查找文件
来源：http://dali.smart0.xyz/Article/details/gtwzrwxzkw.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gtcifczcxm.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gthcwmeqrf.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtrcihhumm.html

[R45] 批量删除
来源：http://dali.hfpthk.cn/Article/details/gtojbpsqti.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gtyjodvzta.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gtnkcfcdah.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gtzohybknl.html

[R47] sed 单行替换
来源：http://dali.cheryme.top/Article/details/gtesqidgyk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtlbnyllol.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtjzhswtff.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtnatipwha.html

[R49] awk 带条件
来源：http://dali.cheryme.top/Article/details/gtzqnqaahd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zdqjudy.top/Article/details/gtqzkrorzh.html

[R50] awk 求和
来源：http://dali.jiagoushi.top/Article/details/gturhtpimt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfrxlyrn.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gtvarwlcyo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gtjrcnqjaq.html

[R52] 统计行数
来源：http://dali.xuetiantiany.cn/Article/details/gtpjifpkqs.html

wc -l a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuqdscmq.html

[R53] 查看文件头与实时尾
来源：http://dali.pycfn.com/Article/details/gtwkmjhmet.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.smart0.xyz/Article/details/gtotahxfza.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gtwvegtwjl.html

diff a.txt b.txt
来源：http://dali.dashuyun.cn/Article/details/gtkwzvhusa.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gtmertkndl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.0kj1m.cn/Article/details/gtibcdxugu.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gtuunvhmrk.html

scp file user@host:/path/
来源：http://dali.zdqjudy.top/Article/details/gtqvpyvofv.html

[R57] 远程执行命令
来源：http://dali.zhixingplan.top/Article/details/gtylebnmtp.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gtubcwuhkd.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gtvyayffrf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yonumen.top/Article/details/gtmdovkoqc.html

[R59] 发 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtpvboafhv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jlsjyb.cn/Article/details/gthjqchcms.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtmibkfaqs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cqqwz.cn/Article/details/gtggfaocxf.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gtapnotipk.html

df -h;  du -sh *
来源：http://dali.cucudq.cn/Article/details/gtoeehcavq.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gtezjmnzqb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhongyouzk.top/Article/details/gtejzjxsjd.html

[R63] 内存与进程
来源：http://dali.mhx1999.top/Article/details/gtmmwsafcu.html

free -h;  ps aux | grep nginx
来源：http://dali.daxiang520.top/Article/details/gtmjwsqzdl.html

[R64] 结束进程
来源：http://dali.dashuyun.cn/Article/details/gtufwbyvuv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhiwuduotai.top/Article/details/gtosizamko.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gtcgrkyenx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cheryme.top/Article/details/gtkngrxdyr.html

[R66] 定时任务
来源：http://dali.yj202588.top/Article/details/gtrjbnnpnz.html

crontab -e;  crontab -l
来源：http://dali.dashuyun.cn/Article/details/gtecbkajyg.html

[R67] 生成随机十六进制串
来源：http://dali.xylfe.cn/Article/details/gtymehlcll.html

openssl rand -hex 16
来源：http://dali.chenjidiqi.icu/Article/details/gtskwaldwt.html

[R68] 计算文件校验值
来源：http://dali.vqdsnc.cn/Article/details/gtgjefrjux.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aizwys.cn/Article/details/gtuoxyzdad.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdroagqz.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gtcrxznvee.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohgayafq.html

date +%s;  date -d @1700000000
来源：http://dali.zhixingplan.top/Article/details/gtvjelciat.html

[R71] 日期格式化
来源：http://dali.yonumen.top/Article/details/gtgjofveoa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jyoumei.cn/Article/details/gtosdptdhm.html

[R72] 等待端口就绪
来源：http://dali.c1oappe.top/Article/details/gtsgsmzgvt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtjuffzbwp.html

[R73] 分割大日志
来源：http://dali.birdmap.top/Article/details/gtbqphtmcz.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gtrcoktizg.html

[R74] 批量重命名
来源：http://dali.yj20258888.top/Article/details/gtlwbxgunx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyewmjwh.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gthxbtezji.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytpqeyhb.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gtunvqgmwh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtmjstkqbs.html

[R77] 读取用户输入
来源：http://dali.nanxinkj.top/Article/details/gtwofdgmdt.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gtrzsusdco.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gtcnbatnkf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gtsgkuhrdq.html

[R79] 解析命令行选项
来源：http://dali.mhx1999.top/Article/details/gtuarvamuc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gtpmhqrhsb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhiwuduotai.top/Article/details/gtrflojhef.html

time ./run.sh
来源：http://dali.cdnleiting.top/Article/details/gtujbyzxpe.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtbekmwngh.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjcmbtcg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gteqptxxxc.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gtpftvokyg.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gtawgzisuc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gtuykkmqzm.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gtybltpria.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtutpkcvff.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gthxgfefrq.html

int x; scanf("%d", &x);
来源：http://dali.sweek.top/Article/details/gtdjlbtrgq.html

[S04] C：字符串复制
来源：http://dali.zhixingplan.top/Article/details/gtjscaanvt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gtvkuauaze.html

[S05] C：字符串长度
来源：http://dali.yj202588.top/Article/details/gtrtnzolbs.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gtkbmhoglt.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtesxpnwlb.html

strcmp(a, b) == 0
来源：http://dali.fzhhl.top/Article/details/gtvijbigss.html

[S07] C：数组遍历求和
来源：http://dali.zdqjudy.top/Article/details/gtvamxgxjs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cqqwz.cn/Article/details/gtbnxuohpe.html

[S08] C：动态内存分配与释放
来源：http://dali.smart0.xyz/Article/details/gtajxhhnwy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gtugfwcszr.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gtiahtloin.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtrnimsqvs.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gtvqnfttps.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gtofzecbdw.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtmmlubkqr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gtsydadvfa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtblrqilqx.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gtrwjyuksc.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gtuievslzz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtnggedmfs.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gtcufxlacz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gtrbicjqbn.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gtxwgxdicx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gtimupebfi.html

[S15] C：类型转换
来源：http://dali.gogol.net.cn/Article/details/gtrcdfnqhp.html

(double) a / b
来源：http://dali.aizwys.cn/Article/details/gtdroovmoc.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gtzgazhwfv.html

x |= (1 << 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtuebobnfq.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtyztuepfu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gtnjiiwtvr.html

[S18] C：命令行参数
来源：http://dali.redwolf501.top/Article/details/gtsonsaboc.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gtsplhctnr.html

[S19] C：快速排序
来源：http://dali.nanxinkj.top/Article/details/gthexdphwt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtrdphdlbo.html

[S20] C：二分查找
来源：http://dali.nwbrower.top/Article/details/gtxwhllkan.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtakaibjev.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gtxstiqodl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gtlkgugzix.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtmnjmgynp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gtnznilrqu.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gtwcurbuxr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.9152youxi.cn/Article/details/gtnkjwoyzt.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gtbjumppmy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gtgagorgvj.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtourozrwg.html

memcpy(dst, src, n);
来源：http://dali.zycfv.cn/Article/details/gtilmridzc.html

[S26] C：内存清零
来源：http://dali.andypj.xyz/Article/details/gtxetekyyk.html


<!-- 参考信息 -->