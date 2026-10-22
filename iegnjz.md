代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtacuarxhz.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gtfvoriwdz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daxiang520.top/Article/details/gtjflqddht.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtabrkyzbv.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkaorqiif.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtxzwtxgjh.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gtiunykagg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydjeuexa.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gtfppstizl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.bjfxy.top/Article/details/gtdusxhnxm.html

[Q64] 提交事务
来源：http://dali.gogol.net.cn/Article/details/gtutokynep.html

COMMIT;
来源：http://dali.xylfe.cn/Article/details/gtomkxoqnk.html

[Q65] 回滚事务
来源：http://dali.wangdashe.top/Article/details/gtcjfupqeh.html

ROLLBACK;
来源：http://dali.iojbl.cn/Article/details/gtjqooeiio.html

[Q66] 行锁查询
来源：http://dali.daxiang520.top/Article/details/gtksybgkqw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gtcwqcryow.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gtaquycsbx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuanzx.com/Article/details/gtilclfaiq.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gtqbrnwolw.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gtlhpkvhhg.html

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gtddcphfzq.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gtgofknwft.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tianlin.xyz/Article/details/gtwzodtajc.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gtgfykeuvm.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gtivuydqsl.html

[Q71] 查看建表语句
来源：http://dali.tian-w.cn/Article/details/gtxwbgscaw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gtmfdxrznh.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gtnyssqmru.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtykczcxfa.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gtzxsfdzgc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtbzxazqev.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtxyppqjhp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gtlozfuvpe.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcuzrkmbj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtbzkaetvv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gtnvesjucq.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gtllnxwxza.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhongyouzk.top/Article/details/gtkmmeockc.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gtszwqjcex.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhixingplan.top/Article/details/gtpagmyipo.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gtbjogrmgq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhiwuduotai.top/Article/details/gtofcjpysg.html

[Q79] 字符串拼接
来源：http://dali.yongpay.top/Article/details/gtympvymbd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daxiang520.top/Article/details/gtrqsprvst.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gtuvywszoz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtowhtvaqj.html

[Q81] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gttecyyrnb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nwbrower.top/Article/details/gtuxqlxxsv.html

[Q82] 字符长度与字节长度
来源：http://dali.snrcjt.cn/Article/details/gtdxprrbew.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtcphdctzk.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtmyuwctbq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtfhnftccw.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gtqywlfzsb.html

SELECT TRIM(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtjkvmqlcb.html

[Q85] 数值取整
来源：http://dali.yvedp.cn/Article/details/gtzfegubgr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hongshengwenyu.top/Article/details/gtmmirirja.html

[Q86] 读取 JSON 字段
来源：http://dali.tianlin.xyz/Article/details/gtmhjanmbc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtrzbupjtr.html

[Q87] JSON 字段做条件
来源：http://dali.ydzc1.top/Article/details/gtulcnxyor.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtqklnupmt.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gtqqajsqhx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgufenzy.top/Article/details/gtcxcdjxuk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtoinkavme.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gtpnpxzrgi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cheryme.top/Article/details/gtjhsyplcm.html

[Q90] 生成序号列
来源：http://dali.gaohongyu789.top/Article/details/gttvnmxiep.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtyymzdukq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gthzgvabao.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gtorxxumri.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwcsidwxi.html

[R01] shebang 与严格模式
来源：http://dali.yongpay.top/Article/details/gtftboebhm.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangtech.top/Article/details/gtqievjjuu.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gtzwtciqre.html

[R02] 变量赋值与使用
来源：http://dali.sysykeji.top/Article/details/gteyrjagtx.html

name="Tom"; echo "$name"
来源：http://dali.meibo888.top/Article/details/gtdfblhvly.html

[R03] 只读变量
来源：http://dali.jinqigfzy.top/Article/details/gtrishmghl.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gtafshlpzn.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gttuctwstq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhoulong.xyz/Article/details/gtkudbulax.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gtbumtjfob.html

name="${1:-default}"
来源：http://dali.meibo888.top/Article/details/gtjghwjona.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gtyptuyqgz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtnxunlbzm.html

[R07] if 判断文件
来源：http://dali.andypj.xyz/Article/details/gtepqmdpje.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtwkequpcz.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gtsdocwdya.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtxehdfdkx.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtnrbrrmeh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtjmevxovi.html

[R10] 正则匹配
来源：http://dali.cdnleiting.top/Article/details/gtxicfokoz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gttlppghzb.html

[R11] case 多分支
来源：http://dali.daxiang520.top/Article/details/gtqlctovab.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gtuecxerhs.html

start) echo "启动" ;;
来源：http://dali.c1oappe.top/Article/details/gtkwzakhsp.html

