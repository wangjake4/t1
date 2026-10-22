代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtbrhvtwsw.html

[Q58] 累计求和
来源：http://dali.sufxvd.cn/Article/details/gtzzpmzhpl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yonumen.top/Article/details/gtbbdaoctp.html

[Q59] 分组内累计
来源：http://dali.yuxming.cn/Article/details/gtezzlqmfe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtbmblmdgh.html

[Q60] 取上一行 / 下一行
来源：http://dali.tanke756.top/Article/details/gtqdskbgnn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258888.top/Article/details/gtuvuditqd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gtnafgkvmc.html

[Q61] 移动平均
来源：http://dali.yangfankeji.com/Article/details/gtpgsfywrx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtfgimaqgz.html

[Q62] 分组占比
来源：http://dali.zhoulong.xyz/Article/details/gtpihfusvv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtwzvsboip.html

[Q63] 开启事务
来源：http://dali.havefunace.top/Article/details/gtuivkedsz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtalxqueyp.html

[Q64] 提交事务
来源：http://dali.xinyue.icu/Article/details/gteyamamux.html

COMMIT;
来源：http://dali.nanxinkj.top/Article/details/gtlubjuafo.html

[Q65] 回滚事务
来源：http://dali.vqdsnc.cn/Article/details/gtkxmvtclm.html

ROLLBACK;
来源：http://dali.tanke756.top/Article/details/gtgldfbzfm.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gttimryaom.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gtanfnnksp.html

[Q67] 设置隔离级别
来源：http://dali.ehwqpu.com/Article/details/gtmwmorkwl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gtygaunsqa.html

[Q68] 保存点
来源：http://dali.chenzaomai.com/Article/details/gtfueotjyt.html

SAVEPOINT sp1;
来源：http://dali.nanxinkj.top/Article/details/gtnoxfvhrt.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gttndnawjj.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gtoiljygna.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gtyloaalwi.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gtqosajsze.html

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gttnhhbppi.html

[Q71] 查看建表语句
来源：http://dali.tianlin.xyz/Article/details/gtsypifdfv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.9152youxi.cn/Article/details/gtrktotigt.html

[Q72] 查看索引
来源：http://dali.aibaodan.cn/Article/details/gtogmcbmyl.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqheshwn.html

[Q73] 查看表状态
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonbdduwh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtykmiikqv.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gtngqhkwrd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.kuanghao11.cn/Article/details/gtynmxpgza.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtgetlmmmn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtyuxuuuqx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hfpthk.cn/Article/details/gtgkwprhsn.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gtemkuczyo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gtceayaijh.html

[Q77] 时间加减
来源：http://dali.shzxlz.cn/Article/details/gtbscbyjsj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gthnsbkrbg.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gtotnanozi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gtampbiepm.html

[Q79] 字符串拼接
来源：http://dali.cashguo.top/Article/details/gtrufrolxj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gtmwmwjhkb.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gtwopkatjw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tian-w.cn/Article/details/gthereffcc.html

[Q81] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gthcfqsuvj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xylfe.cn/Article/details/gtfiaurhyu.html

[Q82] 字符长度与字节长度
来源：http://dali.cdnleiting.top/Article/details/gtzefigbmu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtcajjqvqq.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtjhimacin.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtjqmvrgbd.html

[Q84] 去除首尾空格
来源：http://dali.9152youxi.cn/Article/details/gtswxrktxg.html

