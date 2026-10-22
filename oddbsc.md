代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemnmxtqn.html

[Q60] 取上一行 / 下一行
来源：http://dali.jianghu66.top/Article/details/gtvdxwjjyr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuetiantiany.cn/Article/details/gtlarodhbu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtmtghcjzx.html

[Q61] 移动平均
来源：http://dali.shangyingyoupin.top/Article/details/gthqttyltr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtsnemiqqj.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gtvzyutsqo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtirwobrys.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmhkaqej.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.haohaochexian.top/Article/details/gtpopwbihd.html

[Q64] 提交事务
来源：http://dali.gzhubu.top/Article/details/gtszkhxati.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gtlxbrkrlc.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtwzcljgdl.html

ROLLBACK;
来源：http://dali.haohaochexian.top/Article/details/gtbpsklqml.html

[Q66] 行锁查询
来源：http://dali.tanke756.top/Article/details/gtxvlmjyzu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgfzy.top/Article/details/gtowcsdret.html

[Q67] 设置隔离级别
来源：http://dali.zhengqikj.top/Article/details/gtexxkmwbz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhengqikj.top/Article/details/gtkhlwsypy.html

[Q68] 保存点
来源：http://dali.andypj.xyz/Article/details/gtvvygwitf.html

SAVEPOINT sp1;
来源：http://dali.cheryme.top/Article/details/gtzrdweejn.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtjabbifoo.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gtjoprvnjy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gtcqcqmgkd.html

[Q70] 更新统计信息
来源：http://dali.cashguo.top/Article/details/gtvvrielpi.html

ANALYZE TABLE users;
来源：http://dali.yongpay.top/Article/details/gtmsdvfgen.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gtpjodsuqn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhengqikj.top/Article/details/gtndexvlhh.html

[Q72] 查看索引
来源：http://dali.jqgfzy.top/Article/details/gtfwqgxenn.html

SHOW INDEX FROM users;
来源：http://dali.gzhubu.top/Article/details/gtdnfmansb.html

[Q73] 查看表状态
来源：http://dali.guowangkeji.top/Article/details/gtixgicoik.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtvijncbwv.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gthhnrxcel.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tianlin.xyz/Article/details/gtbilyldkn.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtgozxomvm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtwgrcddgk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangtech.top/Article/details/gtwaxtghmc.html

[Q76] 按天统计
来源：http://dali.zhongyouzk.top/Article/details/gtoozcdooo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.kuanghao11.cn/Article/details/gtkocgqvzb.html

[Q77] 时间加减
来源：http://dali.smart0.xyz/Article/details/gtzqhkyjpi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gtzdxwqwvo.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gtdielrcwz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.mhx1999.top/Article/details/gtjbqnzoju.html

[Q79] 字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gtjnmxonwm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gtwvmvgfek.html

[Q80] 字符串截取
来源：http://dali.iojbl.cn/Article/details/gtfokusuhq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtpjvucweb.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtnvrxfeww.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtycxxniyr.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gtadwitnpi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtutcwsgjr.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtmupgocln.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtrtofsryq.html

[Q84] 去除首尾空格
来源：http://dali.guowangkeji.top/Article/details/gtvkqgmmqb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtuhplslxe.html

[Q85] 数值取整
来源：http://dali.kuanghao11.cn/Article/details/gtuxmdndlo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shuidangran.top/Article/details/gtrbgakemq.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gtjogehtzi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sysykeji.top/Article/details/gtqyuostbl.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gtntmmllbp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhoulong.xyz/Article/details/gtafakcadc.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenjidiqi.icu/Article/details/gtpjbwrkss.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aibaodan.cn/Article/details/gtrdydxrnc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gtvfoxkebs.html

[Q89] 判断表是否存在
来源：http://dali.birdmap.top/Article/details/gtwdnvmprs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cashguo.top/Article/details/gtwkofqukt.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gtgoduzxre.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gtpwwdjbct.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtoekyhrkw.html

R. Bash 专题
来源：http://dali.yangfankeji.com/Article/details/gtthbevrvs.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtiqjdoexd.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gttirnxjxs.html

#!/usr/bin/env bash
来源：http://dali.mhx1999.top/Article/details/gtozfsrdze.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gtrbvdhvje.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmwyfwrg.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtggbejtrf.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gtamszkani.html

readonly PI=3.14
来源：http://dali.yangfankeji.com/Article/details/gtornhlcxw.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gtqjynpofk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gtqdsmmjzw.html

[R05] 参数默认值
来源：http://dali.nanxinkj.top/Article/details/gtqmttetij.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gtjtgvyzzv.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gtjtwdpffw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtgdhfvngg.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtouixiyxt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gtlvrwvdct.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gtetkflxvf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zycfv.cn/Article/details/gtnvrcxxfn.html

[R09] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtpsydqvop.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxwewnji.html

