代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxozcasq.html

[Q58] 累计求和
来源：http://dali.zhiwuduotai.top/Article/details/gtqneuyeuk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gtzxwkgyvz.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gtyttfdoek.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtqaesyecv.html

[Q60] 取上一行 / 下一行
来源：http://dali.0kj1m.cn/Article/details/gtyfpwxbin.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gtkepgdafp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtogxhtiwi.html

[Q61] 移动平均
来源：http://dali.andypj.xyz/Article/details/gttomqqsap.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtmrfclvuv.html

[Q62] 分组占比
来源：http://dali.shzxlz.cn/Article/details/gtpvbfkgop.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtyjzncrkt.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gtnhbposau.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gtcjiadxzy.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gtzlpvhqbc.html

COMMIT;
来源：http://dali.sysykeji.top/Article/details/gtielufnvo.html

[Q65] 回滚事务
来源：http://dali.nwbrower.top/Article/details/gtvyckzzsu.html

ROLLBACK;
来源：http://dali.gogol.net.cn/Article/details/gtqjklwpfw.html

[Q66] 行锁查询
来源：http://dali.tanke756.top/Article/details/gtelgzupne.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yangfankeji.com/Article/details/gtpfwnkenx.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gtusitxvob.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gttftzdjnn.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gtyzjfwtbg.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtchsfmbxz.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejtfipes.html

[Q69] 查看执行计划
来源：http://dali.yongpay.top/Article/details/gtxqkdtazr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gtcevkbcdb.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gtcjqendlr.html

ANALYZE TABLE users;
来源：http://dali.cucudq.cn/Article/details/gtzrfcfpmq.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gtavlyylgr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigfzy.top/Article/details/gttupxwhyz.html

[Q72] 查看索引
来源：http://dali.zdqjudy.top/Article/details/gtyjsjhrdb.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtcuvqpaqj.html

[Q73] 查看表状态
来源：http://dali.hywenlv.cn/Article/details/gtaltwvvff.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuxming.cn/Article/details/gtfznayhod.html

[Q74] 强制使用索引
来源：http://dali.ybcxt.top/Article/details/gtiodesgov.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.mhx1999.top/Article/details/gtzlirvvis.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtrmlnhvim.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtzgeqgqow.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdgsqjcr.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gtergvbyyd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhoulong.xyz/Article/details/gtnbsvdoek.html

[Q77] 时间加减
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbzxykyt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gtaofmibqo.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gtsevvpluo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gthrmtjnkp.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gtflkdhgum.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuanzx.com/Article/details/gtwmoskkca.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gtcogoehyp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aizwys.cn/Article/details/gttincwawf.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtlqmlphvf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtmpoedpkw.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gtnclprpge.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtimuazqhb.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtrdejwlbk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtrioedkaj.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gtpdajcdze.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtroxswisq.html

[Q85] 数值取整
来源：http://dali.chenjidiqi.icu/Article/details/gtchngyibf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gtlomhndij.html

[Q86] 读取 JSON 字段
来源：http://dali.xuanzx.com/Article/details/gteodnzdzu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gtractarbd.html

[Q87] JSON 字段做条件
来源：http://dali.cqqwz.cn/Article/details/gtnazrympe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yangfankeji.com/Article/details/gtrglhumoy.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gtodycnyzk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.havefunace.top/Article/details/gtbowrpysx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtntxskmvq.html

[Q89] 判断表是否存在
来源：http://dali.tian-w.cn/Article/details/gthscvserc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gtklxojwcu.html

[Q90] 生成序号列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwofzqhwx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gtymbljmsq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkhrovcds.html

R. Bash 专题
来源：http://dali.ppjwa.cn/Article/details/gtvccaitvn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtitangnzj.html

[R01] shebang 与严格模式
来源：http://dali.yj202588.top/Article/details/gtjmnyxpgo.html

#!/usr/bin/env bash
来源：http://dali.jqgfzy.top/Article/details/gtmeohinvg.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gtmwcbotcb.html

[R02] 变量赋值与使用
来源：http://dali.smart0.xyz/Article/details/gtwezetdoh.html

name="Tom"; echo "$name"
来源：http://dali.pengpengdd.cyou/Article/details/gtzuxfvtpj.html

[R03] 只读变量
来源：http://dali.daxiang520.top/Article/details/gtrbrdxyqn.html

readonly PI=3.14
来源：http://dali.cucudq.cn/Article/details/gtpttwbunj.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gtsxtegmfw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvoelqyuk.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gtejokbbtr.html

name="${1:-default}"
来源：http://dali.yonumen.top/Article/details/gtpurzbxoq.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtozunlcyo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtsysyczgi.html

[R07] if 判断文件
来源：http://dali.hnxiangtu.top/Article/details/gtfbgyehvz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gtzfsdvmxq.html

[R08] 数值比较
来源：http://dali.zycfv.cn/Article/details/gtrcwqpwaw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gthdmvivcq.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gttfjurakq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.meibo888.top/Article/details/gtunvjpycy.html

