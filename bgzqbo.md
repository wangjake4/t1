代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtgcdopdqh.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gtlkaxlfxg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hongshengwenyu.top/Article/details/gtlrqmkpfr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtsmedzerj.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gtvkbtbxht.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtosruhies.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gtdkvbfbxx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtmslavmoq.html

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gtptfxmomm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gtugzdcdwk.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtxgzmbx.html

COMMIT;
来源：http://dali.daxiang520.top/Article/details/gtxflbyhhs.html

[Q65] 回滚事务
来源：http://dali.chenlongwang.top/Article/details/gtymrdlltl.html

ROLLBACK;
来源：http://dali.shangyingyoupin.top/Article/details/gtonajcbfx.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gtyxscghst.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gtzouxnvqk.html

[Q67] 设置隔离级别
来源：http://dali.pengpengdd.cyou/Article/details/gtjafsboza.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gteruuzywd.html

[Q68] 保存点
来源：http://dali.0kj1m.cn/Article/details/gtqdjrcfuy.html

SAVEPOINT sp1;
来源：http://dali.ybcxt.top/Article/details/gtnsztjuzo.html

ROLLBACK TO sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkiywigvj.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gtuhpxfqck.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zdqjudy.top/Article/details/gtesyjfkuv.html

[Q70] 更新统计信息
来源：http://dali.hywenlv.cn/Article/details/gtfospimnd.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gtywxyqfxk.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gtxdaqbxdc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gtbcwloett.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gtmugukvvk.html

SHOW INDEX FROM users;
来源：http://dali.cucudq.cn/Article/details/gtnouhagjm.html

[Q73] 查看表状态
来源：http://dali.gogol.net.cn/Article/details/gtsspqqdzp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.iojbl.cn/Article/details/gtfbxhbqju.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gtpxzfamls.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zdqjudy.top/Article/details/gtagiecsxl.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtapwmafaa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtaeathovu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gtupgvoknb.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gtwtlarsqk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.quarkkingdee.top/Article/details/gteynpgkco.html

[Q77] 时间加减
来源：http://dali.zhongyouzk.top/Article/details/gtwouawdvs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gtpqhmhucf.html

[Q78] 当前时间
来源：http://dali.xziqi.cn/Article/details/gtfhytpjzd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gtubjpmzhb.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtbqfyfxcm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gzhubu.top/Article/details/gtfdktbjos.html

[Q80] 字符串截取
来源：http://dali.shuidangran.top/Article/details/gtgzydiuzk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtbzylzegu.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtlrdznddu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhyuwetd.html

[Q82] 字符长度与字节长度
来源：http://dali.ivvv.top/Article/details/gtnujlctvn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtuqozwfnq.html

[Q83] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gtgccnjxxl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gthjbcohxo.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gtqiwrpguz.html

SELECT TRIM(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtsrimfhwx.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gtngsmicik.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gtbyinzrzx.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gtzcxaosiv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xylfe.cn/Article/details/gtefoeibqj.html

[Q87] JSON 字段做条件
来源：http://dali.zhiwuduotai.top/Article/details/gtctuajqzh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gtjueskjys.html

[Q88] 行转列（条件聚合）
来源：http://dali.birdmap.top/Article/details/gtitjjwrjr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yongpay.top/Article/details/gtjpbjiwqp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtnwjzdvnz.html

[Q89] 判断表是否存在
来源：http://dali.nanxinkj.top/Article/details/gtpsxiidfx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtlyivxzaa.html

[Q90] 生成序号列
来源：http://dali.kuanghao11.cn/Article/details/gtrrsvogbu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gtgzbafqev.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtesiyfgun.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gtbjbnnlmi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbsibrvkh.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gtsgrccith.html

#!/usr/bin/env bash
来源：http://dali.zhiwuduotai.top/Article/details/gtqvyzlwrr.html

set -euo pipefail
来源：http://dali.chenjidiqi.icu/Article/details/gtpxxgksqm.html

[R02] 变量赋值与使用
来源：http://dali.dianchejie.cn/Article/details/gtnggohkub.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gtecqcqnel.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gtinuuouph.html

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gtrsfcxqwk.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gtkvkfdpvj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gtmjftdfrn.html

[R05] 参数默认值
来源：http://dali.zycfv.cn/Article/details/gtgifnprax.html

name="${1:-default}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvujmvqri.html

[R06] 判断命令是否存在
来源：http://dali.smart0.xyz/Article/details/gtroiykway.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtdwtnrepi.html

[R07] if 判断文件
来源：http://dali.9152youxi.cn/Article/details/gtnrmcrrpm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtzbvrcmjm.html

[R08] 数值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjggyvuds.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.havefunace.top/Article/details/gttacaeekp.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtrhsbjrah.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gthaviakpy.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtrvzqdogq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.havefunace.top/Article/details/gtmsfnoyas.html

[R11] case 多分支
来源：http://dali.jiagoushi.top/Article/details/gtqinznunr.html

case "$1" in
来源：http://dali.xuanzx.com/Article/details/gtsudoqcxx.html

start) echo "启动" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtogqrojyp.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gttniwyerg.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclkaravd.html

