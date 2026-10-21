代发 wailian999

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gttkzyvnpz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtlqincdph.html

[Q62] 分组占比
来源：http://dali.feifeiyinyue.top/Article/details/gtlzpwjzro.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtaymgglbl.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gtdkynxysr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhixingplan.top/Article/details/gthouqlnau.html

[Q64] 提交事务
来源：http://dali.zhengqikj.top/Article/details/gtwahgoaad.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gtqdbwtink.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtaipiinhp.html

ROLLBACK;
来源：http://dali.aizwys.cn/Article/details/gtdbfkbcrz.html

[Q66] 行锁查询
来源：http://dali.nanxuanxn.top/Article/details/gtpmagcdjb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gtssiedzer.html

[Q67] 设置隔离级别
来源：http://dali.hammf.cn/Article/details/gtehnljfps.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gtbgqrvkre.html

[Q68] 保存点
来源：http://dali.guannengcc.top/Article/details/gtfepziruf.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbodcanu.html

ROLLBACK TO sp1;
来源：http://dali.xziqi.cn/Article/details/gtodowunrh.html

[Q69] 查看执行计划
来源：http://dali.haohaochexian.top/Article/details/gtfqnwfvuf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gtdlawqegi.html

[Q70] 更新统计信息
来源：http://dali.zycfv.cn/Article/details/gtdkztgejn.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gtzpglorxn.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gtfeqfyyji.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gtllgfnhxi.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gtnlslmnte.html

SHOW INDEX FROM users;
来源：http://dali.jianghu66.top/Article/details/gttiheiptp.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtfebzkjqi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gogol.net.cn/Article/details/gthcprxzkn.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtonifmfel.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gtiybxyhgq.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtfhiuprgn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daria6918.cn/Article/details/gttizmgyfa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gtkykexsax.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gthulmdpxr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.vqdsnc.cn/Article/details/gtqtydsgyg.html

[Q77] 时间加减
来源：http://dali.smart0.xyz/Article/details/gttqvauvnw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xziqi.cn/Article/details/gtgsuuhcyp.html

[Q78] 当前时间
来源：http://dali.xylfe.cn/Article/details/gtguizlxix.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gtlfgqlbrs.html

[Q79] 字符串拼接
来源：http://dali.xinyue.icu/Article/details/gtfrbwbhne.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ywan-chungtsiang.top/Article/details/gttozoqsrc.html

[Q80] 字符串截取
来源：http://dali.vqdsnc.cn/Article/details/gtdobmhyxg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtdhhzjysb.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtqvlsijqi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtpxuwxela.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslzkoxor.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtunjdccrg.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtbyrmenah.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtjxwlzpnx.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtvddkeljj.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtaijatumi.html

[Q85] 数值取整
来源：http://dali.nwbrower.top/Article/details/gtifbradpo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgufenzy.top/Article/details/gtavmzktnn.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gtfyonpbvl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gtkfzizcde.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gtduioljlj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gthqlpcaqp.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtozaupoxj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gtxixidakk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtujzngifu.html

[Q89] 判断表是否存在
来源：http://dali.yj20258888.top/Article/details/gtsrktgsvi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ppjwa.cn/Article/details/gtnchhlzem.html

[Q90] 生成序号列
来源：http://dali.tian-w.cn/Article/details/gtkkpwbfjd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gaohongyu789.top/Article/details/gtmyqmmwda.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtmbhvynlk.html

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gtogwqycuu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtahbtqlpu.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gtwpooykch.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtmfirwpyz.html

set -euo pipefail
来源：http://dali.0kj1m.cn/Article/details/gtpabdkypk.html

[R02] 变量赋值与使用
来源：http://dali.yueranfly.top/Article/details/gtuhccgqqy.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gtsruawsav.html

[R03] 只读变量
来源：http://dali.fengsongda.top/Article/details/gtgzgsoqhc.html

readonly PI=3.14
来源：http://dali.feifeiyinyue.top/Article/details/gtyvfwajyt.html

