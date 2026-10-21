代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gtnrecvdne.html

[Q58] 累计求和
来源：http://dali.hammf.cn/Article/details/gtujmqebap.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtsycldwct.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gtgiosqgmh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtnntlblrz.html

[Q60] 取上一行 / 下一行
来源：http://dali.jyoumei.cn/Article/details/gtrkjxkfcy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dashuyun.cn/Article/details/gthufwydfm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctfoiljs.html

[Q61] 移动平均
来源：http://dali.0kj1m.cn/Article/details/gtumdsmkao.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gthnteqzyh.html

[Q62] 分组占比
来源：http://dali.svipenyu.cn/Article/details/gtfmpbhsur.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtdhkkhxln.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gtlwtydkpm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gtwodtubnc.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gttprhwgof.html

COMMIT;
来源：http://dali.hysaishi.cn/Article/details/gtysumgfal.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gtgqydlhpx.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gtttvrjneh.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gtqwlhtmbo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.snrcjt.cn/Article/details/gtbykzwjgu.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gtkfbpvbxf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gtftrtpedr.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gtlniokulh.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjuppjerr.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gtdjpqjnyt.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gtdokxrscv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gtbsaqnwmm.html

[Q70] 更新统计信息
来源：http://dali.yonumen.top/Article/details/gtrqvjlcpe.html

ANALYZE TABLE users;
来源：http://dali.xylfe.cn/Article/details/gtnysidaxu.html

[Q71] 查看建表语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjlkvpsn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gtxhjsqmim.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gtjnbzbmhm.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gtlcighgae.html

[Q73] 查看表状态
来源：http://dali.hfpthk.cn/Article/details/gtvybxxfuk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gtoixbxyrt.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gtizzxxvov.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gtuqpsmtkk.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtyeymhunx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtxkzzbzpa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hongshengwenyu.top/Article/details/gtvwwrtrwp.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gtwzjkaynq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gtdmnskzjc.html

[Q77] 时间加减
来源：http://dali.nwbrower.top/Article/details/gtqddtlcqu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.havefunace.top/Article/details/gtndudwjwi.html

[Q78] 当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gtxtlqnisc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gtqbyxumko.html

[Q79] 字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtlmjluluy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gtssudhdfn.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gtfmkldtpq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gthmclvtan.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtgshcvaib.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtfhksikqe.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gtprqusosu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtretfhiaw.html

[Q83] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtogywuibd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtwcmdvpzg.html

[Q84] 去除首尾空格
来源：http://dali.xylfe.cn/Article/details/gtrosgccxo.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtqilheqvr.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gtzeoxtsbt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtbizzpclc.html

[Q86] 读取 JSON 字段
来源：http://dali.kuanghao11.cn/Article/details/gtpcuyejoq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhixingplan.top/Article/details/gtdllrlwhn.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gtqjoiebie.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gttiejfuta.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gtoqclivyw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shangyingyoupin.top/Article/details/gtpkhiqkph.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gtsshzskeh.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gthdjkmgpb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ivvv.top/Article/details/gtjwrtszns.html

[Q90] 生成序号列
来源：http://dali.jiagoushi.top/Article/details/gtghpomljo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtyqaazmpz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvpzuxnqg.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gtgigreafk.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkvmebnrl.html

[R01] shebang 与严格模式
来源：http://dali.nanxuanxn.top/Article/details/gtzklwpohk.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gtvnjzrxoa.html

set -euo pipefail
来源：http://dali.cashguo.top/Article/details/gtszrtwpjz.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gtvqemhiig.html

name="Tom"; echo "$name"
来源：http://dali.chenjidiqi.icu/Article/details/gtwnuhfnpj.html

[R03] 只读变量
来源：http://dali.gotoacloud.top/Article/details/gtiegrnqsp.html

readonly PI=3.14
来源：http://dali.snrcjt.cn/Article/details/gtsrzljsir.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gtwrakcfqn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hywenlv.cn/Article/details/gtwtclwgvx.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gtiocdkpiv.html

name="${1:-default}"
来源：http://dali.daxiang520.top/Article/details/gtcsywwoqd.html

[R06] 判断命令是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtgjuorbeo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwgvolem.html

[R07] if 判断文件
来源：http://dali.jlsjyb.cn/Article/details/gtdlrbkuhg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gtbxtqmcio.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtmlgdmmuy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gtirjiamuv.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtofdyyxhk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.meibo888.top/Article/details/gtykybjyps.html

[R10] 正则匹配
来源：http://dali.xinyue.icu/Article/details/gtevqruxxe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gtpcljrrgo.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gtlnbsrphf.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gtaojqnksg.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gtwfipcbkk.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gtiatdwyuy.html

*)     echo "未知命令" ;;
来源：http://dali.daxiang520.top/Article/details/gtrbcllbkh.html

esac
来源：http://dali.gzhubu.top/Article/details/gtzcvacmib.html

[R12] for 遍历文件
来源：http://dali.yuxming.cn/Article/details/gtcyuyejkn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.9152youxi.cn/Article/details/gtqpnuarpr.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixxreuqp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gteaaiofdu.html

