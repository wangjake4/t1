代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtqpndqzoq.html

[Q58] 累计求和
来源：http://dali.zdqjudy.top/Article/details/gtznsyduch.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtsgizovgd.html

[Q59] 分组内累计
来源：http://dali.yvedp.cn/Article/details/gtaitpanpf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtxotycpyd.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gtjzbgymns.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hammf.cn/Article/details/gtbpppvxcu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtuevgbefd.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gtdutlimat.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtidpmwkop.html

[Q62] 分组占比
来源：http://dali.pycfn.com/Article/details/gtmwhqgwmk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gteppbvjex.html

[Q63] 开启事务
来源：http://dali.smart0.xyz/Article/details/gtcecovquv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gtlhtwwdbl.html

[Q64] 提交事务
来源：http://dali.smart0.xyz/Article/details/gtyoxgcusl.html

COMMIT;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhmlaabk.html

[Q65] 回滚事务
来源：http://dali.hysaishi.cn/Article/details/gtmhizibxm.html

ROLLBACK;
来源：http://dali.hongshengwenyu.top/Article/details/gtxicxhqbn.html

[Q66] 行锁查询
来源：http://dali.mhx1999.top/Article/details/gtqfeazwtm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gtbcqfrmnf.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gtliuwzyeh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gtsnmhvwlz.html

[Q68] 保存点
来源：http://dali.hnqzz.top/Article/details/gtmdqcqohg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gthkdquckt.html

ROLLBACK TO sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndnijmny.html

[Q69] 查看执行计划
来源：http://dali.ppjwa.cn/Article/details/gtclbkfmwz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.meibo888.top/Article/details/gtenqrmwyf.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gtdilrhodq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gtlixhvdeg.html

[Q71] 查看建表语句
来源：http://dali.xuanzx.com/Article/details/gttcshcibm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxinkj.top/Article/details/gtkclhvxko.html

[Q72] 查看索引
来源：http://dali.ydzc1.top/Article/details/gtawkzcvei.html

SHOW INDEX FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtrlpmkczm.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gtcneckrzd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gzhubu.top/Article/details/gtpkqzxjju.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gthotticcs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gtctyzuian.html

[Q75] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gttbngkkxg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtleiiugzm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gtomzlmcnt.html

[Q76] 按天统计
来源：http://dali.sysykeji.top/Article/details/gtsosbvgdm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxuanxn.top/Article/details/gtirkpynqm.html

[Q77] 时间加减
来源：http://dali.sweek.top/Article/details/gtrowrkxst.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.c1oappe.top/Article/details/gtqippdhjt.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gtrvktuvaz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gtdxvdzumk.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gtlguergua.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gtaolxwxkm.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gtkcdbxhih.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gtjypbpflr.html

[Q81] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtwozooblb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gtqtedvpyd.html

[Q82] 字符长度与字节长度
来源：http://dali.jyoumei.cn/Article/details/gtuoykeqny.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtdhlxsrse.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtzykhgrzn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnvfmnxo.html

[Q84] 去除首尾空格
来源：http://dali.9152youxi.cn/Article/details/gtekjtnffi.html