[R10] 正则匹配
来源：http://dali.yongpay.top/Article/details/gtaiteghfp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtxaxxmuox.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gtoitlorid.html

case "$1" in
来源：http://dali.zhiwuduotai.top/Article/details/gtvluvllsi.html

start) echo "启动" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtilxfdyws.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gtwnmaqgkq.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gterrhpdcu.html

esac
来源：http://dali.mhx1999.top/Article/details/gtpoitanag.html

[R12] for 遍历文件
来源：http://dali.vqdsnc.cn/Article/details/gthdljtheq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gtshmulenv.html

[R13] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gtapzrbwcg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gttwtdsxhp.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gtueyqylso.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtpaabzuuw.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtggzqclfa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gtfeugozsg.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gtdstvaqsn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtwgwmaeyx.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gtiotzbybx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jyoumei.cn/Article/details/gtlnvtoqbd.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtnclbpprr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppnjyuus.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtfcpxfweu.html

echo "${#arr[@]}"
来源：http://dali.jinqigfzy.top/Article/details/gtpnpotbzh.html

[R20] 关联数组（字典）
来源：http://dali.yj20258.top/Article/details/gtbnnmplfn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtfyfzgtpx.html

[R21] 字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtpbhzgbii.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gtrdrsixot.html

[R22] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtzpziskwp.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gttcwaxjej.html

[R23] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gtrfadbxmi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gtrsfggjgy.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtiapgdmzx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daria6918.cn/Article/details/gtmkvcdkor.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gtxplxvycz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jyoumei.cn/Article/details/gtfluczikw.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gthnpdjldk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhixingplan.top/Article/details/gtjqnxcgjt.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gtubpdhwaz.html

echo $((1 + 2 * 3))
来源：http://dali.feifeiyinyue.top/Article/details/gtanhentmy.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gteoxmvuib.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhongyouzk.top/Article/details/gtennczwgu.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtwlcjytid.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuozalqbj.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gtpfkrjcwu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gtbuqlbwuk.html

[R31] 局部变量
来源：http://dali.316326.xyz/Article/details/gthygelxlt.html

f() { local x=1; echo "$x"; }
来源：http://dali.redwolf501.top/Article/details/gtgxejanlt.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvgvyimi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtueptmgww.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gtdpypekpa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258888.top/Article/details/gtrucdmvrg.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gthfdlzlze.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtapxvtrzj.html

[R35] 后台执行并等待
来源：http://dali.yuxming.cn/Article/details/gtzvdabzbn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtzsdunovw.html

[R36] 并发执行多个任务
来源：http://dali.daxiang520.top/Article/details/gtxwzimorv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdecfhesf.html

[R37] 把输出赋给变量
来源：http://dali.guannengcc.top/Article/details/gtkbczeaeh.html

files=$(ls -1)
来源：http://dali.jyoumei.cn/Article/details/gtsqdirtaf.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gtobjawdce.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxuanxn.top/Article/details/gtwylbgwce.html

[R39] 重定向标准输出与错误
来源：http://dali.gzhubu.top/Article/details/gtkkvbxocf.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtdimsnwaf.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugveibsj.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gtyuxbfsxs.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gtajirjikv.html

cmd >/dev/null 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtcpnrmaqu.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gtdpgmllcj.html

wc -l < a.txt
来源：http://dali.guannengcc.top/Article/details/gtlzmjibzx.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gtkgqotypk.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gtrftfflua.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gtpkcatdlz.html

find . -mtime -7 -type f
来源：http://dali.yj20258888.top/Article/details/gtxcmdqrzj.html

[R45] 批量删除
来源：http://dali.meibo888.top/Article/details/gtmjmepqyv.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gtnahhwydb.html

[R46] 递归替换文件内容
来源：http://dali.nwbrower.top/Article/details/gtkdlkefws.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gogol.net.cn/Article/details/gtfjqgvywn.html

[R47] sed 单行替换
来源：http://dali.bjfxy.top/Article/details/gtopnuafxu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cheryme.top/Article/details/gtstacvxwm.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gtoigvpdcn.html

awk '{print $1, $3}' a.txt
来源：http://dali.hammf.cn/Article/details/gtheqimkwy.html

[R49] awk 带条件
来源：http://dali.fengsongda.top/Article/details/gtzlteumcu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gaohongyu789.top/Article/details/gthoczywpv.html

[R50] awk 求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhqkvuqp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtnoaqqjyh.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gtemtxljsa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gtysbsibtq.html

[R52] 统计行数
来源：http://dali.xziqi.cn/Article/details/gteybqcift.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gtjkfhqkkn.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpgyquze.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gtnruhwpae.html

[R54] 比较两个文件
来源：http://dali.fengsongda.top/Article/details/gtimqebtuq.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtinhhkuax.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gtwqpbxfpv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmujqlpg.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gtssreinus.html

scp file user@host:/path/
来源：http://dali.snrcjt.cn/Article/details/gthdombqyd.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gtpfdwjnxm.html