[R14] C 风格 for
来源：http://dali.ehwqpu.com/Article/details/gtjjqvprzd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtlesvuuul.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtuwzqgfrh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gtjntpsoqi.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gtqcwlpaay.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtluurqcjk.html

[R17] 数组定义与取值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdnwoeyx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gtgauxbhhh.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gtquscctve.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gtoktcbaaf.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtoziwtuch.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gtcuchraoq.html

[R20] 关联数组（字典）
来源：http://dali.ppjwa.cn/Article/details/gtgggfcsbm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gtdktklxkx.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnkhhvvd.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gtvcybhlcd.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gtvtjpvqhm.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gttpojxgss.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtmewsmhev.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gtpzuzdulz.html

[R24] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtyqhvtcyf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtjwauxixd.html

[R25] 去后缀 / 去前缀
来源：http://dali.sxryk.cn/Article/details/gtbvnnqrqy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gtqytqzhgd.html

[R26] 命令替换
来源：http://dali.sufxvd.cn/Article/details/gtcivzmzag.html

now=$(date +%F); echo "$now"
来源：http://dali.quarkkingdee.top/Article/details/gttclqlozf.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gtyilpbjyn.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gttzgpkgxf.html

[R28] 浮点运算
来源：http://dali.ppjwa.cn/Article/details/gtizvuwjti.html

echo "scale=2; 10/3" | bc
来源：http://dali.pycfn.com/Article/details/gtubbjrcdg.html

[R29] 定义函数
来源：http://dali.yuxming.cn/Article/details/gtzcxvhvbd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtxisjfqnw.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gtdzwuodpe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gtsgjxltec.html

[R31] 局部变量
来源：http://dali.wangdashe.top/Article/details/gtscdpozwr.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gtcofgwalo.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gtdomqpdxi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtklszkzoe.html

[R33] 捕获错误并提示行号
来源：http://dali.kuanghao11.cn/Article/details/gtohomekum.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwsttezk.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gteosntzdz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtwbxehivy.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gtvvsirtwu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gtgmdqrjws.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgumniyt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxuanxn.top/Article/details/gtwpimzedf.html

[R37] 把输出赋给变量
来源：http://dali.hywenlv.cn/Article/details/gtytdaeucj.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtchkeufmq.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gthneqpopi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gtddckwkuk.html

[R39] 重定向标准输出与错误
来源：http://dali.gzhubu.top/Article/details/gtwvhagkcg.html

cmd > out.log 2>&1
来源：http://dali.guannengcc.top/Article/details/gtvkwhdosy.html

[R40] 追加写日志
来源：http://dali.shuidangran.top/Article/details/gtwjisaszp.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtgukhyzvy.html

[R41] 丢弃输出
来源：http://dali.zycfv.cn/Article/details/gteblmtpxq.html

cmd >/dev/null 2>&1
来源：http://dali.guowangkeji.top/Article/details/gtrxifkzeb.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gtwdooazak.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gtdxadugyz.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gtwnlbfhcu.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gtoybnstwb.html

[R44] 按修改时间查找
来源：http://dali.bjfxy.top/Article/details/gtxzkfwrmm.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gtqljtrjti.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gtptmfyaid.html

find . -name "*.tmp" -delete
来源：http://dali.ivvv.top/Article/details/gtgemfskgt.html

[R46] 递归替换文件内容
来源：http://dali.yj20258888.top/Article/details/gtjzmmeqiv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hongshengwenyu.top/Article/details/gtfpvumutb.html

[R47] sed 单行替换
来源：http://dali.hnxiangtu.top/Article/details/gtmounleed.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtplwnewqt.html

[R48] awk 取指定列
来源：http://dali.pengpengdd.cyou/Article/details/gtnpythsdm.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsprnapf.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gtfcfyesbb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.smart0.xyz/Article/details/gtlkznobfh.html

[R50] awk 求和
来源：http://dali.tian-w.cn/Article/details/gtidxttcpr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtgkmiobsq.html

[R51] 排序去重取前几
来源：http://dali.aibaodan.cn/Article/details/gtbtctvwfy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gtcoozyrpw.html

[R52] 统计行数
来源：http://dali.cashguo.top/Article/details/gtflawsyjc.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gtubtjgafo.html

[R53] 查看文件头与实时尾
来源：http://dali.jlsjyb.cn/Article/details/gtatvcmtgc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daxiang520.top/Article/details/gtkxzcmyoi.html

[R54] 比较两个文件
来源：http://dali.svipenyu.cn/Article/details/gteggjkwdx.html

diff a.txt b.txt
来源：http://dali.cdnleiting.top/Article/details/gtimvtaset.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gtzynemeon.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuuhzwwa.html

[R56] 远程拷贝
来源：http://dali.sweek.top/Article/details/gtybeawqyj.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gtjvxsayyz.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gtlvffiyfu.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gtephimirr.html

[R58] 下载文件
来源：http://dali.yj20258888.top/Article/details/gtruzqyfvc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gtaodmmxta.html

[R59] 发 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtxgapcwlz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxinkj.top/Article/details/gtqzskfvoz.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtlsjyurup.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gtscjnkzel.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gtmpwxtizv.html