stop)  echo "停止" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtomtrkboh.html

*)     echo "未知命令" ;;
来源：http://dali.yangfankeji.com/Article/details/gtmsbfgran.html

esac
来源：http://dali.guowangkeji.top/Article/details/gtabbcdvsn.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gtasdqjzyc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gtdwoaxfba.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gtnskzsgau.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtiugngwof.html

[R14] C 风格 for
来源：http://dali.iojbl.cn/Article/details/gtpvlbeaou.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gthkzipizf.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtaiguyhho.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gttgxrcznz.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gtmcmmvjtw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtonuqqdld.html

[R17] 数组定义与取值
来源：http://dali.meibo888.top/Article/details/gtmrnliwcz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gtnscaflhu.html

[R18] 遍历数组
来源：http://dali.hnxiangtu.top/Article/details/gtnzawdgqu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gtkihltbsp.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlqdypum.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gtguqzhlvz.html

[R20] 关联数组（字典）
来源：http://dali.jinqigfzy.top/Article/details/gtmvwexfoo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gtjqjhiiix.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gthdxuvjcw.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gtrickxioi.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtmpphzvmv.html

echo "${s:0:5}"
来源：http://dali.kuanghao11.cn/Article/details/gttiwwggdu.html

[R23] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtapixnovt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gtmrietipj.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtznlemqsm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gtnaamrevw.html

[R25] 去后缀 / 去前缀
来源：http://dali.feifeiyinyue.top/Article/details/gtczreorwb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gtvtfskrrb.html

[R26] 命令替换
来源：http://dali.smart0.xyz/Article/details/gtuvhbylbj.html

now=$(date +%F); echo "$now"
来源：http://dali.hongshengwenyu.top/Article/details/gtxmbkgpff.html

[R27] 算术展开
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkwtcmlu.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gtcgshfycl.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gtdrryszbe.html

echo "scale=2; 10/3" | bc
来源：http://dali.316326.xyz/Article/details/gtrwjdsqxa.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gtfrfyowfs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ivvv.top/Article/details/gtbksefmlq.html

[R30] 函数返回状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtvuowlrgo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangdashe.top/Article/details/gtsthezwim.html

[R31] 局部变量
来源：http://dali.jqgfzy.top/Article/details/gtlkthjcmg.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gtyytzizjr.html

[R32] 参数个数校验
来源：http://dali.shzxlz.cn/Article/details/gtujktvpmg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtojbrvtnw.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gtqpkxvwqr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gtjsjqzdeh.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gtcilxtoqt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gteuoegssb.html

[R35] 后台执行并等待
来源：http://dali.tanke756.top/Article/details/gtsouotfos.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gtfvmauiva.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gtguwitmjc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gtfckjynoj.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gtqxapayfg.html

files=$(ls -1)
来源：http://dali.yonumen.top/Article/details/gtgjcskonp.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gtliummvvv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gtonobmvfr.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gtptoxxlkv.html

cmd > out.log 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtlpwkfsvg.html

[R40] 追加写日志
来源：http://dali.hnqzz.top/Article/details/gtcsradqlb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gtcafcylmo.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gtzurtbacm.html