SELECT TRIM(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtylrtukjl.html

[Q85] 数值取整
来源：http://dali.jyoumei.cn/Article/details/gthikcwyfg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hfpthk.cn/Article/details/gtclqkjxsc.html

[Q86] 读取 JSON 字段
来源：http://dali.gzhubu.top/Article/details/gtkdeyexjz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gtzoherxhe.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gtbepfxnnw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hywenlv.cn/Article/details/gtefhtgvks.html

[Q88] 行转列（条件聚合）
来源：http://dali.hywenlv.cn/Article/details/gtwbrjarzs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sxryk.cn/Article/details/gtyyzzwyxq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtcxwntqfp.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gtmjjjoyqe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gtrepcvywt.html

[Q90] 生成序号列
来源：http://dali.hnxiangtu.top/Article/details/gtvflosmow.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gtufcestjb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxsnnpmee.html

R. Bash 专题
来源：http://dali.andypj.xyz/Article/details/gtfxtijvde.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtcybqbnvu.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gtuejonreq.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gtsgsnaupu.html

set -euo pipefail
来源：http://dali.gzhubu.top/Article/details/gtcwlxovyj.html

[R02] 变量赋值与使用
来源：http://dali.bjfxy.top/Article/details/gtriidqbjb.html

name="Tom"; echo "$name"
来源：http://dali.sweek.top/Article/details/gtynsbtbhq.html

[R03] 只读变量
来源：http://dali.wangshuangyany.cn/Article/details/gtwdwgicaa.html

readonly PI=3.14
来源：http://dali.hysaishi.cn/Article/details/gtivpghhbl.html

[R04] 位置参数
来源：http://dali.feifeiyinyue.top/Article/details/gtwxcvkoxd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jiagoushi.top/Article/details/gtdqdnuods.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gthswtfqmk.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gtdjahljnf.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtwyuotuoi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtmgvbljgk.html

[R07] if 判断文件
来源：http://dali.jinqigfzy.top/Article/details/gtpmcbxuee.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gtpxmpcver.html

[R08] 数值比较
来源：http://dali.zhongyouzk.top/Article/details/gtdnbjwflc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gtysfbaxyj.html

[R09] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtuzcpgyih.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daria6918.cn/Article/details/gtyhflcjhp.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmohqkgse.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xinyue.icu/Article/details/gtubvxtzep.html

[R11] case 多分支
来源：http://dali.feifeiyinyue.top/Article/details/gtwzwddoup.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gtluqeqmnx.html

start) echo "启动" ;;
来源：http://dali.pycfn.com/Article/details/gtmqvtqgpa.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gtsirdjzwf.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvulxpnj.html

esac
来源：http://dali.shzxlz.cn/Article/details/gtvcfjuoqq.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gtlauxqmgz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gtgnxqgnnl.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtkltuzmht.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtgngqditg.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gtvwmhpdzw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gtajjxream.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegptvqlz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zycfv.cn/Article/details/gtmmxppqng.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gtnrwnalqr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtmvvfynco.html

[R17] 数组定义与取值
来源：http://dali.gogol.net.cn/Article/details/gtwjmmbqmd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.quarkkingdee.top/Article/details/gtyecgrbfd.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gtepkqhuhx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtxjruirnn.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtuastmjyl.html

echo "${#arr[@]}"
来源：http://dali.sweek.top/Article/details/gtijadfwfk.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gtbxmpoevz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtypaswken.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtyoqyutxu.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gtllsvpptk.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtjsxjquiy.html

echo "${s:0:5}"
来源：http://dali.jinqigfzy.top/Article/details/gtjbsdzapt.html

[R23] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtovhqprom.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gtbnhtvpdk.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtbuvirmvl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yanxiufei.cn/Article/details/gtihhysrch.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigufen.top/Article/details/gteeangtlq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.vqdsnc.cn/Article/details/gtuvwvahid.html

[R26] 命令替换
来源：http://dali.jinqigfzy.top/Article/details/gtjnorjnbx.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxinkj.top/Article/details/gtaobnabbf.html

[R27] 算术展开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwxpfpxn.html

echo $((1 + 2 * 3))
来源：http://dali.jyoumei.cn/Article/details/gtxifrelrm.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gtrqvpkgea.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gtcgqmzqcz.html

[R29] 定义函数
来源：http://dali.aizwys.cn/Article/details/gtjreqlupn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gtaatoprap.html

[R30] 函数返回状态码
来源：http://dali.ybcxt.top/Article/details/gtqtarzfhr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gtwawolupy.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gtuzevjbcw.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtdebsuwxa.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gtpsqcqruo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtpvizdiqn.html