[R10] 正则匹配
来源：http://dali.jlsjyb.cn/Article/details/gtayjsmioy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tianlin.xyz/Article/details/gtyoojkzfp.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gtzpigulik.html

case "$1" in
来源：http://dali.gaohongyu789.top/Article/details/gtsbakuxzk.html

start) echo "启动" ;;
来源：http://dali.xinyue.icu/Article/details/gtvghjglvy.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitqjceqa.html

*)     echo "未知命令" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtwfqyfkug.html

esac
来源：http://dali.cashguo.top/Article/details/gtrbuldaoz.html

[R12] for 遍历文件
来源：http://dali.yongpay.top/Article/details/gtngyrxrao.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daxiang520.top/Article/details/gtgysquqcv.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gtkynqcvvv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gttmdumweo.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gtaydaskwh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtktlfkbxp.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gtebajunhf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gthfjcdhhf.html

[R16] until 等待条件
来源：http://dali.cucudq.cn/Article/details/gtkwzbrdvu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtvcahzpmp.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gtgsuwoodk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdnaupoi.html

[R18] 遍历数组
来源：http://dali.birdmap.top/Article/details/gtbwlamilr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guannengcc.top/Article/details/gtlvciyweg.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gteglnpskb.html

echo "${#arr[@]}"
来源：http://dali.sysykeji.top/Article/details/gtphwxqgsx.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gttclwyenx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqhishbe.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gtdcgvnugp.html

echo "${#s}"
来源：http://dali.tanke756.top/Article/details/gtgmjbwiml.html

[R22] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gtapnntewv.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gtiabokqxl.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtysvollnn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gtfyebjrua.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtphmupfre.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gtlgauyhhg.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangshuangyany.cn/Article/details/gtegqcvqvy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gtmxpgzrji.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gtspkecmya.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gtlehnyjmo.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtocsmirkd.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gtybkfsxfu.html

[R28] 浮点运算
来源：http://dali.sweek.top/Article/details/gtzxfsgkbj.html

echo "scale=2; 10/3" | bc
来源：http://dali.pycfn.com/Article/details/gtjnrirnki.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gtawuogcdk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gtrqemdkws.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtihbbgtde.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj202588.top/Article/details/gtlqylqzmx.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gtwzvrecpa.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gtyywvihyn.html

[R32] 参数个数校验
来源：http://dali.xuanzx.com/Article/details/gtwncqurap.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtoyycsrkz.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gtjzihntgn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxuanxn.top/Article/details/gtmkodajsz.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gtisiurcrz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtqsbjhawe.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtqohmksvx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gtrozatpuh.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gtrhahjfoa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtemmcslqz.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gtmordmbvd.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gtkdfibirs.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gtukusjxhu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gteajvmemy.html

[R39] 重定向标准输出与错误
来源：http://dali.zdqjudy.top/Article/details/gtofyzcilf.html

cmd > out.log 2>&1
来源：http://dali.c1oappe.top/Article/details/gtbjnoyupe.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gtghctrvdm.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gthyizpznj.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gtedcimrgu.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtimzfwuvg.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gtdhhossmv.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtjuvyfxdg.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gtyjhkiect.html

find . -name "*.log" -type f
来源：http://dali.cucudq.cn/Article/details/gtnrjlktrs.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gtivncqwgk.html

find . -mtime -7 -type f
来源：http://dali.tian-w.cn/Article/details/gtbouazyvt.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gtrwqugvip.html

find . -name "*.tmp" -delete
来源：http://dali.quarkkingdee.top/Article/details/gtsfuqunjh.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gtkmxcreui.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gtfbihrtcw.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gtlrhdipiz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gthdzpplna.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtnxwfbylo.html

awk '{print $1, $3}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtkyxzjwki.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtiwjybpmo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiaubmomh.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtqfgevrma.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gtjdzshbek.html

[R51] 排序去重取前几
来源：http://dali.9152youxi.cn/Article/details/gtndhmhhdn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.feifeiyinyue.top/Article/details/gtekvnhpmp.html

[R52] 统计行数
来源：http://dali.yueranfly.top/Article/details/gtofnkbbgd.html

wc -l a.txt
来源：http://dali.316326.xyz/Article/details/gtoywpflkh.html

[R53] 查看文件头与实时尾
来源：http://dali.quarkkingdee.top/Article/details/gthjcxqffq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gtakxjztar.html

[R54] 比较两个文件
来源：http://dali.cucudq.cn/Article/details/gtugyhpegz.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtqomeykff.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gtyrixlanq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gtwjgfhnco.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gtetophtkb.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gtkiajqerf.html

[R57] 远程执行命令
来源：http://dali.sufxvd.cn/Article/details/gtnbdooufu.html

ssh user@host 'uptime'
来源：http://dali.hongshengwenyu.top/Article/details/gtixjvzezg.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gtpmsxmiyw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.vqdsnc.cn/Article/details/gtxwwvutrq.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtbdeaboaf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiegedlcd.html

[R60] 只看 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtxvtqizat.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gtgjxkaujy.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gttesepjvn.html

