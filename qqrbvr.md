代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtnhvabksm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.haohaochexian.top/Article/details/gtlzimlhmo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hammf.cn/Article/details/gtawsubqxo.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gthlwtbsxx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gtogryvftk.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotqrdjhv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtxujabdvc.html

[Q59] 分组内累计
来源：http://dali.pycfn.com/Article/details/gtwxrwclmm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtcjajfrbi.html

[Q60] 取上一行 / 下一行
来源：http://dali.tianlin.xyz/Article/details/gtbexsmipn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hammf.cn/Article/details/gtxgcskeea.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtouxttyfe.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gttmkvlslv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtcavnqeze.html

[Q62] 分组占比
来源：http://dali.tian-w.cn/Article/details/gttwshksvc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtunrsqgei.html

[Q63] 开启事务
来源：http://dali.ybcxt.top/Article/details/gtksahcfjj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.iojbl.cn/Article/details/gtdnlogfiz.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gtxsmztbdk.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gtezjpimtp.html

[Q65] 回滚事务
来源：http://dali.jinqigufen.top/Article/details/gthwotmxqz.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gtxigwbass.html

[Q66] 行锁查询
来源：http://dali.gogol.net.cn/Article/details/gtpkuzcjbd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shzxlz.cn/Article/details/gtamxsjzuv.html

[Q67] 设置隔离级别
来源：http://dali.jinghuilouyu.cn/Article/details/gtofxtremf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gtufxkkrsz.html

[Q68] 保存点
来源：http://dali.yonumen.top/Article/details/gtqusrmwpl.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtmyrxmxiy.html

ROLLBACK TO sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtqtamslyo.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gtlnlretav.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gtiqqxyzlc.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gtbwgxwgsm.html

ANALYZE TABLE users;
来源：http://dali.cucudq.cn/Article/details/gtteyaycit.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gttaenrepe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jlsjyb.cn/Article/details/gtoxqadbcy.html

[Q72] 查看索引
来源：http://dali.tanke756.top/Article/details/gtsrvgorny.html

SHOW INDEX FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtqgxkjeqx.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtxlxecrrw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yangfankeji.com/Article/details/gtzjpknehk.html

[Q74] 强制使用索引
来源：http://dali.nwbrower.top/Article/details/gthtyroxvd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gtmnnljpdu.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gtoodoeryu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtbsffrcyk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gtigubcwht.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gtlcxxhetd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dianchejie.cn/Article/details/gtlgpueixq.html

[Q77] 时间加减
来源：http://dali.shangyingyoupin.top/Article/details/gtzfmcpyyi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gtoltvwnnc.html

[Q78] 当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtabcdbond.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xylfe.cn/Article/details/gtjqrbrygf.html

[Q79] 字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtgbhddm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nwbrower.top/Article/details/gtmpbcvitz.html

[Q80] 字符串截取
来源：http://dali.yanxiufei.cn/Article/details/gttfbtoqcu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtihtooirl.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtldnjxzat.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtvckhjbms.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258888.top/Article/details/gtxxexsftw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtxxgbyjlb.html

[Q83] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtuxtvgotl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtcyivjfsh.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gtpmnrrgbj.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtaoqzsfjm.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gtyxynbqlc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gtplexcqgu.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258888.top/Article/details/gtxamdatnc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangshuangyany.cn/Article/details/gtfocdmdhz.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gtolzgftqu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gotoacloud.top/Article/details/gtocrizwup.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gtjwvixqnb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gtgqyyjogo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gtpswmirrh.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtlbscfwxh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yongpay.top/Article/details/gtjsxbkllw.html

[Q90] 生成序号列
来源：http://dali.smart0.xyz/Article/details/gtoeirprvg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guannengcc.top/Article/details/gtdtlofanr.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbotzjpig.html

R. Bash 专题
来源：http://dali.guowangkeji.top/Article/details/gtywfuwscu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtmgaqpjpz.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gtlhwoyuon.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gtsmflwxgt.html

set -euo pipefail
来源：http://dali.dianchejie.cn/Article/details/gtcpjdjbic.html

[R02] 变量赋值与使用
来源：http://dali.zhoulong.xyz/Article/details/gtcbihgdfz.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gtpmaskziy.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gtxqkipvsp.html

readonly PI=3.14
来源：http://dali.chenzaomai.com/Article/details/gtcxrnaxte.html

[R04] 位置参数
来源：http://dali.yongpay.top/Article/details/gtgnirseak.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gtvplqubsm.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gtflhpwmdq.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gtsuihzkik.html

[R06] 判断命令是否存在
来源：http://dali.shuidangran.top/Article/details/gtxootwolb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtnwzmwcpp.html

[R07] if 判断文件
来源：http://dali.andypj.xyz/Article/details/gtyhhephcm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtqcnayufg.html

[R08] 数值比较
来源：http://dali.316326.xyz/Article/details/gtjrgpardf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtmcgonfgz.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtujezadis.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtarfqnfnd.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtbmgtaige.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gtatuaunbg.html

[R11] case 多分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxhnkumr.html

