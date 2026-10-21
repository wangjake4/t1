代发 wailian999

[Q61] 移动平均
来源：http://dali.guannengcc.top/Article/details/gtraknazuq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtvqbelzwd.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gtqgjkhkxn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtjkbdmohl.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gterntpnmq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sweek.top/Article/details/gtdgyrqwua.html

[Q64] 提交事务
来源：http://dali.pengpengdd.cyou/Article/details/gtqzyptmfp.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gtauvnmidw.html

[Q65] 回滚事务
来源：http://dali.sxryk.cn/Article/details/gtrejqbumy.html

ROLLBACK;
来源：http://dali.aibaodan.cn/Article/details/gtgirvgdjc.html

[Q66] 行锁查询
来源：http://dali.guowangkeji.top/Article/details/gtrkonbyty.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwljnjnyh.html

[Q67] 设置隔离级别
来源：http://dali.jyoumei.cn/Article/details/gterzrgqfq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daxiang520.top/Article/details/gtmrbdvszh.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gtewwaseun.html

SAVEPOINT sp1;
来源：http://dali.ybcxt.top/Article/details/gtsavcoavk.html

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gtobulxywc.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gtdfssqjip.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gtxwxnvvef.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gtpcmujvau.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gtbrlpljlj.html

[Q71] 查看建表语句
来源：http://dali.svipenyu.cn/Article/details/gtcdvddduy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.meibo888.top/Article/details/gtbsrtpczb.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gtndhabxun.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gtvqrlxgpd.html

[Q73] 查看表状态
来源：http://dali.cucudq.cn/Article/details/gtshgfmtli.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtnwpdywyi.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gtobmxslpy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guannengcc.top/Article/details/gtghsjcxcb.html

[Q75] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxhgsaiy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtkswwacod.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yonumen.top/Article/details/gtocxzvekp.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gtvmavhofn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gtzrwscxlb.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gtzjjiwola.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxinkj.top/Article/details/gtsmkqgsrv.html

[Q78] 当前时间
来源：http://dali.sufxvd.cn/Article/details/gtfbvvolrl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinghuilouyu.cn/Article/details/gtavhewxyi.html

[Q79] 字符串拼接
来源：http://dali.yonumen.top/Article/details/gtghoezhas.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gtfdwpidwj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gthudlpgzh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtapcrlihy.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtshxnxliy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtibmuxfcn.html

[Q82] 字符长度与字节长度
来源：http://dali.havefunace.top/Article/details/gtmyulbbff.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtucuggduo.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtximckxvp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtberzsuhq.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpatrxsav.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtnmqrjeha.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtvebieyfg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gttfafvcsg.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gthsrihbrv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jiagoushi.top/Article/details/gtaoxkskud.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258888.top/Article/details/gtfbmnyxcl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtspkmovlr.html

[Q88] 行转列（条件聚合）
来源：http://dali.vqdsnc.cn/Article/details/gtqumdevsz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gtqaeqpiwm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cucudq.cn/Article/details/gtgpytxqbb.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gtiennatrp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gthmlxichn.html

[Q90] 生成序号列
来源：http://dali.gogol.net.cn/Article/details/gtdpkmuruq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gttxbomgxa.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtgjflycmq.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gtrntkgedf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gttijaffuo.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemvaxeba.html

#!/usr/bin/env bash
来源：http://dali.gaohongyu789.top/Article/details/gtreokptds.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gtboktuyxt.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gtrjonxree.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gtxpdoifnu.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gtpnyjepos.html

readonly PI=3.14
来源：http://dali.feifeiyinyue.top/Article/details/gtykguaroi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gtgdbapbre.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.svipenyu.cn/Article/details/gtpzdcziyk.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gtyxixruzj.html

name="${1:-default}"
来源：http://dali.nwbrower.top/Article/details/gtbgijsyid.html

[R06] 判断命令是否存在
来源：http://dali.dashuyun.cn/Article/details/gttqqvioob.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtwuphwjgg.html

[R07] if 判断文件
来源：http://dali.shuidangran.top/Article/details/gtkcualobv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ybcxt.top/Article/details/gthmdvhskz.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gtncaqbmjf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gtgeoqxxhp.html

[R09] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvanpmngo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gtdhqapnxh.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gtsuwjmpet.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtcceyygkb.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gtvancatwj.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gtnohpcjsa.html

start) echo "启动" ;;
来源：http://dali.yuanzhike.top/Article/details/gtjywprbqq.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gthyeltwhd.html

*)     echo "未知命令" ;;
来源：http://dali.aibaodan.cn/Article/details/gtnwzsqizd.html

esac
来源：http://dali.shuidangran.top/Article/details/gtebpdtqfi.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gtysqukcik.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gtqgxqqyxi.html

[R13] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gtuectjfgk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtzglbdmsn.html

[R14] C 风格 for
来源：http://dali.aizwys.cn/Article/details/gtxykduwsf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtenhweqch.html

[R15] while 逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtaofqaqbk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtjhvtguef.html

[R16] until 等待条件
来源：http://dali.wangshuangyany.cn/Article/details/gtgbpvvmim.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtdmpzmcoc.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gtyqcdhgfu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gtftawxtif.html