ssh user@host 'uptime'
来源：http://dali.aizwys.cn/Article/details/gtyqhzuyhb.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gtturiiywg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guowangkeji.top/Article/details/gthxtngsnr.html

[R59] 发 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtyrgwumcw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gtbwlwebux.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtvlqlclsm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtanzlbdsc.html

[R61] 磁盘占用
来源：http://dali.zhengqikj.top/Article/details/gtxokapwkd.html

df -h;  du -sh *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxjbwsno.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmjfziwuc.html

du -ah . | sort -rh | head -10
来源：http://dali.tianlin.xyz/Article/details/gtjapmscsj.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtzspabzfv.html

free -h;  ps aux | grep nginx
来源：http://dali.pengpengdd.cyou/Article/details/gtdwwlkzcl.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gtvogikyzg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gtugpuxrdz.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gtzmhpszya.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhaomingkeji.xyz/Article/details/gtealupdrh.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtskdqwawj.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gtntnwubxt.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gtwvppaljv.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gtdexfbsnr.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gtfdomwpsy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hywenlv.cn/Article/details/gtshxdnnvu.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gtwkchszgy.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbblnewbe.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtrkjvlayf.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gtkkcorvno.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gtpcwrnrox.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.0kj1m.cn/Article/details/gtnmtziqfn.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gtwzsykvzu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtadhrkynr.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gtlynhicwc.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gtkzatoscb.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gttluglxbx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj202588.top/Article/details/gtjlobimls.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gtlvdzhoaf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gtnwdkpgfo.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gtxekyyafg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtlzhtttxz.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gtphrmzfem.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gtdbznwiow.html

[R78] 交互式菜单
来源：http://dali.jyoumei.cn/Article/details/gtpqyltbni.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gtxsifedat.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gtgrtcjsvv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cucudq.cn/Article/details/gtudmspuhn.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzqytjbx.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gttsevwnbf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtkjlmgasa.html

S. C / C++ 专题
来源：http://dali.hnqzz.top/Article/details/gtjpvhjxmf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtspnygcui.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gteovcydgz.html

#include <stdio.h>
来源：http://dali.feifeiyinyue.top/Article/details/gtizqsfjid.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gthxwkzyyh.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtimviivrf.html

int a = 10; printf("%d\n", a);
来源：http://dali.vqdsnc.cn/Article/details/gtfgaqccel.html

[S03] C：读入整数
来源：http://dali.gaohongyu789.top/Article/details/gtxvzvlkog.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtoxbflrgv.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gtdlqotzzj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtmjirdrup.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gtzmxskeqy.html

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsjxisdw.html

[S06] C：字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gthpduzilf.html

strcmp(a, b) == 0
来源：http://dali.meibo888.top/Article/details/gtjdphadjz.html

[S07] C：数组遍历求和
来源：http://dali.aibaodan.cn/Article/details/gtmfkikdai.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gtbygeogus.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gticesihtu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gtldsojwgv.html

[S09] C：结构体定义与初始化
来源：http://dali.316326.xyz/Article/details/gtmmswncwt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gtawlybzyf.html

[S10] C：指针与解引用
来源：http://dali.xuanzx.com/Article/details/gttxivnzet.html

int *p = &a;  *p = 5;
来源：http://dali.guowangkeji.top/Article/details/gtapzanbcr.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlygcatcq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigfzy.top/Article/details/gtoadpczmc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daria6918.cn/Article/details/gtkbhaboci.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtcpfzdjpz.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gtsixyhsdf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtdxrfemaw.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gtqarthrck.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gtxjkfecar.html

[S14] C：枚举
来源：http://dali.sysykeji.top/Article/details/gtegxnpdvp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gtndkxnffi.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gtzrngdkoj.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gthwhmxtoq.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gtutwhzotw.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gtdxczqudj.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtzuyaijbb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfseozgxx.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxemlptzo.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gtvkdetueh.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gtakrwttfu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtfgjoenbu.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gtdcfpqzjx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtdiccldsm.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gtfliegoaj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxuanxn.top/Article/details/gtfyqlnsmv.html

[S22] C：字符串转数字
来源：http://dali.jianghu66.top/Article/details/gtfvgbdrle.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtlhnzmcot.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gtylqzbbwn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gtbcewhyck.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gtsgfvjxhn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gthdozqyom.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gtlnzlztve.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gtvgcmuhrp.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gtmspyposx.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gtnivvhcpm.html

[S27] C：定义常量
来源：http://dali.zhengqikj.top/Article/details/gtrwrabydy.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtayugfrqn.html

[S28] C：静态变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhvvublj.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gtcmlehjlw.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gtdrhjdglh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gtadubodhs.html

[S30] C：头文件保护
来源：http://dali.zhiwuduotai.top/Article/details/gtidjmhqxw.html


<!-- 参考信息 -->