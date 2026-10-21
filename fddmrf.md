代发 wailian999

[Q61] 移动平均
来源：http://dali.yangfankeji.com/Article/details/gtyqqixryg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtdxvwlzvy.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gtgxgckbrn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtoiivosrh.html

[Q63] 开启事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqafbvaqp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daxiang520.top/Article/details/gticulnzkm.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gttrjvpppq.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gtcsyrgain.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gtqwryoqft.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gtjcwdtfte.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gtljycmuyt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.smart0.xyz/Article/details/gthvbumkhl.html

[Q67] 设置隔离级别
来源：http://dali.nanxuanxn.top/Article/details/gtminarmdn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxuanxn.top/Article/details/gtroggyote.html

[Q68] 保存点
来源：http://dali.jyoumei.cn/Article/details/gtpwcnxoqc.html

SAVEPOINT sp1;
来源：http://dali.wangdashe.top/Article/details/gtepduevgg.html

ROLLBACK TO sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtjwbglmii.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gtbiyinoli.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gtsshuvxym.html

[Q70] 更新统计信息
来源：http://dali.cucudq.cn/Article/details/gtxhxtbzay.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gtkhoidees.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gtqjokaqac.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhengqikj.top/Article/details/gtoynmyykk.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gtavvrjdae.html

SHOW INDEX FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtmypjdvvq.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gtffushqho.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gtdbooxqpn.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gtefdhzbjm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gtykdrkbln.html

[Q75] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gttvlshqxm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtyrlktjca.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.feifeiyinyue.top/Article/details/gtjnsowmrq.html

[Q76] 按天统计
来源：http://dali.yuxming.cn/Article/details/gtwtzagrel.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gttwzgcjqz.html

[Q77] 时间加减
来源：http://dali.xylfe.cn/Article/details/gtjujqzabk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cashguo.top/Article/details/gtybfkchnl.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gttexmyonn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gtvjueqrrj.html

[Q79] 字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtrnbeskkz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.mhx1999.top/Article/details/gtpahqkpya.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gtwemzsgfy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtgkenrtom.html

[Q81] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtmxvcmsqw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.andypj.xyz/Article/details/gtawzendjf.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gthbaolqzm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtjvbnryct.html

[Q83] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtjhglabqg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtcguywukb.html

[Q84] 去除首尾空格
来源：http://dali.jinqigfzy.top/Article/details/gtfqdvhahm.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtckvhnxoe.html

[Q85] 数值取整
来源：http://dali.jqgufenzy.top/Article/details/gtwklstdic.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpzimafh.html

[Q86] 读取 JSON 字段
来源：http://dali.shangyingyoupin.top/Article/details/gtrtgnhdob.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gtlpetxfaf.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gtyeoyclhr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtxlioznph.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj202588.top/Article/details/gtbzalunfb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuanzhike.top/Article/details/gtspgvhqih.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtmpcypkuv.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gtolcbphho.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenlongwang.top/Article/details/gttjhkkpjs.html

[Q90] 生成序号列
来源：http://dali.wangshuangyany.cn/Article/details/gtxisythci.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gtnuidmzsg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksvwstyd.html

R. Bash 专题
来源：http://dali.bjfxy.top/Article/details/gtswimomcl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkomysnra.html

[R01] shebang 与严格模式
来源：http://dali.yuanzhike.top/Article/details/gthiwrahqa.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gtakchzdqj.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gtonlpxajr.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gtcjupcjph.html

name="Tom"; echo "$name"
来源：http://dali.yonumen.top/Article/details/gtbivwnour.html

[R03] 只读变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtbldxoz.html

readonly PI=3.14
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkwxrqgb.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gttdtkhjln.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gtogglkfiy.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gtrygarshf.html

name="${1:-default}"
来源：http://dali.jinqigufen.top/Article/details/gtqnirkiml.html

[R06] 判断命令是否存在
来源：http://dali.zdqjudy.top/Article/details/gtvxwkswrh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtglgkadut.html

[R07] if 判断文件
来源：http://dali.cashguo.top/Article/details/gtpphimyfv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yongpay.top/Article/details/gteymkwjer.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gtuvgpyfgs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtnoopgpwm.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtynmddlso.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtgjwnxpre.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gtqnekkamu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtnpexxtvo.html

[R11] case 多分支
来源：http://dali.hnxiangtu.top/Article/details/gtljbqmfjd.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtulurzlvs.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gtcleqgjle.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gttejukppi.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gtgwxzmlew.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gtgqrfkqpk.html

[R12] for 遍历文件
来源：http://dali.aizwys.cn/Article/details/gtitjrnhqi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtqdruahxn.html

[R13] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gtcbpchmop.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxnsrivc.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gttlhlwfow.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gttocoteli.html

[R15] while 逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtbaijzodd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhixingplan.top/Article/details/gtrwooufhp.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gtkceadqjm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtrictnsir.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwdmcblw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gtkxmogeok.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gtkgtnaqjw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fzhhl.top/Article/details/gtzsiktbvo.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtwjzeooqc.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gtxdxoxmjr.html