df -h;  du -sh *
来源：http://dali.snrcjt.cn/Article/details/gtyazavwev.html

[R62] 找最占空间的文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsceautul.html

du -ah . | sort -rh | head -10
来源：http://dali.hfpthk.cn/Article/details/gtmprudlnm.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gtzppquefp.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gthsmcnhyc.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gtoczmacpq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gtrjqvfztd.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gthcnpehkt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gtclreosrq.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gtectdzjxg.html

crontab -e;  crontab -l
来源：http://dali.c1oappe.top/Article/details/gtrfajpthj.html

[R67] 生成随机十六进制串
来源：http://dali.gotoacloud.top/Article/details/gtpduilnha.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gtucwstlao.html

[R68] 计算文件校验值
来源：http://dali.jyoumei.cn/Article/details/gtutxkpmcb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fzhhl.top/Article/details/gtvmkvbevx.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gtpkfgywox.html

head -c 16 /dev/urandom | base64
来源：http://dali.kuanghao11.cn/Article/details/gtuzirxspw.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gtretuncoc.html

date +%s;  date -d @1700000000
来源：http://dali.yuanzhike.top/Article/details/gtnquirhiy.html

[R71] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxeyfglz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuxming.cn/Article/details/gtzdikysvk.html

[R72] 等待端口就绪
来源：http://dali.hnqzz.top/Article/details/gtsahbfgzp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtxrscxgyv.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gthofnclvz.html

split -l 1000 big.log part_
来源：http://dali.yanxiufei.cn/Article/details/gtjmolwknl.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gtvelhoxrf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tanke756.top/Article/details/gtkdqszosx.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtpfcufagv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtwsebismi.html

[R76] 使用临时文件
来源：http://dali.hfpthk.cn/Article/details/gttqludkxs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtyxgokuch.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gtffxbjgdz.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gtnjptwidu.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gtlwdnndkg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gtuxfxwbro.html

[R79] 解析命令行选项
来源：http://dali.yj20258888.top/Article/details/gtnamuulaw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.9152youxi.cn/Article/details/gtssjvnbun.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gtyqqftcbf.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gtrdsiuoay.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfxfrqeex.html

S. C / C++ 专题
来源：http://dali.svipenyu.cn/Article/details/gtilwybxqs.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtzfszkpip.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gtmpijuwtv.html

#include <stdio.h>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyflndaxz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ydzc1.top/Article/details/gturqxyvas.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtidhzbzxh.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gtwdsxfhkr.html

[S03] C：读入整数
来源：http://dali.mhx1999.top/Article/details/gtlgqetelx.html

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gtaghskmqw.html

[S04] C：字符串复制
来源：http://dali.cheryme.top/Article/details/gtgncyfjwn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtfumgnjzs.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtpubgqoko.html

strlen(s)
来源：http://dali.sufxvd.cn/Article/details/gtwlblrrmu.html

[S06] C：字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gthrqdkjvc.html

strcmp(a, b) == 0
来源：http://dali.zdqjudy.top/Article/details/gtberhxdax.html

[S07] C：数组遍历求和
来源：http://dali.jqgfzy.top/Article/details/gtgsosopaw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gtpymovlom.html

[S08] C：动态内存分配与释放
来源：http://dali.kuanghao11.cn/Article/details/gtxvfipstv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gtaibsylod.html

[S09] C：结构体定义与初始化
来源：http://dali.tianlin.xyz/Article/details/gtjwmhxjch.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gtuerxidjg.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gthgoijzqd.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gtdjgwrkmk.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtsvjwmjlm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gtfxkouhel.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gtuedvvtnk.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcryhrsah.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gtcuxujjgr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtwhmmsyil.html

[S13] C：宏定义
来源：http://dali.hnxiangtu.top/Article/details/gtjmbqhawo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.c1oappe.top/Article/details/gtvpxnjbvo.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gtkafiiayx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gtjoynbjoi.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gtoyvdkyyo.html

(double) a / b
来源：http://dali.fengsongda.top/Article/details/gtyhsztrjl.html

[S16] C：位操作置位
来源：http://dali.redwolf501.top/Article/details/gtsuhltljf.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtbrhvbchm.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtyvhdjgqp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gtpxlmbqym.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmcndxos.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtzkrxbolg.html

[S19] C：快速排序
来源：http://dali.zdqjudy.top/Article/details/gtounnyvpu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtwbltypyc.html

[S20] C：二分查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwkapnzd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnyxlsjz.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gtkracgxvf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.bjfxy.top/Article/details/gthidwcecp.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gtqqnexxia.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjplabvid.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gttwzsmnag.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.vqdsnc.cn/Article/details/gtzucndtjw.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gtxzjmgfec.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhiwuduotai.top/Article/details/gtymmeeynj.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gtaotvsrdk.html

memcpy(dst, src, n);
来源：http://dali.daria6918.cn/Article/details/gtuxnrzhcb.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gttepsslod.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gtsvjwqfva.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gtwbjnaikf.html

const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtgkdxtciv.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gtyneiiwwt.html


<!-- 参考信息 -->