[R04] 位置参数
来源：http://dali.xziqi.cn/Article/details/gtcwcozpmo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gtcxrqgvqm.html

[R05] 参数默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtfctmhzws.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gtvycvidgs.html

[R06] 判断命令是否存在
来源：http://dali.andypj.xyz/Article/details/gtorifxghl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtcdtheqje.html

[R07] if 判断文件
来源：http://dali.hongshengwenyu.top/Article/details/gthcbafgyg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gtinmukfac.html

[R08] 数值比较
来源：http://dali.jyoumei.cn/Article/details/gtsnokjzjt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hammf.cn/Article/details/gtlqqzcvnu.html

[R09] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtqryaujmt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtluqaanxv.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gtepcxvnne.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gtycheklti.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gtftgxydgi.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gtiaxpiiya.html

start) echo "启动" ;;
来源：http://dali.jiagoushi.top/Article/details/gtokbtzcyr.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtqwczeiiv.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gtqewpfpgj.html

esac
来源：http://dali.chenjidiqi.icu/Article/details/gtqoulzgux.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gtjamupuif.html

for f in *.txt; do echo "$f"; done
来源：http://dali.snrcjt.cn/Article/details/gtexuopbzn.html

[R13] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gtetobngdi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtyxwzinuz.html

[R14] C 风格 for
来源：http://dali.pycfn.com/Article/details/gtvawlfirk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtvjciwwgb.html

[R15] while 逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gttjvlrgsl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtmylmrbpw.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiftilwkg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gtoamxuiee.html

[R17] 数组定义与取值
来源：http://dali.aibaodan.cn/Article/details/gtsmyptmlw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yongpay.top/Article/details/gtbowjokkw.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gtaidsrbgh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgufenzy.top/Article/details/gtrxbxmuoe.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtdexhfvya.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gtemuegowp.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gtdrahickh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gtzcorsyua.html

[R21] 字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtfsqyskps.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtzuuelyxx.html

[R22] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtijannlui.html

echo "${s:0:5}"
来源：http://dali.hywenlv.cn/Article/details/gtyxplerhu.html

[R23] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gthjnkbpoo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cqqwz.cn/Article/details/gtajtfoxgx.html

[R24] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gtobcgzrim.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbueyfntn.html

[R25] 去后缀 / 去前缀
来源：http://dali.gaohongyu789.top/Article/details/gtvckfzpza.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gtuoevehbk.html

[R26] 命令替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwcidiia.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtkedcqaok.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtnnbhbggs.html

echo $((1 + 2 * 3))
来源：http://dali.aizwys.cn/Article/details/gtjmcipfsa.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gtugsepved.html

echo "scale=2; 10/3" | bc
来源：http://dali.yanxiufei.cn/Article/details/gteuwblkhn.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gtdkdemtde.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.9152youxi.cn/Article/details/gtzkyzrgfe.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gtltkwwuox.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sysykeji.top/Article/details/gtyghykntk.html

[R31] 局部变量
来源：http://dali.yonumen.top/Article/details/gtdxcdzono.html

f() { local x=1; echo "$x"; }
来源：http://dali.fzhhl.top/Article/details/gtatnjzgxk.html

[R32] 参数个数校验
来源：http://dali.yanxiufei.cn/Article/details/gtlsuiibsw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtwkcxtbhj.html

[R33] 捕获错误并提示行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtafduboca.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gtpsvpzdpm.html

[R34] 退出时清理
来源：http://dali.hywenlv.cn/Article/details/gtimchcyrm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gtgypkaapc.html

[R35] 后台执行并等待
来源：http://dali.nanxuanxn.top/Article/details/gtfztpmmas.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gtaakzkrwo.html

[R36] 并发执行多个任务
来源：http://dali.316326.xyz/Article/details/gtipwcwjqa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sweek.top/Article/details/gtrherrwla.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gtykmrmjvv.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gthyjcqzgm.html