esac
来源：http://dali.yangfankeji.com/Article/details/gtvivaqygu.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gtlqvmaxph.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gtoswzcokd.html

[R13] for 计数循环
来源：http://dali.hammf.cn/Article/details/gtvdtyhvhp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtgwudtcuj.html

[R14] C 风格 for
来源：http://dali.ydzc1.top/Article/details/gtigfbkbko.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtqayiangs.html

[R15] while 逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtqnhkfaob.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daria6918.cn/Article/details/gtxlpwfwgf.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gtokoerobv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtiuoaykuw.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtxoctlmme.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gtkbhytkku.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gtejuflddd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gtsfoqfuqq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtkjxdtnft.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gtborjcqbn.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gtgvefmeim.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gthsmsnlin.html

[R21] 字符串长度
来源：http://dali.jiagoushi.top/Article/details/gtnvsvzqcn.html

echo "${#s}"
来源：http://dali.jianghu66.top/Article/details/gtfugdbiup.html

[R22] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gtimehfnxn.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gtggqbusom.html

[R23] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gthonrxtff.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhoulong.xyz/Article/details/gtgrstfhbf.html

[R24] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtqfpwmwwb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aizwys.cn/Article/details/gttniqlrxl.html

[R25] 去后缀 / 去前缀
来源：http://dali.fengsongda.top/Article/details/gtbauqiqqi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gttcdbeoxu.html

[R26] 命令替换
来源：http://dali.gaohongyu789.top/Article/details/gtqcnuapsg.html

now=$(date +%F); echo "$now"
来源：http://dali.bjfxy.top/Article/details/gtkytyovsz.html

[R27] 算术展开
来源：http://dali.0kj1m.cn/Article/details/gtckucrlrb.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gtgeuuhmpn.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gtgtegkxmb.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gtcwlcvwra.html

[R29] 定义函数
来源：http://dali.sweek.top/Article/details/gtvieesqdw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gthicdquoj.html

[R30] 函数返回状态码
来源：http://dali.pycfn.com/Article/details/gtzigzcngu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gtlsqtasvo.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gtkeezvyki.html

f() { local x=1; echo "$x"; }
来源：http://dali.yonumen.top/Article/details/gtobpgzcdk.html

[R32] 参数个数校验
来源：http://dali.shangyingyoupin.top/Article/details/gtigwzzfcw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gtwebwhdde.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gtyrhjcnkc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.meibo888.top/Article/details/gtiatkgcvd.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gtlcnwxhkk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtupowzhkm.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gtijpsrvjg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gtsucqyoir.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gtinmtzczh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gthpvgured.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gtcdbtipwk.html

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gtwmrsgcgf.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gtlwwbsmxe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtkrlauqaw.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gtxehgwyox.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtsfrjvavi.html

[R40] 追加写日志
来源：http://dali.yj20258888.top/Article/details/gtlbrxbsru.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gtzznqdlwa.html

[R41] 丢弃输出
来源：http://dali.hongshengwenyu.top/Article/details/gtwqdgvbug.html

cmd >/dev/null 2>&1
来源：http://dali.redwolf501.top/Article/details/gtjorzfuhi.html

[R42] 输入重定向
来源：http://dali.yongpay.top/Article/details/gtipwkvwod.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gttiotvyib.html

[R43] 按名字查找文件
来源：http://dali.daria6918.cn/Article/details/gtsrkagpyl.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gtroojymlz.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtcfcrpcxl.html

find . -mtime -7 -type f
来源：http://dali.zhongyouzk.top/Article/details/gttuolaofg.html

[R45] 批量删除
来源：http://dali.redwolf501.top/Article/details/gtutdrknru.html

find . -name "*.tmp" -delete
来源：http://dali.wangshuangyany.cn/Article/details/gtleyifbuu.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gtdiebxpcn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gtmblmccyn.html

[R47] sed 单行替换
来源：http://dali.yangfankeji.com/Article/details/gthkidrwhg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtpmikljyw.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gtyepqlqwe.html

awk '{print $1, $3}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtmkjyqbvv.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gtflpgqals.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gtavrhbmpl.html

[R50] awk 求和
来源：http://dali.pycfn.com/Article/details/gtsesqmwxq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guannengcc.top/Article/details/gtoclcvnyi.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gtxpadxrqx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jiagoushi.top/Article/details/gtvihpeirl.html

[R52] 统计行数
来源：http://dali.sweek.top/Article/details/gtvrznefxi.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gtmpdshabl.html

[R53] 查看文件头与实时尾
来源：http://dali.jlsjyb.cn/Article/details/gtgeshkvua.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gtdrngbhjp.html

[R54] 比较两个文件
来源：http://dali.daxiang520.top/Article/details/gtsoljppzl.html

diff a.txt b.txt
来源：http://dali.xuanzx.com/Article/details/gttpqjznlj.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gtnqrrpoos.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gticyhzpnx.html

[R56] 远程拷贝
来源：http://dali.yongpay.top/Article/details/gtnacdrbid.html