cmd >/dev/null 2>&1
来源：http://dali.cheryme.top/Article/details/gtuajkyqkt.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gtlgybttpi.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkvofjxm.html

[R43] 按名字查找文件
来源：http://dali.yonumen.top/Article/details/gtuxxbwreq.html

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gturryacws.html

[R44] 按修改时间查找
来源：http://dali.jqgufenzy.top/Article/details/gtpmznuymq.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtvkjyznnt.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gtutvzffke.html

find . -name "*.tmp" -delete
来源：http://dali.cqqwz.cn/Article/details/gtbjopofyw.html

[R46] 递归替换文件内容
来源：http://dali.gotoacloud.top/Article/details/gtpvfbzkuf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gtxgfdhpth.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtvpyfigrs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtfyrquglv.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gtqpwhefnh.html

awk '{print $1, $3}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtccxpqyku.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gtcpfxshna.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.birdmap.top/Article/details/gtuthbmomw.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtuxkioryp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtjgutphqd.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gtugxalmxi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.quarkkingdee.top/Article/details/gtzeykofme.html

[R52] 统计行数
来源：http://dali.svipenyu.cn/Article/details/gtuurskfwl.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gtpjjprhcz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuuchjqr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gtokpvvwjm.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gtemtwjlyg.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtfetcyney.html

[R55] 压缩与解压
来源：http://dali.wangshuangyany.cn/Article/details/gtnimhaiza.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gtyghcjkmh.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gtukdaornq.html

scp file user@host:/path/
来源：http://dali.mhx1999.top/Article/details/gtozdypawh.html

[R57] 远程执行命令
来源：http://dali.andypj.xyz/Article/details/gtyujtflxb.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnshawtv.html

[R58] 下载文件
来源：http://dali.chenzaomai.com/Article/details/gtmfgdbqno.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ivvv.top/Article/details/gtbgbsegpt.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gthyatdqiq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxurnjmu.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtbgocsewc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gtzatxilwa.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gtpfrpktfv.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gtqwikmkzy.html

[R62] 找最占空间的文件
来源：http://dali.snrcjt.cn/Article/details/gtznwqezlr.html

du -ah . | sort -rh | head -10
来源：http://dali.9152youxi.cn/Article/details/gtctkmqyun.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gtltuoeqbs.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gtnatgmqrd.html

[R64] 结束进程
来源：http://dali.c1oappe.top/Article/details/gtqyzifinc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgzcbttx.html

[R65] 查看端口占用
来源：http://dali.gogol.net.cn/Article/details/gtflkvznpy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gzhubu.top/Article/details/gtcfaxwcsk.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gtdbhkngac.html

crontab -e;  crontab -l
来源：http://dali.havefunace.top/Article/details/gtaqhwuupr.html

[R67] 生成随机十六进制串
来源：http://dali.gogol.net.cn/Article/details/gtdfjqkbpl.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gtxwocizur.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangtech.top/Article/details/gtvibaijtf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tianlin.xyz/Article/details/gtivpdibnc.html

[R69] 生成随机密码
来源：http://dali.nanxinkj.top/Article/details/gtedzrrzzg.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gtqboajxhm.html

[R70] 时间戳与互转
来源：http://dali.yueranfly.top/Article/details/gtjecxhfcr.html

date +%s;  date -d @1700000000
来源：http://dali.jyoumei.cn/Article/details/gtwyldirvh.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtfdnqdlgn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cdnleiting.top/Article/details/gtfhzwdzsy.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gtgiqvjniw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gtplyeulyu.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gtgglldyax.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gtyuwotkif.html

[R74] 批量重命名
来源：http://dali.yonumen.top/Article/details/gtybttjdoy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gtifbmxesr.html

[R75] 导出环境变量
来源：http://dali.daria6918.cn/Article/details/gtkqhpuxib.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gtxaxfdwwx.html