[R18] 遍历数组
来源：http://dali.dashuyun.cn/Article/details/gtfamlxwwy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gtwpugftiz.html

[R19] 数组长度
来源：http://dali.andypj.xyz/Article/details/gtuhzhneva.html

echo "${#arr[@]}"
来源：http://dali.xuanzx.com/Article/details/gtsquxelui.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gtzdxssjmx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gtlxukkmnh.html

[R21] 字符串长度
来源：http://dali.yueranfly.top/Article/details/gtqyqvpupp.html

echo "${#s}"
来源：http://dali.kuanghao11.cn/Article/details/gtnjgosysi.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtvxihodpr.html

echo "${s:0:5}"
来源：http://dali.wangshuangyany.cn/Article/details/gtzkzivlxc.html

[R23] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gtygqcnafk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gtbeacaavw.html

[R24] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtvvuhuvvw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gtdzmjjhxc.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gtjrtxacgw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gtoyoyixsu.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gtrpxbylsm.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gtsqdbpmys.html

[R27] 算术展开
来源：http://dali.jinqigfzy.top/Article/details/gtlulzajwh.html

echo $((1 + 2 * 3))
来源：http://dali.jqgfzy.top/Article/details/gtrucnjzzh.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gtgkjevgtz.html

echo "scale=2; 10/3" | bc
来源：http://dali.shangyingyoupin.top/Article/details/gtbuwkfjlh.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtlniradcg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gtryjnzcxc.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gtrjmvzgrb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gtpzktxpcw.html

[R31] 局部变量
来源：http://dali.yuanzhike.top/Article/details/gtijqlveie.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbrmikzlg.html

[R32] 参数个数校验
来源：http://dali.hnqzz.top/Article/details/gtoezdpcuj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gthmgrbrco.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gttxftdezn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gtcvvfixgc.html

[R34] 退出时清理
来源：http://dali.c1oappe.top/Article/details/gtoafrskex.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gttnsotrjr.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gttekaxpjj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ppjwa.cn/Article/details/gtxlhhsnzj.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gtbrtqnamq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenzaomai.com/Article/details/gtfbrvkmqa.html

[R37] 把输出赋给变量
来源：http://dali.havefunace.top/Article/details/gtrfnqnlts.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gtwltfzysb.html

[R38] 管道串联
来源：http://dali.svipenyu.cn/Article/details/gtgdjnahwf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtgrfbmlij.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gtnqcjxmiy.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtfrzrgtkl.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gtlauarbkx.html

echo "log" >> out.log
来源：http://dali.gzhubu.top/Article/details/gtbfxkgavb.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gthdhrrofi.html

cmd >/dev/null 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtxqblbxkp.html

[R42] 输入重定向
来源：http://dali.kuanghao11.cn/Article/details/gthgeozdel.html

wc -l < a.txt
来源：http://dali.xziqi.cn/Article/details/gtboihmpil.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gtjzvicyyf.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbwxnlmi.html

[R44] 按修改时间查找
来源：http://dali.aizwys.cn/Article/details/gtvstngssd.html

find . -mtime -7 -type f
来源：http://dali.sufxvd.cn/Article/details/gtuoeysmeg.html

[R45] 批量删除
来源：http://dali.ehwqpu.com/Article/details/gtkemsimln.html

find . -name "*.tmp" -delete
来源：http://dali.nanxinkj.top/Article/details/gtaifkylem.html

[R46] 递归替换文件内容
来源：http://dali.shzxlz.cn/Article/details/gtpefeqpsd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sxryk.cn/Article/details/gtpktikuqh.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gtxmilbnio.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gtfydrqqcj.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtvyruzrfk.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtqlufhpsm.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gtlnclnsxy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gogol.net.cn/Article/details/gtfzkxidas.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gtgaxhmxcs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtwewmspkn.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gtvruzqcjp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gotoacloud.top/Article/details/gtsuqpepzb.html

[R52] 统计行数
来源：http://dali.aizwys.cn/Article/details/gttotfbdgf.html

wc -l a.txt
来源：http://dali.316326.xyz/Article/details/gtfdoqnbgn.html

[R53] 查看文件头与实时尾
来源：http://dali.jlsjyb.cn/Article/details/gtcyhypjam.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gtuhtucakw.html

[R54] 比较两个文件
来源：http://dali.daxiang520.top/Article/details/gtkxcxpzam.html

diff a.txt b.txt
来源：http://dali.tianlin.xyz/Article/details/gtgiaynpwl.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gtyvkmtgct.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxkgnaej.html

[R56] 远程拷贝
来源：http://dali.bjfxy.top/Article/details/gtkoyrfwwq.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gtntdafldc.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gtkmpesglz.html

ssh user@host 'uptime'
来源：http://dali.wangdashe.top/Article/details/gtijkntosz.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gtoerplnuz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gtvtqdgbev.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtmtmtczyf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgccmifa.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtgzotysqs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuxming.cn/Article/details/gtqyjfafip.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gtartebovj.html

df -h;  du -sh *
来源：http://dali.wangdashe.top/Article/details/gtkdymreha.html

