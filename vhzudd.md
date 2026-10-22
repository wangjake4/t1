代发 wailian999

[Q61] 移动平均
来源：http://dali.nanxinkj.top/Article/details/gtkfwjcgho.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtcahixidm.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gtgwldaboq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtnihhdymr.html

[Q63] 开启事务
来源：http://dali.yvedp.cn/Article/details/gtsppdartc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258.top/Article/details/gtgdcxevgl.html

[Q64] 提交事务
来源：http://dali.hfpthk.cn/Article/details/gtmlpfyyuk.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gtmkjmxmaa.html

[Q65] 回滚事务
来源：http://dali.cheryme.top/Article/details/gtjsaflfmq.html

ROLLBACK;
来源：http://dali.zhiwuduotai.top/Article/details/gtajzgzmyb.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtdidnnjxw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gtpqiccqdi.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gtjkihtrlq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gtdzczngeg.html

[Q68] 保存点
来源：http://dali.gogol.net.cn/Article/details/gtiqbavlnc.html

SAVEPOINT sp1;
来源：http://dali.yueranfly.top/Article/details/gtgiphbvpv.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gtmokufpxr.html

[Q69] 查看执行计划
来源：http://dali.guannengcc.top/Article/details/gttidgwqez.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gthhdyavdm.html

[Q70] 更新统计信息
来源：http://dali.xuetiantiany.cn/Article/details/gttuwmtbyo.html

ANALYZE TABLE users;
来源：http://dali.fengsongda.top/Article/details/gtycxnvokn.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjeilgiiz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gtuxaibywz.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gtlkcagdwg.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyejkvuhu.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtqmwxkrxn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gtjiryomgz.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gtxqwmbxzh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.9152youxi.cn/Article/details/gtrslvxyiv.html

[Q75] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtzvudmlwv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.meibo888.top/Article/details/gtuoskbonu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pycfn.com/Article/details/gtdxidxtmd.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gtwpknbtrm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gtenutwudo.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gtzastrznl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gtkzylyvdf.html

[Q78] 当前时间
来源：http://dali.sufxvd.cn/Article/details/gtrmbtpseh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gtlkaollan.html

[Q79] 字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtkjayexkl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gtkjsdohae.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkznmfujn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtftpcifdy.html

[Q81] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gtdomtwmuy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtjnkdunth.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgfzy.top/Article/details/gtfjhmiasj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtpicneqte.html

[Q83] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtnqqobbfh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtuwkdqxvf.html

[Q84] 去除首尾空格
来源：http://dali.guowangkeji.top/Article/details/gttrvzwmie.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtteefjabr.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gtgeqirjaa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gtiwldgrba.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gtwookmcmz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.mhx1999.top/Article/details/gtuqfcoekk.html

[Q87] JSON 字段做条件
来源：http://dali.redwolf501.top/Article/details/gtojqomdkg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pycfn.com/Article/details/gtrpwdzgpf.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gtgjopisdr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gtyftptjuo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqkshsrt.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gtploiygty.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.redwolf501.top/Article/details/gtpclnmjsg.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gtjyskvujc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gtdsuphell.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqvcgblca.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gtosbgstil.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtuqxcvoqj.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gtyjbcevic.html

#!/usr/bin/env bash
来源：http://dali.jiagoushi.top/Article/details/gtcxlypyea.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gtbyugszvx.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gtqlbwewnm.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxzjkwpk.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gtwlrsjwce.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gtjlncaijd.html

[R04] 位置参数
来源：http://dali.ivvv.top/Article/details/gtoozdjybg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.svipenyu.cn/Article/details/gtawbalxtb.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gtnepdcpwa.html

name="${1:-default}"
来源：http://dali.jianghu66.top/Article/details/gthecfnyew.html

[R06] 判断命令是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtbhkxcqod.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtndxmrsua.html

[R07] if 判断文件
来源：http://dali.dashuyun.cn/Article/details/gtqzkiphmo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gtpvrbeyhr.html

[R08] 数值比较
来源：http://dali.dianchejie.cn/Article/details/gtmvqvgsxg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xinyue.icu/Article/details/gtmbdlfztg.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gttfgwxqml.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gtjvzjvjos.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gtbjbfdgpj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gtfijmwrwb.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gtuosxgrac.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gtfqtxgehj.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtzpzbxihb.html

stop)  echo "停止" ;;
来源：http://dali.redwolf501.top/Article/details/gtdgxgiioz.html

*)     echo "未知命令" ;;
来源：http://dali.dashuyun.cn/Article/details/gtftvrxvgy.html

esac
来源：http://dali.jinqigufen.top/Article/details/gtsnohscbk.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gtwsgenniy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gtmkjjhwac.html

[R13] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gtggissfau.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtkrpgksps.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gtzhztrixf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtbmwxrskm.html

[R15] while 逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtdtufhvlu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dianchejie.cn/Article/details/gtqkdyfgsz.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gtyknxkgti.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtwztgfqvt.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gtifclwvzk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gtuldxfjvf.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gtpvukkugv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guannengcc.top/Article/details/gtkwxezfys.html