[R38] 管道串联
来源：http://dali.guowangkeji.top/Article/details/gtleuiimoa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenjidiqi.icu/Article/details/gtxkqiobjx.html

[R39] 重定向标准输出与错误
来源：http://dali.hywenlv.cn/Article/details/gtbqodvvwv.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtsrynqsep.html

[R40] 追加写日志
来源：http://dali.meibo888.top/Article/details/gtrszrwtzv.html

echo "log" >> out.log
来源：http://dali.snrcjt.cn/Article/details/gtnrygjkjh.html

[R41] 丢弃输出
来源：http://dali.aibaodan.cn/Article/details/gtwtuyezxi.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gtpibkjdwj.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gtoafxvegx.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gtpnobjjud.html

[R43] 按名字查找文件
来源：http://dali.aibaodan.cn/Article/details/gtkiejslaz.html

find . -name "*.log" -type f
来源：http://dali.cucudq.cn/Article/details/gtoksbqeha.html

[R44] 按修改时间查找
来源：http://dali.cqqwz.cn/Article/details/gtcpavwqmu.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gtzvqwbwzu.html

[R45] 批量删除
来源：http://dali.daria6918.cn/Article/details/gtwsgsxcyi.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gtlokhdqxa.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gtrpqepoez.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hywenlv.cn/Article/details/gtpzzkjxfh.html

[R47] sed 单行替换
来源：http://dali.sufxvd.cn/Article/details/gtlsjpzgrq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.meibo888.top/Article/details/gtsrpmgiiz.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtumjgkqcn.html

awk '{print $1, $3}' a.txt
来源：http://dali.shuidangran.top/Article/details/gthmymfcrb.html

[R49] awk 带条件
来源：http://dali.zhoulong.xyz/Article/details/gtfkvuxbew.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gtvqixxeme.html

[R50] awk 求和
来源：http://dali.nanxuanxn.top/Article/details/gtkcjhmoxa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtcytwaufv.html

[R51] 排序去重取前几
来源：http://dali.xuanzx.com/Article/details/gtfbhofzcr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gtlbawfkef.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gthitecfks.html

wc -l a.txt
来源：http://dali.shuidangran.top/Article/details/gtzddxjwqn.html

[R53] 查看文件头与实时尾
来源：http://dali.jyoumei.cn/Article/details/gtyzwlhkbf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gtjzjmmisu.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gtjhgbrpnt.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbjvqpqq.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gtthgpjhgo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jianghu66.top/Article/details/gtbeurejnb.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtcwxgteze.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbhdgzdr.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gtvgmkwqpe.html

ssh user@host 'uptime'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbuufedzi.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtwifunzaa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aibaodan.cn/Article/details/gtpdetgxsw.html

[R59] 发 POST JSON
来源：http://dali.yj20258.top/Article/details/gtrtihrcti.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gtysqxkglm.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtzprpdssc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhongyouzk.top/Article/details/gtyudijojm.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gtnkehmesw.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gtgwklxyep.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gtulqdqjjt.html

du -ah . | sort -rh | head -10
来源：http://dali.hnxiangtu.top/Article/details/gtyrvzxndl.html

[R63] 内存与进程
来源：http://dali.aibaodan.cn/Article/details/gtzkigtxva.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gtvzzpcqfr.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gtejxuigzz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.9152youxi.cn/Article/details/gtdzqgjdmb.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gtvroinhah.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yongpay.top/Article/details/gtpooogtbj.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gtroryvvng.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gtergecsrz.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gtbazrpyrg.html

openssl rand -hex 16
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvakypogd.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gtdwskexaz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gttzyygptn.html

[R69] 生成随机密码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzfxwnor.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gtxjyzwbdj.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gtwkvikpwt.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gtclfywxid.html

[R71] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtbtogrrhx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gtxanmfbyv.html

[R72] 等待端口就绪
来源：http://dali.yj20258888.top/Article/details/gtpvuegjia.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzjjgikj.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gtzyissgre.html