scp file user@host:/path/
来源：http://dali.ivvv.top/Article/details/gttwwmzgmf.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gtivprrwve.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gtohwdospb.html

[R58] 下载文件
来源：http://dali.yuanzhike.top/Article/details/gtannuwlyw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gtmnehxfzq.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gtqoynfmug.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.kuanghao11.cn/Article/details/gtryojelfy.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpgaodip.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gtfifbwapg.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gtirxtyraa.html

df -h;  du -sh *
来源：http://dali.jinqigufen.top/Article/details/gthbsfzmfb.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gteriqkvpp.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gtrtsogrox.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gtshhnrcmc.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gtyykloryv.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gtdkmojhaf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gtstnihsoh.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gtvjzbhhby.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gtejzgpwzw.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gtqbjvgcqb.html

crontab -e;  crontab -l
来源：http://dali.yuanzhike.top/Article/details/gtysmvtdtb.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gtbazmkzqb.html

openssl rand -hex 16
来源：http://dali.hnxiangtu.top/Article/details/gtdgirvldd.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gtahcrjfgf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueekzfdt.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtvrtbpibr.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndptdtza.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gtxdpqyyvy.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gtiflglwys.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtcvxwwhyq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtcsnsjubx.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gttxoqwsas.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtmwtmbmpt.html

[R73] 分割大日志
来源：http://dali.chenzaomai.com/Article/details/gtnwyineex.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gtmmpbjcvz.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gtvwfeabpo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknriqmdo.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtaxejpmtx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gtcdkwmubg.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gtthusnudr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtgmfhbiis.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gtgrjpbhwh.html

read -rp "请输入: " ans
来源：http://dali.yueranfly.top/Article/details/gtlwlvljxl.html

[R78] 交互式菜单
来源：http://dali.ivvv.top/Article/details/gtmqpqbrze.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gtyfbiszcl.html

[R79] 解析命令行选项
来源：http://dali.iojbl.cn/Article/details/gtdguedusm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gtgqitlwvu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhiwuduotai.top/Article/details/gtfonxvjqi.html

time ./run.sh
来源：http://dali.sxryk.cn/Article/details/gtxezmgmtw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtscnwlsza.html

S. C / C++ 专题
来源：http://dali.kuanghao11.cn/Article/details/gtucwqkgia.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtuilklkjt.html

[S01] C：Hello World
来源：http://dali.yvedp.cn/Article/details/gtiqjnzlnn.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gtrjeyokny.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gtusdmszdp.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gtrmynhrxg.html

int a = 10; printf("%d\n", a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphjmbzqb.html

[S03] C：读入整数
来源：http://dali.daxiang520.top/Article/details/gtckbdcbwp.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gtvlfesija.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtrqvivjhc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtpthldbvp.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gtpytgaqrz.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gtnfexuxdq.html

[S06] C：字符串比较
来源：http://dali.meibo888.top/Article/details/gteyhawxws.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gtalptlsju.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gtqnabsxhh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinghuilouyu.cn/Article/details/gttukgkest.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gtqcnaqcgd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258.top/Article/details/gtxqzdysog.html

[S09] C：结构体定义与初始化
来源：http://dali.xuetiantiany.cn/Article/details/gtkfxfughf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gtycoqwagb.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gtvgywvycx.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gtfrzywrfg.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtqsyurkqg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gtwacverlu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gtdndqssyc.html

fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtnjqgfaze.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtsxpkpzmb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtcybgcxvf.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gtwenjgjxe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gtxhdiohxi.html

[S14] C：枚举
来源：http://dali.cqqwz.cn/Article/details/gtpjyezoly.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.redwolf501.top/Article/details/gtzsbflkey.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtjpixgffu.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gtohafwhzz.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gtuyuziqnq.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtyxhwgtlj.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtmklgngbj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gtuwntrxus.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtszxddigp.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtakyagsat.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtltbuvyzq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtyxnghufq.html

[S20] C：二分查找
来源：http://dali.yuanzhike.top/Article/details/gtejwoosja.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtdvcgesks.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gtcwexlkpp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gtbcddrnup.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtkxjvnoxt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hfpthk.cn/Article/details/gtzmwqvlve.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gtswrvbiea.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sufxvd.cn/Article/details/gtmnvemdgw.html

[S24] C：获取本地时间
来源：http://dali.jiagoushi.top/Article/details/gtyzvesiml.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gtishxfxti.html

[S25] C：内存拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtaiqkfwdy.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gthabqbieg.html

[S26] C：内存清零
来源：http://dali.shzxlz.cn/Article/details/gttarbpuyj.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikmyjumu.html

[S27] C：定义常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtellpranp.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtrsohhdhn.html

[S28] C：静态变量
来源：http://dali.jiagoushi.top/Article/details/gtndlqbhvy.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtgsjjoufd.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gttkocjpdt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gtxnqqezbk.html

[S30] C：头文件保护
来源：http://dali.kuanghao11.cn/Article/details/gtnfrcdeyq.html


<!-- 参考信息 -->