[R20] 关联数组（字典）
来源：http://dali.hnqzz.top/Article/details/gtxwejpykq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.c1oappe.top/Article/details/gtnufxmoed.html

[R21] 字符串长度
来源：http://dali.redwolf501.top/Article/details/gttkvipgcz.html

echo "${#s}"
来源：http://dali.kuanghao11.cn/Article/details/gtsyfproqv.html

[R22] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtubsutbzo.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnqauhzy.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtrzkjabhd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.316326.xyz/Article/details/gtfcqpgnab.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtyzgdcjua.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daxiang520.top/Article/details/gtuadzlmqx.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gtgztalhst.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.vqdsnc.cn/Article/details/gtyooubqec.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gtctuboqqa.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gtwpdsckyp.html

[R27] 算术展开
来源：http://dali.haohaochexian.top/Article/details/gtyckeadbz.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnklrpae.html

[R28] 浮点运算
来源：http://dali.gaohongyu789.top/Article/details/gtrjyeccjs.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhiwuduotai.top/Article/details/gtaxniipnr.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtikjocmfj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ivvv.top/Article/details/gtnhbhlice.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gtmfyjrvxg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhoulong.xyz/Article/details/gtaixnzojx.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gtivdyuhzy.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gtxziythcg.html

[R32] 参数个数校验
来源：http://dali.hnqzz.top/Article/details/gtuxbniszm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtprxedkkv.html

[R33] 捕获错误并提示行号
来源：http://dali.xuetiantiany.cn/Article/details/gtqgpcpond.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtwryafjxz.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gtuvneuqgd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtexhvtsem.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gtumtvzeha.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybzebkjz.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gtkhbcqrrh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gzhubu.top/Article/details/gtpwpmsjib.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gtiwdjpblw.html

files=$(ls -1)
来源：http://dali.chenjidiqi.icu/Article/details/gttffepcri.html

[R38] 管道串联
来源：http://dali.zhengqikj.top/Article/details/gtutwjrdpv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sweek.top/Article/details/gtxdwkfpdp.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtlcjusisr.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gtkuilyctf.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtxazauwmx.html

echo "log" >> out.log
来源：http://dali.tianlin.xyz/Article/details/gtmhinvxnk.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gtfpklpuec.html

cmd >/dev/null 2>&1
来源：http://dali.yueranfly.top/Article/details/gtnhudsbpb.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gtcfueeeaf.html

wc -l < a.txt
来源：http://dali.jiagoushi.top/Article/details/gtomblrxow.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gtjivxsqwc.html

find . -name "*.log" -type f
来源：http://dali.yj202588.top/Article/details/gtsxasghcv.html

[R44] 按修改时间查找
来源：http://dali.yvedp.cn/Article/details/gtnnjeeire.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gtskhlcope.html

[R45] 批量删除
来源：http://dali.meibo888.top/Article/details/gtvnblknnk.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gthqtauyhn.html

[R46] 递归替换文件内容
来源：http://dali.c1oappe.top/Article/details/gthafppalq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guowangkeji.top/Article/details/gtanepapaz.html

[R47] sed 单行替换
来源：http://dali.zdqjudy.top/Article/details/gtywchoobx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ybcxt.top/Article/details/gtawoamqxa.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtflsgrhbf.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtirnjouyx.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarvkxves.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.snrcjt.cn/Article/details/gtpwnnuzxp.html

[R50] awk 求和
来源：http://dali.nwbrower.top/Article/details/gtgxgnmgnh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtjzukaigs.html

[R51] 排序去重取前几
来源：http://dali.chenjidiqi.icu/Article/details/gthkeznoyl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gtomoplvzb.html

[R52] 统计行数
来源：http://dali.hfpthk.cn/Article/details/gtuqimrsub.html

wc -l a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtzwcsjsuh.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgufenzy.top/Article/details/gtpwaannng.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.andypj.xyz/Article/details/gtcrqrrgfp.html

[R54] 比较两个文件
来源：http://dali.chenzaomai.com/Article/details/gtqcpjeaqb.html

diff a.txt b.txt
来源：http://dali.sufxvd.cn/Article/details/gtehkytyyq.html

[R55] 压缩与解压
来源：http://dali.cheryme.top/Article/details/gtfsseymub.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmlsqopt.html

[R56] 远程拷贝
来源：http://dali.yongpay.top/Article/details/gtxprktgoz.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gtnfehnddb.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gtpwairxyc.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gtnddnuysb.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gtyqhltsam.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gtylogtxoj.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtbjyyljgn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gtkfcghswj.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtkhvoujru.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yonumen.top/Article/details/gthqcwfyjz.html

[R61] 磁盘占用
来源：http://dali.kuanghao11.cn/Article/details/gtwekjzimg.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gtveeabxvh.html

[R62] 找最占空间的文件
来源：http://dali.wangshuangyany.cn/Article/details/gtourwfeeg.html

du -ah . | sort -rh | head -10
来源：http://dali.guowangkeji.top/Article/details/gtffkbmjtl.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gtynphgzpu.html