case "$1" in
来源：http://dali.gogol.net.cn/Article/details/gtzkhelvuw.html

start) echo "启动" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxxuteee.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gtofcxnclf.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtmqphmjrw.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gtyubrygpc.html

[R12] for 遍历文件
来源：http://dali.wangshuangyany.cn/Article/details/gtovcttgci.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gtsunhhwtl.html

[R13] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gtofnkmtpn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtcoxnrlan.html

[R14] C 风格 for
来源：http://dali.svipenyu.cn/Article/details/gtxtwtqdyc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gtryibpuvz.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtihacpxof.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gtkrwluwzt.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gtryocduyy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtefaajxnp.html

[R17] 数组定义与取值
来源：http://dali.9152youxi.cn/Article/details/gtmyikaayt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gtptyosybs.html

[R18] 遍历数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbseelcqg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gtcuuxjxgx.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtwwsfkgky.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gttluotxre.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gtrbnjrzxb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtowcnoktx.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gtmonskpii.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gtakbkketg.html

[R22] 截取子串
来源：http://dali.yvedp.cn/Article/details/gttvbkdvix.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gtcaugqyaa.html

[R23] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtkgwaifjl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtysixtcvr.html

[R24] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtcafwbjst.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gttnbnmtbn.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gtthhjcqoi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.meibo888.top/Article/details/gtnhlxgqqr.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtmjncrrnb.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gtrjldhdqw.html

[R27] 算术展开
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfcsmtzr.html

echo $((1 + 2 * 3))
来源：http://dali.shuidangran.top/Article/details/gttomomwrv.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gthptkhiri.html

echo "scale=2; 10/3" | bc
来源：http://dali.yongpay.top/Article/details/gthnwvwkac.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gtwmfujese.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tianlin.xyz/Article/details/gtakcbppae.html

[R30] 函数返回状态码
来源：http://dali.sweek.top/Article/details/gthggtpprd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ppjwa.cn/Article/details/gtyonlcigk.html

[R31] 局部变量
来源：http://dali.xylfe.cn/Article/details/gtcmusfqdy.html

f() { local x=1; echo "$x"; }
来源：http://dali.gogol.net.cn/Article/details/gtuxygcdsm.html

[R32] 参数个数校验
来源：http://dali.ivvv.top/Article/details/gtithbzuok.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtjudnuujl.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigufen.top/Article/details/gtzmjaoejm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinghuilouyu.cn/Article/details/gtujjfjxip.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtxconpxsk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtwlbnembu.html

[R35] 后台执行并等待
来源：http://dali.sweek.top/Article/details/gtmombtsux.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gtkdyzomji.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gtoztalnxc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yongpay.top/Article/details/gtamycihpf.html

[R37] 把输出赋给变量
来源：http://dali.tanke756.top/Article/details/gtqkzlcoog.html

files=$(ls -1)
来源：http://dali.haohaochexian.top/Article/details/gttmppcerc.html

[R38] 管道串联
来源：http://dali.zhengqikj.top/Article/details/gtppxqwncu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gtndsgbule.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gthizwkixp.html

cmd > out.log 2>&1
来源：http://dali.xinyue.icu/Article/details/gtmcwnaabk.html

[R40] 追加写日志
来源：http://dali.wangshuangyany.cn/Article/details/gtczjpvzob.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gtzkrvfros.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gtldxzmeld.html

cmd >/dev/null 2>&1
来源：http://dali.daria6918.cn/Article/details/gtvhzypblf.html

[R42] 输入重定向
来源：http://dali.ivvv.top/Article/details/gtwsqrigvj.html

wc -l < a.txt
来源：http://dali.cashguo.top/Article/details/gtlxwxqdwi.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gtnjmybeof.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gtkqlqifzx.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtdtamkdcf.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrczczeqb.html

[R45] 批量删除
来源：http://dali.hnxiangtu.top/Article/details/gtdphbaqxo.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxstfbim.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gtmuywsvaw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gtobxazqis.html

[R47] sed 单行替换
来源：http://dali.gzhubu.top/Article/details/gtbedfabwp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfownjtn.html

[R48] awk 取指定列
来源：http://dali.cdnleiting.top/Article/details/gtufixwamm.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gtofxvhjmb.html

[R49] awk 带条件
来源：http://dali.xziqi.cn/Article/details/gtvfedhafh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jyoumei.cn/Article/details/gtcmmkkghg.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gtwdtxchpv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guannengcc.top/Article/details/gtrzwwhkex.html

[R51] 排序去重取前几
来源：http://dali.yj20258888.top/Article/details/gtnnjmedvz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gtfhyjjhzv.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gtusskpjdh.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gtayyellva.html

[R53] 查看文件头与实时尾
来源：http://dali.zhixingplan.top/Article/details/gtdxrpqsse.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gtjdioztsj.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gthepvcuon.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtdvbqbbhr.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gtvwfkruzh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gtnhsdfcsw.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtzjzqycok.html

scp file user@host:/path/
来源：http://dali.smart0.xyz/Article/details/gtowpxfqek.html