[R76] 使用临时文件
来源：http://dali.hongshengwenyu.top/Article/details/gtjbkvedcw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtibemujxo.html

[R77] 读取用户输入
来源：http://dali.cdnleiting.top/Article/details/gtksboudni.html

read -rp "请输入: " ans
来源：http://dali.aibaodan.cn/Article/details/gttvqzoyde.html

[R78] 交互式菜单
来源：http://dali.vqdsnc.cn/Article/details/gtyjhfglvc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgfzy.top/Article/details/gtvdrlksag.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gttpspwrol.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gtittmjaof.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigfzy.top/Article/details/gtnyekwuos.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gtxuzjvtby.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtsqwyfjyw.html

S. C / C++ 专题
来源：http://dali.cdnleiting.top/Article/details/gtbjgetprs.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtucfulnjl.html

[S01] C：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtetmqimmd.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkaeefiko.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.haohaochexian.top/Article/details/gtgpyxvjnq.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gtrjktydgu.html

int a = 10; printf("%d\n", a);
来源：http://dali.hysaishi.cn/Article/details/gtrmxbvwga.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gtkkyduabc.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvsghlqk.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gtrzsakbqp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtqnbvohsb.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gtvnkteufb.html

strlen(s)
来源：http://dali.xuanzx.com/Article/details/gtjscpowwj.html

[S06] C：字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzoeqdeyr.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gtekbffqbz.html

[S07] C：数组遍历求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocxkgrwy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.feifeiyinyue.top/Article/details/gtfzwbvivs.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxuanxn.top/Article/details/gtmtpjagjh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cucudq.cn/Article/details/gtvnortrbe.html

[S09] C：结构体定义与初始化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbdtjtxs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gtjvhpexrn.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gtdkibkudz.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gtwmfylwoj.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtmdespffk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daxiang520.top/Article/details/gtgdrjvdcz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuanzx.com/Article/details/gtcgwsnkyg.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujqlnnrf.html

[S12] C：写文件
来源：http://dali.jlsjyb.cn/Article/details/gttqtqmkyg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gtinffsqim.html

[S13] C：宏定义
来源：http://dali.yvedp.cn/Article/details/gtuatcbiyr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ehwqpu.com/Article/details/gtedykqnsj.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgulmhuni.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxinkj.top/Article/details/gtukdcolfv.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gtumjkwdhp.html

(double) a / b
来源：http://dali.hywenlv.cn/Article/details/gtvrrzsvvh.html

[S16] C：位操作置位
来源：http://dali.hammf.cn/Article/details/gtfnypuauy.html

x |= (1 << 3);
来源：http://dali.daria6918.cn/Article/details/gteaehfowa.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gtqoohrznp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gtpuvsgrxi.html

[S18] C：命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtxmewrmis.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtcvpqmlol.html

[S19] C：快速排序
来源：http://dali.ivvv.top/Article/details/gtxeqmoyrs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtucibqrbe.html

[S20] C：二分查找
来源：http://dali.zycfv.cn/Article/details/gtgnpnkamf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtsmsykgyk.html

[S21] C：字符类别判断
来源：http://dali.daria6918.cn/Article/details/gtghfkdchb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gtpqsiznwn.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyhgsjba.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gtqyjmpndk.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtiqydsmhd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.kuanghao11.cn/Article/details/gtldnqaqcx.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gtodkcejqr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gtlbegqylk.html

[S25] C：内存拷贝
来源：http://dali.jqgfzy.top/Article/details/gtnfdhvpzo.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gtsevcevfu.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gtnuditqiu.html

memset(a, 0, sizeof a);
来源：http://dali.ydzc1.top/Article/details/gtcdgnudzb.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gtgckzyjsq.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtspfrevak.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gtbqanojok.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtibgapinv.html

[S29] C：变参函数
来源：http://dali.yuxming.cn/Article/details/gtqfnpnula.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gthwssqwvt.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gtdbfwcxve.html


<!-- 参考信息 -->