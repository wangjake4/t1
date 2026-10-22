代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtphstwnic.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gtfwnlatgz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtgklmjecs.html

[Q57] 行号
来源：http://dali.xinyue.icu/Article/details/gttgctxiwr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtqjmtqltq.html

[Q58] 累计求和
来源：http://dali.meibo888.top/Article/details/gtwssqqlvi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtjjppmbfg.html

[Q59] 分组内累计
来源：http://dali.sysykeji.top/Article/details/gttwzaridc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtjjfudjzq.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgfzy.top/Article/details/gtraswxmpo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.bjfxy.top/Article/details/gtilfeapow.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtguzvnbcu.html

[Q61] 移动平均
来源：http://dali.dashuyun.cn/Article/details/gtzmmjvoeo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtstnnpfph.html

[Q62] 分组占比
来源：http://dali.mhx1999.top/Article/details/gtbeeqprmu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbssohhsd.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gtfjnkyrpz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gtmfgweapo.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gtttjyqlgo.html

COMMIT;
来源：http://dali.0kj1m.cn/Article/details/gtranttirc.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gtdfulpjdr.html

ROLLBACK;
来源：http://dali.jqgufenzy.top/Article/details/gtnfqlkzxd.html

[Q66] 行锁查询
来源：http://dali.aibaodan.cn/Article/details/gtrdjhzmgn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gtdjfpvlbu.html

[Q67] 设置隔离级别
来源：http://dali.cashguo.top/Article/details/gtxevnpegr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cdnleiting.top/Article/details/gtonlctnuf.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gtvfxbnqdc.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gtannvhjqo.html

ROLLBACK TO sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtfqfqpjgo.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtkddxnalo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gtjzhzqaam.html

[Q70] 更新统计信息
来源：http://dali.haohaochexian.top/Article/details/gtmelvdeef.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gtyhymaxmo.html

[Q71] 查看建表语句
来源：http://dali.kuanghao11.cn/Article/details/gtbhbcfacv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yongpay.top/Article/details/gtjfdtjebk.html

[Q72] 查看索引
来源：http://dali.jyoumei.cn/Article/details/gtrldfjaep.html

SHOW INDEX FROM users;
来源：http://dali.havefunace.top/Article/details/gtjqqgmtwi.html

[Q73] 查看表状态
来源：http://dali.meibo888.top/Article/details/gtcudyaqqi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gtslhtrcza.html

[Q74] 强制使用索引
来源：http://dali.jinqigufen.top/Article/details/gtpotpgphq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gtqcpztujt.html

[Q75] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtrlnlwgjj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tanke756.top/Article/details/gtjdksdbkg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnxiangtu.top/Article/details/gtiewlfuuy.html

[Q76] 按天统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynsepydp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.haohaochexian.top/Article/details/gtiwzdjhmi.html

[Q77] 时间加减
来源：http://dali.cdnleiting.top/Article/details/gtslsgtjce.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhongyouzk.top/Article/details/gtpvbzsdrg.html

[Q78] 当前时间
来源：http://dali.bjfxy.top/Article/details/gtidzwdlun.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sufxvd.cn/Article/details/gtreoqfelo.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtijlnxliy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gtgdwlmwfj.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gtkhncwquu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gthoffjjvv.html

[Q81] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtwtzflqic.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sysykeji.top/Article/details/gtdiezvavy.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gtvdlpnwao.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtqxfymoua.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtnnjpxejb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtkmjrptpn.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gtbdqchhxr.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtaetmpzgo.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtpseqcxve.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgfzy.top/Article/details/gtofpsdkwi.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gtqskitmzg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gtmaxfcqvf.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigfzy.top/Article/details/gtiftoyuby.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtnsznygsl.html

[Q88] 行转列（条件聚合）
来源：http://dali.yanxiufei.cn/Article/details/gtqzjajyjr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gtochgfsaw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj202588.top/Article/details/gtfxympnbg.html

[Q89] 判断表是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtpwigkzji.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gtthrctyid.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gtepwkzcgz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gtcrfkihnm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtqtenyvvf.html

R. Bash 专题
来源：http://dali.vqdsnc.cn/Article/details/gtcczgmqpq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxrzohjxn.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gtjdtsizav.html

#!/usr/bin/env bash
来源：http://dali.haohaochexian.top/Article/details/gthfszvmqd.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gtrmawgxaq.html

[R02] 变量赋值与使用
来源：http://dali.yueranfly.top/Article/details/gtkqgqedkv.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gtorigxscm.html

[R03] 只读变量
来源：http://dali.cqqwz.cn/Article/details/gtugdzoajn.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gtkftednjt.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gtihtntwwk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gtekjmnout.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gtxnwcdaza.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gtquvabefw.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gtylwaopjv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtnifddfdi.html

[R07] if 判断文件
来源：http://dali.birdmap.top/Article/details/gtjczyfjkz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtfnzfwhoj.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtwqawgcjo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sweek.top/Article/details/gtihyfykeu.html

[R09] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfqyywwt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sufxvd.cn/Article/details/gtzlwyghpc.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gtdgruduab.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gogol.net.cn/Article/details/gtpsgdywpv.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtngrnzwsi.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gtfbhiunur.html