df -h;  du -sh *
来源：http://dali.chenlongwang.top/Article/details/gteliybcas.html

[R62] 找最占空间的文件
来源：http://dali.zhixingplan.top/Article/details/gtajobkhcc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlicvcic.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gtkczmmxkd.html

free -h;  ps aux | grep nginx
来源：http://dali.pengpengdd.cyou/Article/details/gtiinubzzd.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gtvieqzygm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenlongwang.top/Article/details/gtqvmjnjim.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttkldkmy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gtpuhctcof.html

[R66] 定时任务
来源：http://dali.dianchejie.cn/Article/details/gtsckixiei.html

crontab -e;  crontab -l
来源：http://dali.sweek.top/Article/details/gtpuxzfpxh.html

[R67] 生成随机十六进制串
来源：http://dali.shangyingyoupin.top/Article/details/gtreqxldph.html

openssl rand -hex 16
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlnmsorb.html

[R68] 计算文件校验值
来源：http://dali.0kj1m.cn/Article/details/gtluesklaf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gtppjbgkck.html

[R69] 生成随机密码
来源：http://dali.kuanghao11.cn/Article/details/gtkkkqghin.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gtzkuyludp.html

[R70] 时间戳与互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkunthsig.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gtnnsecbqt.html

[R71] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtornzlcia.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gtffvkzywe.html

[R72] 等待端口就绪
来源：http://dali.cashguo.top/Article/details/gtcvmijsij.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtrjahmaxv.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gtbqisfeya.html

split -l 1000 big.log part_
来源：http://dali.havefunace.top/Article/details/gtjzxwabkw.html

[R74] 批量重命名
来源：http://dali.ybcxt.top/Article/details/gtzewffewy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fzhhl.top/Article/details/gtzlmbgzaj.html

[R75] 导出环境变量
来源：http://dali.haohaochexian.top/Article/details/gtteqahonu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gtqqsugthz.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gtdnsvysit.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gttjiefvwi.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gtpyemnbtg.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gtsltdqlsd.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gthalwxhmk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gtdfihlevm.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gtuyrqannv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gthdizlefl.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gtvebzaqcw.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gtmhqktfaj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgofkeknd.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gtqvxljayl.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfawcekqv.html

[S01] C：Hello World
来源：http://dali.wangdashe.top/Article/details/gtpdxbhwxp.html

#include <stdio.h>
来源：http://dali.zhiwuduotai.top/Article/details/gtbprfuayx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj202588.top/Article/details/gtjelzsitk.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtyksqygja.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gtyylorsck.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gthnyvmgjj.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gtmbdosuoq.html

[S04] C：字符串复制
来源：http://dali.kuanghao11.cn/Article/details/gtoyywkpnd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gttmetamzz.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtmtvxawgr.html

strlen(s)
来源：http://dali.redwolf501.top/Article/details/gtomuxxcrb.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gtolrgjkrr.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gtbegkckpt.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gtvwfxhdbw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jlsjyb.cn/Article/details/gtlnrjxoeh.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gtvpjqycvj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gtrrbhdfau.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gtrmsrfhxr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinghuilouyu.cn/Article/details/gtdchrbifz.html

[S10] C：指针与解引用
来源：http://dali.jiagoushi.top/Article/details/gteozztflo.html

int *p = &a;  *p = 5;
来源：http://dali.jiagoushi.top/Article/details/gtlehhhpfc.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gthzhctiwc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.meibo888.top/Article/details/gtdiovtssj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gtbxpxpvmu.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtbomokkys.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gtjuuscldk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmehvhrb.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gtsbphagfq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shuidangran.top/Article/details/gtuvfsnvys.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gtmnifvqgt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gtdecjunqt.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gtfmtutnhk.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gtyqmrxlrx.html

[S16] C：位操作置位
来源：http://dali.cucudq.cn/Article/details/gtzvwnzwaa.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtntehzwvj.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtklrrfbkv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gtsxyichic.html

[S18] C：命令行参数
来源：http://dali.cucudq.cn/Article/details/gtuqagqcsg.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gtxfcekypg.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gterjxyxjc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtswgjmdam.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gttxfhdmut.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gthndftuyt.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gtmhbyczcl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxinkj.top/Article/details/gtkxkwtstf.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gtohdgsqrq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj202588.top/Article/details/gtlekixvcy.html

[S23] C：随机数
来源：http://dali.yj20258.top/Article/details/gtbsbjhdcm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gtmdfwvtlt.html

[S24] C：获取本地时间
来源：http://dali.iojbl.cn/Article/details/gtzuefljll.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gtkjslpqrf.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gtchggkgkc.html

memcpy(dst, src, n);
来源：http://dali.jianghu66.top/Article/details/gtfingnclg.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gtkfqszhft.html

memset(a, 0, sizeof a);
来源：http://dali.yvedp.cn/Article/details/gtfqtcyqtj.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gtudxzozgu.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtuxqalbjj.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gtbscgnfjp.html


<!-- 参考信息 -->