[R19] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtqomkdxzv.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gtradkiqgx.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gthphkparl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hysaishi.cn/Article/details/gtbssjftkq.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gtzoqaqraa.html

echo "${#s}"
来源：http://dali.yuanzhike.top/Article/details/gtsvdymueg.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtoexnwhva.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gtdwmscuku.html

[R23] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gtjafkdkkq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gtawhvwwsz.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtwbbczcac.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gtgkxrnmwe.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gtvepdczvf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gtycjgxevp.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gtqlwhuwcs.html

now=$(date +%F); echo "$now"
来源：http://dali.chenjidiqi.icu/Article/details/gtwwzgsghh.html

[R27] 算术展开
来源：http://dali.vqdsnc.cn/Article/details/gtbzkuqihq.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gtnfssmytj.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gtdrpgscmf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytftojhw.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gthrsgttpb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gtxmhczpya.html

[R30] 函数返回状态码
来源：http://dali.tian-w.cn/Article/details/gtifsbbmgb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbsjdvtg.html

[R31] 局部变量
来源：http://dali.316326.xyz/Article/details/gtgshijdud.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gthzrcmhdp.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgziidyrp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtleagfoml.html

[R33] 捕获错误并提示行号
来源：http://dali.zycfv.cn/Article/details/gtadskhwqj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgllkbgw.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gtxbdjlcnz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtugpvucnl.html

[R35] 后台执行并等待
来源：http://dali.0kj1m.cn/Article/details/gtqxtpiyrc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ehwqpu.com/Article/details/gtalztlfex.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gtweqcdnws.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sweek.top/Article/details/gtemhjaqdm.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gtpuzzyecr.html

files=$(ls -1)
来源：http://dali.yuanzhike.top/Article/details/gtiidulgue.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gtkbflqism.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gtldeukbet.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gtyhpfutqm.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gtspmblasl.html

[R40] 追加写日志
来源：http://dali.kuanghao11.cn/Article/details/gtzafakavf.html

echo "log" >> out.log
来源：http://dali.jianghu66.top/Article/details/gtcrtazxxa.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gtbcgoamlf.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtwvlkhhxs.html

[R42] 输入重定向
来源：http://dali.zhoulong.xyz/Article/details/gtixtyquzs.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gtrnhqgecn.html

[R43] 按名字查找文件
来源：http://dali.cashguo.top/Article/details/gtkajrjtmj.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gtlkvxnsnk.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gttponbcyv.html

find . -mtime -7 -type f
来源：http://dali.xuanzx.com/Article/details/gtlpgrgcty.html

[R45] 批量删除
来源：http://dali.yj20258.top/Article/details/gtppvvrcpw.html

find . -name "*.tmp" -delete
来源：http://dali.vqdsnc.cn/Article/details/gtjohqoevl.html

[R46] 递归替换文件内容
来源：http://dali.jianghu66.top/Article/details/gtqloklspw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxtklrmt.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gtmlbccpud.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtkxtrvhka.html

[R48] awk 取指定列
来源：http://dali.redwolf501.top/Article/details/gtaxaqedvo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtrplneuwr.html

[R49] awk 带条件
来源：http://dali.bjfxy.top/Article/details/gthciebsxl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gtfszhdhig.html

[R50] awk 求和
来源：http://dali.daria6918.cn/Article/details/gtymvhbehe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtrkyymjot.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gtisonmbpq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gtcsqrrari.html

[R52] 统计行数
来源：http://dali.daxiang520.top/Article/details/gtzbqepkkx.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gtzjrexmue.html

[R53] 查看文件头与实时尾
来源：http://dali.jyoumei.cn/Article/details/gtgyahrejc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nwbrower.top/Article/details/gtjklunxxg.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gtaovnqtvp.html

diff a.txt b.txt
来源：http://dali.hywenlv.cn/Article/details/gtzhmbceuk.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gturoahhlj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgfzy.top/Article/details/gtmicntntg.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtwrbsjnve.html

scp file user@host:/path/
来源：http://dali.xuetiantiany.cn/Article/details/gtqyuasxpw.html

[R57] 远程执行命令
来源：http://dali.dashuyun.cn/Article/details/gtpdlbmsyc.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gtfglxiwoa.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gtgqrasluw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gtbmeujamq.html

[R59] 发 POST JSON
来源：http://dali.mhx1999.top/Article/details/gtvgikwwtt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jlsjyb.cn/Article/details/gtllunkyxd.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gtlmsipjfk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenjidiqi.icu/Article/details/gtdxdoxybo.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gtgfraghdi.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtphraajwp.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gtednasbzg.html

du -ah . | sort -rh | head -10
来源：http://dali.jianghu66.top/Article/details/gtsgsszupx.html

[R63] 内存与进程
来源：http://dali.bjfxy.top/Article/details/gtwgrulzpv.html