[R33] 捕获错误并提示行号
来源：http://dali.hammf.cn/Article/details/gtnjlwgjsl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aizwys.cn/Article/details/gtbasinaxv.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gttysvcqsz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtgawpovqp.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtcbcncskc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhongyouzk.top/Article/details/gtmdvpecgw.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gtzwlwxpwo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gtzbtwuscx.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gtxaomeypl.html

files=$(ls -1)
来源：http://dali.pycfn.com/Article/details/gtrhicynza.html

[R38] 管道串联
来源：http://dali.cucudq.cn/Article/details/gtgojawriy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtrdgcwgtb.html

[R39] 重定向标准输出与错误
来源：http://dali.andypj.xyz/Article/details/gtgtxsomzg.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtfffnjako.html

[R40] 追加写日志
来源：http://dali.meibo888.top/Article/details/gtzwshwvqd.html

echo "log" >> out.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttssblkrk.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gtkoiogpuy.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gthunnwbji.html

[R42] 输入重定向
来源：http://dali.ppjwa.cn/Article/details/gtmasaxuyz.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gtqhtshejo.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gtysdruhrh.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gtevhfwicm.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gtnmevdhiw.html

find . -mtime -7 -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtpwdnhhwi.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gtaatnmbwx.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdyjkjqu.html

[R46] 递归替换文件内容
来源：http://dali.chenlongwang.top/Article/details/gtvytoygzg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yangfankeji.com/Article/details/gtfdhvzxnu.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gtatiueyrq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtetvglwai.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gtztipyefd.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtlfarnfkt.html

[R49] awk 带条件
来源：http://dali.cucudq.cn/Article/details/gtsbtjxdom.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258888.top/Article/details/gtqdhvveia.html

[R50] awk 求和
来源：http://dali.hongshengwenyu.top/Article/details/gtzqwemhoq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtsjvvompc.html

[R51] 排序去重取前几
来源：http://dali.yvedp.cn/Article/details/gtdppwgydu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.316326.xyz/Article/details/gthnctoyje.html

[R52] 统计行数
来源：http://dali.wangdashe.top/Article/details/gtggrmsfvv.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gtipqlupyd.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gtvldbonaz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ivvv.top/Article/details/gtzduzmile.html

[R54] 比较两个文件
来源：http://dali.guowangkeji.top/Article/details/gtauqbeeza.html

diff a.txt b.txt
来源：http://dali.wangdashe.top/Article/details/gthkfqtynt.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gtnltignjx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gtnksgvezy.html

[R56] 远程拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugjeotuj.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gtblscykei.html

[R57] 远程执行命令
来源：http://dali.cashguo.top/Article/details/gtzokzbycy.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gtidxkscju.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gtlofryvow.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gtazenramt.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtlfzgshcq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gtthaqwbfl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtrheytljs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gtqnjploay.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gtpmbvvemg.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gtaoijjhis.html

[R62] 找最占空间的文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gttodrxwxx.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gtlbahqaku.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gtagfiecct.html

free -h;  ps aux | grep nginx
来源：http://dali.smart0.xyz/Article/details/gtanozjgvg.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcasjerp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gtelrwyxhf.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gtddbznvkm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gtgzjlrblv.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtifyleeph.html

crontab -e;  crontab -l
来源：http://dali.sufxvd.cn/Article/details/gtyteeyycq.html

[R67] 生成随机十六进制串
来源：http://dali.gaohongyu789.top/Article/details/gtwvzhvkrv.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gtpzzgmkkj.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gtyhhdrtnn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xziqi.cn/Article/details/gtyqibtdrd.html

[R69] 生成随机密码
来源：http://dali.316326.xyz/Article/details/gtmtenzsfq.html

head -c 16 /dev/urandom | base64
来源：http://dali.pengpengdd.cyou/Article/details/gtzrhtoaan.html

[R70] 时间戳与互转
来源：http://dali.jinqigufen.top/Article/details/gtbqqbthoq.html

date +%s;  date -d @1700000000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajignssx.html

[R71] 日期格式化
来源：http://dali.sweek.top/Article/details/gtetelldyh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gtpzkwmtdx.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gtsydiwkpz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtzpzkcbkx.html