split -l 1000 big.log part_
来源：http://dali.yangfankeji.com/Article/details/gtjkjkbgua.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gtevlgyduw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jianghu66.top/Article/details/gtfqvwnhtr.html

[R75] 导出环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtorfqslik.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.mhx1999.top/Article/details/gtfoxpcbbd.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gtbzikxlvo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtsdhjdpsk.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gtasyjpojl.html

read -rp "请输入: " ans
来源：http://dali.yuanzhike.top/Article/details/gtwoghzhai.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gtoonxdbgi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gtxcmhwbbi.html

[R79] 解析命令行选项
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuzmiwzp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gtagzyoyyl.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gtsbkvajue.html

time ./run.sh
来源：http://dali.xinyue.icu/Article/details/gtpjxtkzcw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlmrcwhsy.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gtwitvydvv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtibbfywas.html

[S01] C：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtmjbmjetq.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gtrhcwrefd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ydzc1.top/Article/details/gtxzabwjnd.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gtpdzmhzof.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangdashe.top/Article/details/gtuuyeudau.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtzojmrzqg.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtmcgfwwtv.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcexlccn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtkiwcqpqv.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gtmvaorwrf.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gtqiyaaawd.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gtmeuhuiis.html

strcmp(a, b) == 0
来源：http://dali.sweek.top/Article/details/gtyiuodazg.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gtzznrjptx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pengpengdd.cyou/Article/details/gtzflctgzc.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gtayngffne.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gteygpdpza.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gtahfxwjqe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cdnleiting.top/Article/details/gtnrjiitxr.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gtvieuxbbk.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gtysjodlgd.html

[S11] C：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtyyntynaf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gtvzxexhhs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gtvfcauqkr.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtqadtnkad.html

[S12] C：写文件
来源：http://dali.ydzc1.top/Article/details/gtngynsbhl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqdmwcpv.html

[S13] C：宏定义
来源：http://dali.redwolf501.top/Article/details/gtaxdhfgox.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gtbguavwkz.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtphotqqep.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gtemxnyszn.html

[S15] C：类型转换
来源：http://dali.havefunace.top/Article/details/gtdlianien.html

(double) a / b
来源：http://dali.316326.xyz/Article/details/gthovcugvc.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gtrubirzzy.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtzvcqdjrg.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gthpxlguel.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.c1oappe.top/Article/details/gtsqgwpsqo.html

[S18] C：命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtnmhduprb.html

int main(int argc, char **argv)
来源：http://dali.zdqjudy.top/Article/details/gtxttlwimo.html

[S19] C：快速排序
来源：http://dali.pengpengdd.cyou/Article/details/gtfpoammwz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtptpfthqc.html

[S20] C：二分查找
来源：http://dali.hnxiangtu.top/Article/details/gtsqpmsdfj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtuemgnmno.html

[S21] C：字符类别判断
来源：http://dali.ivvv.top/Article/details/gtrzowiktj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hfpthk.cn/Article/details/gtrtyorrzk.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijpyphda.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.c1oappe.top/Article/details/gtdyrbdmcc.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtnxgvdpez.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sysykeji.top/Article/details/gtyfvdywir.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gttwzblrld.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gtgzwjdzpw.html

[S25] C：内存拷贝
来源：http://dali.snrcjt.cn/Article/details/gtmnvpdemr.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gttgbdtbnk.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gtvcxcmccm.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gtuslenpap.html

[S27] C：定义常量
来源：http://dali.nanxuanxn.top/Article/details/gtykrihqis.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtoakgpwaq.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gtiemujopu.html

static int counter = 0;
来源：http://dali.chenzaomai.com/Article/details/gtonkipeqq.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gtfodmqvgz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gtbznqqzzq.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gtascpjkgu.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtvyiabdjz.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gtaeslexpa.html

#endif
来源：http://dali.yuxming.cn/Article/details/gtqnmqjjkd.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gttbsoiswr.html


<!-- 参考信息 -->