free -h;  ps aux | grep nginx
来源：http://dali.dianchejie.cn/Article/details/gtsyjckcfi.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gtmjvgtidr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.redwolf501.top/Article/details/gtshejwvnu.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gtzirsuztg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xinyue.icu/Article/details/gtkifqaban.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtqvgbiaei.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gtnoihuvdk.html

[R67] 生成随机十六进制串
来源：http://dali.guannengcc.top/Article/details/gtbfsekhww.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gttobiuzkl.html

[R68] 计算文件校验值
来源：http://dali.cdnleiting.top/Article/details/gtcuavpgsh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.316326.xyz/Article/details/gtmilzwisj.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gtjgdyxjou.html

head -c 16 /dev/urandom | base64
来源：http://dali.shangyingyoupin.top/Article/details/gtsymrgxre.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtbjombxld.html

date +%s;  date -d @1700000000
来源：http://dali.quarkkingdee.top/Article/details/gtnwvexlzx.html

[R71] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtqrubhtcm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gtgjpwdmyl.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gtmwzzfbmz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gtpowjqyvv.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gtsgvedytk.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gtohyanufg.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gtcsxakvhv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gtwsqtghwf.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtwhynbtgp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hammf.cn/Article/details/gtjxvhorrk.html

[R76] 使用临时文件
来源：http://dali.hnqzz.top/Article/details/gtulinadmx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtrpkilkrq.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gthrhyzhhg.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gtvxzmbfev.html

[R78] 交互式菜单
来源：http://dali.meibo888.top/Article/details/gtpdosbliv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gtlouyumqd.html

[R79] 解析命令行选项
来源：http://dali.feifeiyinyue.top/Article/details/gtyxzqjfkr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gtiblzgzbs.html

[R80] 查看脚本执行耗时
来源：http://dali.aizwys.cn/Article/details/gtilcwozpk.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gtpkjpumyy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkqrmtzuh.html

S. C / C++ 专题
来源：http://dali.gogol.net.cn/Article/details/gtvaldefci.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gthymvhjim.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gtulyllvfk.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtccxgsnfx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gtdporbvci.html

[S02] C：变量与格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgsbbktr.html

int a = 10; printf("%d\n", a);
来源：http://dali.xylfe.cn/Article/details/gttmxbliqk.html

[S03] C：读入整数
来源：http://dali.shuidangran.top/Article/details/gtoayenruy.html

int x; scanf("%d", &x);
来源：http://dali.dashuyun.cn/Article/details/gtosrhkvul.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewhjitea.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gtchihkjfx.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtwueojjub.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtuwjoykyu.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtkkbtmbpj.html

strcmp(a, b) == 0
来源：http://dali.bjfxy.top/Article/details/gtwygaugen.html

[S07] C：数组遍历求和
来源：http://dali.jqgfzy.top/Article/details/gtkoaujlzu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gtbberzmyc.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxuanxn.top/Article/details/gturzfyncq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gtlmffheey.html

[S09] C：结构体定义与初始化
来源：http://dali.bjfxy.top/Article/details/gthhiqzuuv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gteabctvgx.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqfeanly.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gtnqnylbal.html

[S11] C：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtvglguwts.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gtpwsjxylg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtfmjwndst.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gtllekeayz.html

[S12] C：写文件
来源：http://dali.guowangkeji.top/Article/details/gtqfpzgzxr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtztjwiekh.html

[S13] C：宏定义
来源：http://dali.yj20258.top/Article/details/gtpvtavrew.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gtvmibzyfw.html

[S14] C：枚举
来源：http://dali.zhengqikj.top/Article/details/gtrftelrqi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.snrcjt.cn/Article/details/gtmgdobbpc.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtdwltgvru.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gtjjzszpzv.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gtelalgvoo.html

x |= (1 << 3);
来源：http://dali.jinqigufen.top/Article/details/gtptayqitm.html

[S17] C：安全拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtbwoounxb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fzhhl.top/Article/details/gtkpdolxbx.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtskwpfuyi.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gthlmmpfkz.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gtfaudomyx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtjotjylxi.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gtdogwfqig.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtwkfrfxri.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gtizrxhgrs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gtgobvjrng.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtktunrtbq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pycfn.com/Article/details/gthylvessk.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gtloiegnij.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gtzoznibtr.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gtwgxbjvnz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gtdlcdyfkm.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gtsklrpwze.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gtfkrpxnrc.html

[S26] C：内存清零
来源：http://dali.9152youxi.cn/Article/details/gtivjtprqx.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gtziretbmn.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gtirbjypfl.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtredpjret.html

[S28] C：静态变量
来源：http://dali.meibo888.top/Article/details/gturggwsju.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gtinavqpyr.html

[S29] C：变参函数
来源：http://dali.zhoulong.xyz/Article/details/gtwvjiblac.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbudgsodp.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gtezlhsgsa.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gtnbbbgogn.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gtujsijxxf.html

#endif
来源：http://dali.ydzc1.top/Article/details/gtykniovqf.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtlduxsmbc.html


<!-- 参考信息 -->