start) echo "启动" ;;
来源：http://dali.havefunace.top/Article/details/gtkpciymgg.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdypwubt.html

*)     echo "未知命令" ;;
来源：http://dali.xinyue.icu/Article/details/gtruqhdjkv.html

esac
来源：http://dali.nanxinkj.top/Article/details/gtexhkzqsz.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gtsckmtpuw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.meibo888.top/Article/details/gtxbulbmlt.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gtciijqffy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtkzvgmtru.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gtahgydmkm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gttzyubage.html

[R15] while 逐行读文件
来源：http://dali.yj202588.top/Article/details/gtchejqiie.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gtmbgobbam.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gtndrfbfgg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gtqqvpajdn.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gtfiskdwgg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gtrwfapekd.html

[R18] 遍历数组
来源：http://dali.chenzaomai.com/Article/details/gtnnrrejnf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ybcxt.top/Article/details/gtxaasrswe.html

[R19] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtkevmtfyy.html

echo "${#arr[@]}"
来源：http://dali.hammf.cn/Article/details/gtfctjepvj.html

[R20] 关联数组（字典）
来源：http://dali.hywenlv.cn/Article/details/gtuvsnyugq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtqetpdvku.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtorazzktv.html

echo "${#s}"
来源：http://dali.c1oappe.top/Article/details/gtjyuwbglp.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtrexpmghr.html

echo "${s:0:5}"
来源：http://dali.vqdsnc.cn/Article/details/gtscywkezp.html

[R23] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtbocphvof.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gtedujlakf.html

[R24] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtghgyiatp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gtyloohtsg.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gtwrfdroxm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnpkjeao.html

[R26] 命令替换
来源：http://dali.yangfankeji.com/Article/details/gtezrcyicj.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gttvxpgrkm.html

[R27] 算术展开
来源：http://dali.yonumen.top/Article/details/gtmgwexpjr.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gtocksuacd.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gtrwzllaaq.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gtmqzuahxd.html

[R29] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gthxrljicv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gtjayjfncy.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gtukbaqizb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangdashe.top/Article/details/gtkzflkmjz.html

[R31] 局部变量
来源：http://dali.hnqzz.top/Article/details/gtqgntuwkb.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtjnrjeuwr.html

[R32] 参数个数校验
来源：http://dali.hnxiangtu.top/Article/details/gtupihsksl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gtmradnqly.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtdfjxlsrw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gtqhrxcjfk.html

[R34] 退出时清理
来源：http://dali.yvedp.cn/Article/details/gtdzzztjgf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiorcltfm.html

[R35] 后台执行并等待
来源：http://dali.cheryme.top/Article/details/gtyzrrfasa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xinyue.icu/Article/details/gtkoseqpiy.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gtvoamenbs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gtxkqfzuom.html

[R37] 把输出赋给变量
来源：http://dali.guowangkeji.top/Article/details/gtzrgiigdi.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtztcoyqil.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gtmgovjxqm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtrqtkykwa.html

[R39] 重定向标准输出与错误
来源：http://dali.jlsjyb.cn/Article/details/gtnffhjfwi.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtavpdqbil.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gtzguyxsji.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gtsndwuptt.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gtmbzeqwuy.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gtptazxgfl.html

[R42] 输入重定向
来源：http://dali.meibo888.top/Article/details/gtucxcftnf.html

wc -l < a.txt
来源：http://dali.cashguo.top/Article/details/gtolvhfmau.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gtijbnkmul.html

find . -name "*.log" -type f
来源：http://dali.cashguo.top/Article/details/gtfnsssgbn.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtzfoougkv.html

find . -mtime -7 -type f
来源：http://dali.zhixingplan.top/Article/details/gtpeiqvosc.html

[R45] 批量删除
来源：http://dali.yanxiufei.cn/Article/details/gtqnqhsnub.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gtrkweabwx.html

[R46] 递归替换文件内容
来源：http://dali.vqdsnc.cn/Article/details/gtlrscbudw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigufen.top/Article/details/gtqhrortzy.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtwoxexghv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtwfwbymop.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gtuqzcqdgo.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtlqfalnfo.html

[R49] awk 带条件
来源：http://dali.hnxiangtu.top/Article/details/gtltojgkkz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gtsxwqxkah.html

[R50] awk 求和
来源：http://dali.mhx1999.top/Article/details/gtnwtdzily.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtsjcqidyn.html

[R51] 排序去重取前几
来源：http://dali.iojbl.cn/Article/details/gtkvxedzgs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.0kj1m.cn/Article/details/gtjuwxkkwn.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gtwwwapazj.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtqqjwstvb.html

[R53] 查看文件头与实时尾
来源：http://dali.gogol.net.cn/Article/details/gtqqitdduh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gtvxqsivty.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gtvjmyngpa.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtboicpseu.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gthcfodlny.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guannengcc.top/Article/details/gtbnldfiqe.html

[R56] 远程拷贝
来源：http://dali.cqqwz.cn/Article/details/gteckkbqbd.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gtycgjmuuv.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gtevfvpauf.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gtctwhhvke.html