SELECT TRIM(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtficnlxfw.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gtuxfwwcno.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.havefunace.top/Article/details/gtaeknstyu.html

[Q86] 读取 JSON 字段
来源：http://dali.yj202588.top/Article/details/gtjakvwfcq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cheryme.top/Article/details/gtbbmxubsi.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gtbyfslrrc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shzxlz.cn/Article/details/gthmwszisa.html

[Q88] 行转列（条件聚合）
来源：http://dali.sweek.top/Article/details/gtzfuuwvfx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gtljbupctv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuxming.cn/Article/details/gtameugdvg.html

[Q89] 判断表是否存在
来源：http://dali.haohaochexian.top/Article/details/gtmxnjdzdz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtmnoylrep.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gtyvufkbjh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fzhhl.top/Article/details/gtmstnoqpw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtaqoyrcoe.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gtnmrglvzg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtluvgmqug.html

[R01] shebang 与严格模式
来源：http://dali.sysykeji.top/Article/details/gtkbrwzusq.html

#!/usr/bin/env bash
来源：http://dali.yj20258.top/Article/details/gtuepgkydi.html

set -euo pipefail
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrvfzowh.html

[R02] 变量赋值与使用
来源：http://dali.yueranfly.top/Article/details/gtpzgldccf.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gtmszooqcd.html

[R03] 只读变量
来源：http://dali.havefunace.top/Article/details/gtelospswq.html

readonly PI=3.14
来源：http://dali.wangdashe.top/Article/details/gtcweqeiwt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gtyatncmzx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gtusiusfaz.html

[R05] 参数默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtdtcrqmjk.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gtkilkmdxy.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gtrxlipmwv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtipwdigis.html

[R07] if 判断文件
来源：http://dali.gzhubu.top/Article/details/gtagzemefd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gtzhqvmawn.html

[R08] 数值比较
来源：http://dali.sufxvd.cn/Article/details/gtexjobunw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pycfn.com/Article/details/gtegfimzye.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gthamecvcw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.0kj1m.cn/Article/details/gtrrgzrtns.html

[R10] 正则匹配
来源：http://dali.jiagoushi.top/Article/details/gtzrabugtd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gtfdnbxcrm.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gtwpwhvehc.html

case "$1" in
来源：http://dali.jqgufenzy.top/Article/details/gtbfbkaqwv.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqzvejqm.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gtssgwzyve.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258.top/Article/details/gtslhyukoh.html

esac
来源：http://dali.wangshuangyany.cn/Article/details/gtavnjpibw.html

[R12] for 遍历文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqddfbxo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tanke756.top/Article/details/gtgnjjajgq.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtfvvkjfif.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtrokhbllb.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtmclwmvzd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtygqslqlg.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtncipxqqg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gtnardpwxy.html

[R16] until 等待条件
来源：http://dali.c1oappe.top/Article/details/gthsufyazy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtjwrxakda.html

[R17] 数组定义与取值
来源：http://dali.mhx1999.top/Article/details/gtpdkencwc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gtwmhiyypq.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gtknnpxmiq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gtaceecrhq.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtpvdmofdc.html

echo "${#arr[@]}"
来源：http://dali.nanxuanxn.top/Article/details/gtjoztvzvy.html

[R20] 关联数组（字典）
来源：http://dali.smart0.xyz/Article/details/gttkrsjlod.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yueranfly.top/Article/details/gtitmzsxlc.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gttyvbmaac.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gtvskkeahn.html

[R22] 截取子串
来源：http://dali.zycfv.cn/Article/details/gtqrmrgtoj.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfocjcjr.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtnxyeiqyh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gtrabwmyvu.html

[R24] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpzpwqxf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gzhubu.top/Article/details/gttemompab.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gtqbrwmcln.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtfvyodmai.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gtxpcettff.html

now=$(date +%F); echo "$now"
来源：http://dali.hnqzz.top/Article/details/gtfjfuffap.html

[R27] 算术展开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpktvtdil.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gtftxffdqo.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gtbfnzvjsv.html

echo "scale=2; 10/3" | bc
来源：http://dali.xinyue.icu/Article/details/gtrnakzyvg.html

[R29] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtnnsfvdnv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtcuqqsazu.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gtbpeecoqc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozqzqqbp.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gtfktnkxdb.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtmhtkolta.html

[R32] 参数个数校验
来源：http://dali.havefunace.top/Article/details/gtedldsfoh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtctdifzqg.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gtbexikgtd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gtnpcpabrt.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gtxhwzxaig.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtqwapjvmq.html

[R35] 后台执行并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtanvatnuw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jyoumei.cn/Article/details/gtobvgjjqm.html

[R36] 并发执行多个任务
来源：http://dali.xylfe.cn/Article/details/gtoeldfdfj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gogol.net.cn/Article/details/gtbahwxhfv.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gtngiznbsn.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtmdksnhkk.html

[R38] 管道串联
来源：http://dali.nanxuanxn.top/Article/details/gtaqumdhaa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhengqikj.top/Article/details/gtuobgojbf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gtbrkoszvu.html

cmd > out.log 2>&1
来源：http://dali.andypj.xyz/Article/details/gtdzwlxmrk.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gtqwgqfyuv.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gtfnegsnrs.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gtdjgsboku.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtxclasxvg.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gtojdeclrs.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gtudydhzbk.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gtavihxmyq.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gtnmobtchu.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukldktgr.html

find . -mtime -7 -type f
来源：http://dali.9152youxi.cn/Article/details/gtubnntadx.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gtrjudbdza.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gtsdfrywsw.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gtygmrcpna.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnxiangtu.top/Article/details/gtbklqmgho.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gtbygdtyti.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gtttiadxhw.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkcqdibk.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtkfxrooqi.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gtxagzvcrr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tianlin.xyz/Article/details/gtrcgimsox.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gtwdgviwbo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtrdxxuowx.html

[R51] 排序去重取前几
来源：http://dali.c1oappe.top/Article/details/gthgidsorh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangtech.top/Article/details/gtouptckot.html

[R52] 统计行数
来源：http://dali.zhiwuduotai.top/Article/details/gtxkrzufzf.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gtezuortqm.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gthfpmllkk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj202588.top/Article/details/gttrggsyiz.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gtousuttmn.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gtvivqenlc.html

[R55] 压缩与解压
来源：http://dali.zhongyouzk.top/Article/details/gtnckukoqj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gtzasumjht.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtxwwgwwde.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gtrkfpbpmx.html

[R57] 远程执行命令
来源：http://dali.pengpengdd.cyou/Article/details/gtopvafiwq.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gtraerhuee.html

[R58] 下载文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcojpvxx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxinkj.top/Article/details/gtbyitevnl.html

[R59] 发 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gtlqcmgqkn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daxiang520.top/Article/details/gtedntmecn.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtwqxffryb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zycfv.cn/Article/details/gthfaqzrio.html

[R61] 磁盘占用
来源：http://dali.sysykeji.top/Article/details/gtwihwgpqg.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gtvrhgfnex.html

[R62] 找最占空间的文件
来源：http://dali.fzhhl.top/Article/details/gtdjekftri.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gtbjuxwtsi.html

[R63] 内存与进程
来源：http://dali.jyoumei.cn/Article/details/gtprucpztv.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gtumswncrg.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gtebitbfyl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gttyyrkans.html

[R65] 查看端口占用
来源：http://dali.zhoulong.xyz/Article/details/gtlhwkecdn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gtfgdvtzzc.html

[R66] 定时任务
来源：http://dali.yuxming.cn/Article/details/gtpmsbvudj.html

crontab -e;  crontab -l
来源：http://dali.pycfn.com/Article/details/gtcgedumdn.html

[R67] 生成随机十六进制串
来源：http://dali.hywenlv.cn/Article/details/gtysjcgkkj.html

openssl rand -hex 16
来源：http://dali.pycfn.com/Article/details/gtjknoqbcm.html

[R68] 计算文件校验值
来源：http://dali.fzhhl.top/Article/details/gtejemzpgu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ppjwa.cn/Article/details/gtgmdnjkts.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gtpqnssqbr.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gtyvxazpvo.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gtwzreqasg.html

date +%s;  date -d @1700000000
来源：http://dali.guowangkeji.top/Article/details/gtwvgxvkjj.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtfwqtwxfs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yanxiufei.cn/Article/details/gtoqlolpps.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gtdqdchgsu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gtafgjgfhv.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gtlnghyery.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtsifeqqqo.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gtapbqlszw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gtjxopekcz.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gtybyjrggv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.0kj1m.cn/Article/details/gtepoodpit.html

[R76] 使用临时文件
来源：http://dali.hysaishi.cn/Article/details/gtydwvnajh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gthngcnvqe.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzvmuqhj.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gtsfufkdhu.html

[R78] 交互式菜单
来源：http://dali.9152youxi.cn/Article/details/gtmdomkown.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gtfmetgmqb.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gtmifxecbf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnqzz.top/Article/details/gtymtqkqja.html

[R80] 查看脚本执行耗时
来源：http://dali.xuanzx.com/Article/details/gtcsaooeca.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gtsianwdbq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbfmwhvzi.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtunxlgbbx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtpzoaoodg.html

[S01] C：Hello World
来源：http://dali.yonumen.top/Article/details/gtuhiyovfx.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gtexukxjgh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gtxtemdrez.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtpisjoysq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfbrmlyx.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gtbmbhmvra.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gtfdcjolyc.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gtscngbryj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gttcivqcra.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gtmggscart.html

strlen(s)
来源：http://dali.gaohongyu789.top/Article/details/gtusznzpjy.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtnhqkhljl.html

strcmp(a, b) == 0
来源：http://dali.shuidangran.top/Article/details/gtqhovpggd.html

[S07] C：数组遍历求和
来源：http://dali.bjfxy.top/Article/details/gtzluncsaa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gtmmlpimfn.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gthzojckpk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gtirtuhzbo.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gtwrtgfmaw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ehwqpu.com/Article/details/gttcgnwvbt.html

[S10] C：指针与解引用
来源：http://dali.andypj.xyz/Article/details/gteowojoob.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gttuiwogfm.html

[S11] C：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtjmonxnir.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gtgdeigdqr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hammf.cn/Article/details/gtfgskhock.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtuqjlpooa.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gthkgliryx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gtydjqqfqe.html

[S13] C：宏定义
来源：http://dali.nanxuanxn.top/Article/details/gtsmtdqsvp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yonumen.top/Article/details/gtsvwyrjeq.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gtbdqdkinx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shuidangran.top/Article/details/gtwwfijruh.html

[S15] C：类型转换
来源：http://dali.haohaochexian.top/Article/details/gtahziyzii.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gtheirppoe.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gtokeutzze.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gtlzujqeiv.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gthhfddyuh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gtiefbpcca.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gtmyyvbqic.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gtepkddcsw.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gtmnbarugv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtcgyqdayr.html

[S20] C：二分查找
来源：http://dali.cheryme.top/Article/details/gtwmwokihf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtodtxnxut.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gtqpdsjfwg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gtcvmrrcsv.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gtdnygxcbc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gtkdebibwt.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gtfjzsdcud.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxzisbas.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gtcvsscizg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cdnleiting.top/Article/details/gtviytyudc.html

[S25] C：内存拷贝
来源：http://dali.meibo888.top/Article/details/gtlberzxmq.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gtgfxazgzi.html

[S26] C：内存清零
来源：http://dali.aibaodan.cn/Article/details/gtoflpiprx.html

memset(a, 0, sizeof a);
来源：http://dali.cdnleiting.top/Article/details/gtdppnfsdb.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gtxwbztmva.html

const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtmfskzdwf.html

[S28] C：静态变量
来源：http://dali.jiagoushi.top/Article/details/gtnvhyhjeq.html


<!-- 参考信息 -->