free -h;  ps aux | grep nginx
来源：http://dali.ehwqpu.com/Article/details/gtywmhfrfa.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gtqjzeupjs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gtovvarhnm.html

[R65] 查看端口占用
来源：http://dali.hysaishi.cn/Article/details/gtqevsvfxr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gtgalzgtbn.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gtxterqdhm.html

crontab -e;  crontab -l
来源：http://dali.yangfankeji.com/Article/details/gtvbnqhrxv.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gtynrcrgmn.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gtumdrtnia.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gtdgixjmxp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gotoacloud.top/Article/details/gtepyodmnp.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwzeegrl.html

head -c 16 /dev/urandom | base64
来源：http://dali.shuidangran.top/Article/details/gtdyyrdsng.html

[R70] 时间戳与互转
来源：http://dali.c1oappe.top/Article/details/gtvwzxssqz.html

date +%s;  date -d @1700000000
来源：http://dali.ybcxt.top/Article/details/gtbkaaoenf.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtjzrlinid.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gtzwizrrex.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkbiprrb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtcxcvmmer.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrydwwjw.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gtefljccpp.html

[R74] 批量重命名
来源：http://dali.hywenlv.cn/Article/details/gtrfiluybl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gtftoiehqy.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gtjxdsmshq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuanzx.com/Article/details/gtdxwxlhha.html

[R76] 使用临时文件
来源：http://dali.aibaodan.cn/Article/details/gtawrhsdhs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gtidknfrjl.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gtusbbwyod.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gtvzqtxldz.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gtslwzdqux.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gtummopaxr.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gtflssnslm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shzxlz.cn/Article/details/gttoneeqtr.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gthexovhwy.html

time ./run.sh
来源：http://dali.redwolf501.top/Article/details/gtbrkgwqyw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtixpvydhh.html

S. C / C++ 专题
来源：http://dali.shzxlz.cn/Article/details/gtrnrjdbxq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtinqvtooy.html

[S01] C：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtwokfwcou.html

#include <stdio.h>
来源：http://dali.kuanghao11.cn/Article/details/gtrpjlznpi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gtdpzztndg.html

[S02] C：变量与格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtxpazzucn.html

int a = 10; printf("%d\n", a);
来源：http://dali.yanxiufei.cn/Article/details/gtaaqkpgso.html

[S03] C：读入整数
来源：http://dali.wangshuangyany.cn/Article/details/gtxfcjnenp.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gtqktlmisk.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gtpzvquovw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gticerzxpw.html

[S05] C：字符串长度
来源：http://dali.daxiang520.top/Article/details/gtxduxrzew.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gttetwleyy.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gtjivuworz.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gtnblshxur.html

[S07] C：数组遍历求和
来源：http://dali.yangfankeji.com/Article/details/gtdqoebzfi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gtukuiqpgq.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gtcznbcnks.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gtxeafyefw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gtsjutraei.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gtfbijyzay.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gtrbkfilvk.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gttegpssjd.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gteyysbuwp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gtdkftjwbf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gttlevbfym.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtofvthmbc.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gtflrxvipf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudhsbczv.html

[S13] C：宏定义
来源：http://dali.cdnleiting.top/Article/details/gtbgpipejs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenzaomai.com/Article/details/gtxeclktkq.html

[S14] C：枚举
来源：http://dali.gzhubu.top/Article/details/gtdqvauzfc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gtebanayxw.html

[S15] C：类型转换
来源：http://dali.zhengqikj.top/Article/details/gtlglxywfh.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gtxtqxjceo.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gtuqkfavrw.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtvncnxypt.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtkujlmyrz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtvzezwezv.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gtqvprfkxr.html

int main(int argc, char **argv)
来源：http://dali.xuetiantiany.cn/Article/details/gtzkstwbwq.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtldkdgibh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtbascvgfu.html

[S20] C：二分查找
来源：http://dali.hfpthk.cn/Article/details/gtlhnrjspe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtghidmchd.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gtwjbhxkwh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gtjokhizng.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gtsnrtkxff.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gttlcbcydr.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gtnluprfhl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrfokfdd.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gtmcoosivg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gtnmwhsadv.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gtsksnwghx.html

memcpy(dst, src, n);
来源：http://dali.pengpengdd.cyou/Article/details/gtsvkevvpg.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gtvhgxiaqo.html

memset(a, 0, sizeof a);
来源：http://dali.hongshengwenyu.top/Article/details/gthkpicwtt.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtegarpqsr.html

const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtekpantsr.html

[S28] C：静态变量
来源：http://dali.hywenlv.cn/Article/details/gtxmiubrwt.html

static int counter = 0;
来源：http://dali.yuanzhike.top/Article/details/gtclsnfgke.html

[S29] C：变参函数
来源：http://dali.ydzc1.top/Article/details/gtiywyezfs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gtttlhrtkn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gtrwgzdrgi.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtpncqgavr.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gtuhzsudef.html

#endif
来源：http://dali.bjfxy.top/Article/details/gtycmmhidh.html

[S31] C++：Hello World
来源：http://dali.xinyue.icu/Article/details/gtcvfvgxbv.html


<!-- 参考信息 -->