[R58] 下载文件
来源：http://dali.9152youxi.cn/Article/details/gtgshukejw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pengpengdd.cyou/Article/details/gtlhrfkovm.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtlzqrxldg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aibaodan.cn/Article/details/gtlbioxwea.html

[R60] 只看 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtenmxnmeo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gtfpdqcoot.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnhozkyh.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gtremzffof.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gtamwmhete.html

du -ah . | sort -rh | head -10
来源：http://dali.sysykeji.top/Article/details/gtkyepgzxh.html

[R63] 内存与进程
来源：http://dali.nwbrower.top/Article/details/gtrjqkpqcm.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gtfogegagw.html

[R64] 结束进程
来源：http://dali.hywenlv.cn/Article/details/gtrjgmuors.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gtmgkzemry.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gtlumjdlbd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gtygacfqls.html

[R66] 定时任务
来源：http://dali.gaohongyu789.top/Article/details/gtrbkcldsi.html

crontab -e;  crontab -l
来源：http://dali.zycfv.cn/Article/details/gtrtepzbvh.html

[R67] 生成随机十六进制串
来源：http://dali.jiagoushi.top/Article/details/gtmqgvvqne.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gtureytrzd.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gtegywihyx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gtyiegidrs.html

[R69] 生成随机密码
来源：http://dali.sweek.top/Article/details/gtwupbawrc.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gtuznlimbg.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gtbwjbwufm.html

date +%s;  date -d @1700000000
来源：http://dali.nwbrower.top/Article/details/gtnzqutzyg.html

[R71] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtmdwoyrmr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gtqlcdrpmy.html

[R72] 等待端口就绪
来源：http://dali.bjfxy.top/Article/details/gtnjgfztxx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtytbotkvg.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvozjccrp.html

split -l 1000 big.log part_
来源：http://dali.daxiang520.top/Article/details/gtcylzflnc.html

[R74] 批量重命名
来源：http://dali.hammf.cn/Article/details/gtbeivbicb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gtspnpfozf.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gtuawvcgli.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gtrpchvzbc.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gtnvxavyku.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gteqepspxo.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gtraibikrs.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gtiwuvfedd.html

[R78] 交互式菜单
来源：http://dali.jlsjyb.cn/Article/details/gtxwsubvtw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gtbyefjhsu.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gtpuzjztnp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj202588.top/Article/details/gtmhsuoaxz.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gtdwdrrimj.html

time ./run.sh
来源：http://dali.wangshuangyany.cn/Article/details/gtapxubhwn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtniipamdk.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gtmugfrdlu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdtiuaeui.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtxzgdcjqn.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gtdxnoocsn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gtgtkqbtdx.html

[S02] C：变量与格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtbavzezky.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gtognvyfff.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gtvfgyitpb.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gtcpklppev.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqfvjgla.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.0kj1m.cn/Article/details/gtfqhvszcb.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gtddqcgwfs.html

strlen(s)
来源：http://dali.0kj1m.cn/Article/details/gtqcotbook.html

[S06] C：字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtjowaweih.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtolgbxxaj.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtcvpounht.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gtihjgudfv.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbckjhhav.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gtisletxqp.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gtvmpukssk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtuewrpedj.html

[S10] C：指针与解引用
来源：http://dali.fengsongda.top/Article/details/gtsspfpgnc.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gtydpxofwj.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtignmbydv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yonumen.top/Article/details/gtzmpycgoo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gtyuzmsjld.html

fclose(f);
来源：http://dali.pycfn.com/Article/details/gtzzdjzumj.html

[S12] C：写文件
来源：http://dali.mhx1999.top/Article/details/gthowlowkz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtvqfzzyrb.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gtwpbuxsrm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhengqikj.top/Article/details/gtqyfasxcy.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gtmmtfjkvh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghmbfqgf.html

[S15] C：类型转换
来源：http://dali.yangfankeji.com/Article/details/gtlieaqnxc.html

(double) a / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnglqhak.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gtvjxnpiyq.html

x |= (1 << 3);
来源：http://dali.zycfv.cn/Article/details/gtjtuheuvg.html

[S17] C：安全拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtqioqjxna.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yanxiufei.cn/Article/details/gtrlrqivut.html

[S18] C：命令行参数
来源：http://dali.hysaishi.cn/Article/details/gtvjcaflgl.html

int main(int argc, char **argv)
来源：http://dali.xuetiantiany.cn/Article/details/gtvcnyujyu.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gtgjvtbqgn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtwwaipjrb.html

[S20] C：二分查找
来源：http://dali.jianghu66.top/Article/details/gtjjmblmyb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtpmuuruer.html

[S21] C：字符类别判断
来源：http://dali.haohaochexian.top/Article/details/gtxvnafvwj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ivvv.top/Article/details/gtzozkmlhr.html

[S22] C：字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gtcrxslylb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhoulong.xyz/Article/details/gthxuhncrd.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gtkzretvvx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cheryme.top/Article/details/gtvqkxkpoy.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gtitlgqenn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gtaaoiqrpb.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gtbzbpaqfj.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gtjvdyggbq.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gthptyhdrl.html


<!-- 参考信息 -->