[R62] 找最占空间的文件
来源：http://dali.hammf.cn/Article/details/gtwyxvcjnm.html

du -ah . | sort -rh | head -10
来源：http://dali.tianlin.xyz/Article/details/gtbpfeiatw.html

[R63] 内存与进程
来源：http://dali.yongpay.top/Article/details/gtgfceovqo.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gtxrogmham.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gtqupudbxo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gtfyshream.html

[R65] 查看端口占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhzrzzhl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pengpengdd.cyou/Article/details/gtdihtrwdx.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gtdvlqxmlg.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gtxiccviio.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gtplzjcgtl.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gtzlkdvjfp.html

[R68] 计算文件校验值
来源：http://dali.jianghu66.top/Article/details/gtpkyfiprv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gtxrucnurx.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gthdscheon.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gthucvvuzz.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtfspphpzw.html

date +%s;  date -d @1700000000
来源：http://dali.pengpengdd.cyou/Article/details/gtpbzqoyfx.html

[R71] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtxxcryayd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gtghhjsbuh.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gtdhhhcziz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtdyzfzxjm.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gtmwnunduu.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gtaxoumuls.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixcapapy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhixingplan.top/Article/details/gthittxqdo.html

[R75] 导出环境变量
来源：http://dali.jiagoushi.top/Article/details/gtfnjsipuv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhoulong.xyz/Article/details/gtwifbbtke.html

[R76] 使用临时文件
来源：http://dali.yongpay.top/Article/details/gtxphsbyma.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gteqvirxmb.html

[R77] 读取用户输入
来源：http://dali.316326.xyz/Article/details/gtwconcaai.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gtgnndorag.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gtzmjsvkqf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gtupnqgjcj.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gtxixxdqyi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guowangkeji.top/Article/details/gtpsspnqki.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gtehfjvxyf.html

time ./run.sh
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodhtsork.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gthtcmhqpi.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtvmmhlofp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtevngukgg.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtjefgrufo.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gtonfitffw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yanxiufei.cn/Article/details/gtzbrcwxcc.html

[S02] C：变量与格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtygqchdym.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gtbaossazm.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gtpcmmlfaq.html

int x; scanf("%d", &x);
来源：http://dali.xuetiantiany.cn/Article/details/gtsvlpqzwi.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gtafnbctlw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gtrubgwmhy.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzabolteb.html

strlen(s)
来源：http://dali.hnxiangtu.top/Article/details/gtqbxljwxv.html

[S06] C：字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtovtghpqa.html

strcmp(a, b) == 0
来源：http://dali.tanke756.top/Article/details/gtpvgnbhlr.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gteoajokdm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gtyicrzxuz.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gtywbpivwq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gttivtyeuj.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gtavfmarqn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yonumen.top/Article/details/gtuevvcqjy.html

[S10] C：指针与解引用
来源：http://dali.cheryme.top/Article/details/gtmdsujzav.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gtbbadkfdi.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtsjuehzjc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gtbffsqnts.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtlctyncik.html

fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtniymhohl.html

[S12] C：写文件
来源：http://dali.havefunace.top/Article/details/gtigbedntu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkufndbrz.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gtsyeuizhe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gtdwxdryxa.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gtynsejrmr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.c1oappe.top/Article/details/gtbdllwjxx.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gtdamjdvrd.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gtkytuarpz.html

[S16] C：位操作置位
来源：http://dali.hnxiangtu.top/Article/details/gtzszjiiwu.html

x |= (1 << 3);
来源：http://dali.cheryme.top/Article/details/gtjyjfhmsv.html

[S17] C：安全拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvgnntes.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gtcynsdyjv.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtpoyruodk.html

int main(int argc, char **argv)
来源：http://dali.hammf.cn/Article/details/gtkiewsetf.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtjgpwcwep.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtbdmnadbm.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gtepjkrvwb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gtwpicfued.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gtzarbmmfo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gthxqkqkpe.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gtpqxoxeol.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cdnleiting.top/Article/details/gtjoueflhh.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gtmogxdhyg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xziqi.cn/Article/details/gtazsbykfg.html

[S24] C：获取本地时间
来源：http://dali.yueranfly.top/Article/details/gtndvosqhk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gtxmkjuwau.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtwwnpnapx.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gtddzsuxnr.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gtsvfubigb.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gtuiwenrkp.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gtxjtfiaxk.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtqbimpwce.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gtgygbhlws.html

static int counter = 0;
来源：http://dali.quarkkingdee.top/Article/details/gtxvxmzqea.html

[S29] C：变参函数
来源：http://dali.haohaochexian.top/Article/details/gtrxfnbynh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gtirqrlgtb.html

[S30] C：头文件保护
来源：http://dali.cdnleiting.top/Article/details/gtdoedfzlr.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gtoerqtegr.html

#define X_H
来源：http://dali.zycfv.cn/Article/details/gtkxhxmvyw.html

#endif
来源：http://dali.c1oappe.top/Article/details/gtthrfkprn.html

[S31] C++：Hello World
来源：http://dali.bjfxy.top/Article/details/gtwhqjuqiy.html


<!-- 参考信息 -->