[R73] 分割大日志
来源：http://dali.fengsongda.top/Article/details/gtpnmknlig.html

split -l 1000 big.log part_
来源：http://dali.daxiang520.top/Article/details/gtwyoxvooz.html

[R74] 批量重命名
来源：http://dali.daria6918.cn/Article/details/gtigccjxoi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gtjcwhqnri.html

[R75] 导出环境变量
来源：http://dali.ydzc1.top/Article/details/gttyhxojdd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gtcqgtmymr.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gtneexvrrn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtrtbbtjxw.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtycjdakix.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gtoedurgkq.html

[R78] 交互式菜单
来源：http://dali.jinqigfzy.top/Article/details/gtxrdpqiqv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.snrcjt.cn/Article/details/gtrnokilji.html

[R79] 解析命令行选项
来源：http://dali.cucudq.cn/Article/details/gtcqhmpzqh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtzrkaxqvz.html

[R80] 查看脚本执行耗时
来源：http://dali.jyoumei.cn/Article/details/gtwotxtcho.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gtsuztpmlj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtwzilukhc.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtjulkyxso.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gttaotvuow.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtsxkrqqre.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gtkyalekqf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gtucfcuuph.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtstiavaxc.html

int a = 10; printf("%d\n", a);
来源：http://dali.9152youxi.cn/Article/details/gtvwwgyhaw.html

[S03] C：读入整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcjtcapl.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gtfsyvrbee.html

[S04] C：字符串复制
来源：http://dali.ppjwa.cn/Article/details/gtrkldxxkn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daria6918.cn/Article/details/gttqsxvyah.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gthodnfoyx.html

strlen(s)
来源：http://dali.daxiang520.top/Article/details/gtnqzatqbm.html

[S06] C：字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtzewlfidh.html

strcmp(a, b) == 0
来源：http://dali.shangyingyoupin.top/Article/details/gthhvxyoax.html

[S07] C：数组遍历求和
来源：http://dali.yuanzhike.top/Article/details/gtdjlgasuy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gtoulbzyts.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gtzmeoicsg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dashuyun.cn/Article/details/gtsxjrxskx.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gtbwyejfyv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yanxiufei.cn/Article/details/gtblwrfszn.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gtmgfzvbvs.html

int *p = &a;  *p = 5;
来源：http://dali.fengsongda.top/Article/details/gtmbmxlxyy.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtsarizmfd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigfzy.top/Article/details/gtpxorkhby.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gtdqjgixbe.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtraquxcjl.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gtveebglxk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtespilkqq.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gtljwobugo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tanke756.top/Article/details/gtyzzjvjxi.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gtxsclixfu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dianchejie.cn/Article/details/gtucvbkkcc.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gtexwjjhbf.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gtjkkvhoue.html

[S16] C：位操作置位
来源：http://dali.wangdashe.top/Article/details/gtgxlcpzvq.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gtgujytzum.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtfqwkmxdw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gtuhmxxchk.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtactkaocn.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtbljothqi.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqctssvoq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gtooscwkok.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gtvugoaibw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtzhwqnlwt.html

[S21] C：字符类别判断
来源：http://dali.hywenlv.cn/Article/details/gtjmeufdtf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sufxvd.cn/Article/details/gtocaqiziy.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gthjdqozap.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.andypj.xyz/Article/details/gtwvzqeuno.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gtxxrqisma.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gtuxpwpsig.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gtgdbxgofk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gtivfakust.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gthiwdammv.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gtfnktzaou.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gtxqcotezf.html

memset(a, 0, sizeof a);
来源：http://dali.c1oappe.top/Article/details/gtbyehggdt.html

[S27] C：定义常量
来源：http://dali.ybcxt.top/Article/details/gtmnmzvspd.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtnutjjque.html

[S28] C：静态变量
来源：http://dali.chenzaomai.com/Article/details/gttlfbghum.html


<!-- 参考信息 -->