[R57] 远程执行命令
来源：http://dali.kuanghao11.cn/Article/details/gthsmfuozw.html

ssh user@host 'uptime'
来源：http://dali.yj20258.top/Article/details/gtcscvvsuz.html

[R58] 下载文件
来源：http://dali.guowangkeji.top/Article/details/gtlmmntatg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gtfrtxcari.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtfqfbprfs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gtaipkguko.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtrjfohcvh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnxiangtu.top/Article/details/gthhhcrbvw.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxxexdlp.html

df -h;  du -sh *
来源：http://dali.jianghu66.top/Article/details/gterkykgqf.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gtjcyjgzuy.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gtquamopaf.html

[R63] 内存与进程
来源：http://dali.jiagoushi.top/Article/details/gtdejvqrup.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gtcemvkmst.html

[R64] 结束进程
来源：http://dali.yanxiufei.cn/Article/details/gtuzdbllbg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gtisveobns.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gthumsolbo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cheryme.top/Article/details/gttpiflcij.html

[R66] 定时任务
来源：http://dali.chenzaomai.com/Article/details/gtbzzmnhjo.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gtzezahkjq.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gtghylrqmq.html

openssl rand -hex 16
来源：http://dali.jqgfzy.top/Article/details/gtsyljjbhr.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrrfhwpk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gtbutsboha.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gtxtbxoihu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zdqjudy.top/Article/details/gtkuegljiy.html

[R70] 时间戳与互转
来源：http://dali.tianlin.xyz/Article/details/gtamahtggt.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gtavsjfrkp.html

[R71] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtwxsleprw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gtbizmjkmt.html

[R72] 等待端口就绪
来源：http://dali.tian-w.cn/Article/details/gteydcxmvi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtyrbsnzvj.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gtxbdknnid.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gtapkbariz.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gtglpbjkyn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258.top/Article/details/gtosiwpskt.html

[R75] 导出环境变量
来源：http://dali.hywenlv.cn/Article/details/gtulxpdcjw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gtmdnhzwtl.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtnnzfxspt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtsvilhnxs.html

[R77] 读取用户输入
来源：http://dali.shuidangran.top/Article/details/gtvqzyxikm.html

read -rp "请输入: " ans
来源：http://dali.yj202588.top/Article/details/gtopveieqm.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxudoaxw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gtqqyfbjxv.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gtaxwfukpv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gtbrbbuvhu.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gtitnbbcut.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gthqiyxdew.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmlaggliq.html

S. C / C++ 专题
来源：http://dali.0kj1m.cn/Article/details/gttxrptrew.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlfputapj.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gtnsqijqpc.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gtmkmmvuar.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.birdmap.top/Article/details/gtbsauadkw.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtqwrlthnn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zdqjudy.top/Article/details/gtipexrzrw.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gtqwvdvpju.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gtfhrwqkdn.html

[S04] C：字符串复制
来源：http://dali.smart0.xyz/Article/details/gtmtjzafzx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shzxlz.cn/Article/details/gtrseiykar.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxnbulwq.html

strlen(s)
来源：http://dali.vqdsnc.cn/Article/details/gtfbujhtor.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtcrisyjkc.html

strcmp(a, b) == 0
来源：http://dali.hywenlv.cn/Article/details/gtxzelroyx.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gtoubpokzn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtmgiozovu.html

[S08] C：动态内存分配与释放
来源：http://dali.nwbrower.top/Article/details/gtccqhhmvi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gtekmfxqpr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gtkvxxqlfj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gtpugqjwmk.html

[S10] C：指针与解引用
来源：http://dali.jiagoushi.top/Article/details/gtfkpnyqbe.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gtyqarqhcb.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtjgpnxxrz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gtfgilbjbr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsnopyfs.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtmnbiabto.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gtujlpchoo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtbsspuxah.html

[S13] C：宏定义
来源：http://dali.jianghu66.top/Article/details/gtuiswbnwm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gtzeoixawd.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtkpxbqnhe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tanke756.top/Article/details/gtpausjvkn.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtlzqoetmh.html

(double) a / b
来源：http://dali.316326.xyz/Article/details/gtoxmmwedh.html

[S16] C：位操作置位
来源：http://dali.gogol.net.cn/Article/details/gtfxtjipaf.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtjsiqczvf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtdxrdaqqb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hammf.cn/Article/details/gtfkjzphbs.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gtbtjwozxc.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtudyhunme.html

[S19] C：快速排序
来源：http://dali.zhiwuduotai.top/Article/details/gtncdknsdl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtuwqsigvz.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gtymhzebxs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtfnteywib.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gtnnjdbrcl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gtntmhjeqk.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtcwidtfsu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yvedp.cn/Article/details/gtaornokiu.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtjyfddpvj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtgnvrfhxx.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gtqthzjkgc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gturyvuzxc.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gtmyebegwh.html

memcpy(dst, src, n);
来源：http://dali.sufxvd.cn/Article/details/gtgdzyigfx.html

[S26] C：内存清零
来源：http://dali.havefunace.top/Article/details/gtdgbrqmmn.html


<!-- 参考信息 -->