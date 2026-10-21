代发 wailian999

[Q61] 移动平均
来源：http://dali.daria6918.cn/Article/details/gtnrwyjqru.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtkkfcpsfv.html

[Q62] 分组占比
来源：http://dali.dashuyun.cn/Article/details/gtnmalzqhy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaarfvios.html

[Q63] 开启事务
来源：http://dali.zhiwuduotai.top/Article/details/gtmjdklqas.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.havefunace.top/Article/details/gtittxgjbc.html

[Q64] 提交事务
来源：http://dali.pycfn.com/Article/details/gtntkzjipw.html

COMMIT;
来源：http://dali.hysaishi.cn/Article/details/gtwaguhmzp.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gtgsrzzlqv.html

ROLLBACK;
来源：http://dali.yj20258888.top/Article/details/gtnrsppwws.html

[Q66] 行锁查询
来源：http://dali.daxiang520.top/Article/details/gtgqrjywtx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gtgumpnbmz.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gtyewolsmu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guannengcc.top/Article/details/gtipkmfieb.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gtdvzgwufe.html

SAVEPOINT sp1;
来源：http://dali.tianlin.xyz/Article/details/gtqgdmybms.html

ROLLBACK TO sp1;
来源：http://dali.hysaishi.cn/Article/details/gtedtwdyry.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gtjlyczqfm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhongyouzk.top/Article/details/gtjqdnpqal.html

[Q70] 更新统计信息
来源：http://dali.yj20258.top/Article/details/gtmlduvdjv.html

ANALYZE TABLE users;
来源：http://dali.fengsongda.top/Article/details/gtbodgummh.html

[Q71] 查看建表语句
来源：http://dali.yuanzhike.top/Article/details/gtnynhxfyv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yongpay.top/Article/details/gthfetjlvt.html

[Q72] 查看索引
来源：http://dali.jinqigufen.top/Article/details/gtgribkpje.html

SHOW INDEX FROM users;
来源：http://dali.aizwys.cn/Article/details/gtsjzzzxyk.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbjqzevj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dashuyun.cn/Article/details/gtchbmibwg.html

[Q74] 强制使用索引
来源：http://dali.zhiwuduotai.top/Article/details/gtkjwgsgit.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hongshengwenyu.top/Article/details/gtnhaihoge.html

[Q75] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtnxkmfmvp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwdsxcxp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gtawxpnbhw.html

[Q76] 按天统计
来源：http://dali.kuanghao11.cn/Article/details/gtdfixeagp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.redwolf501.top/Article/details/gtvnfqynkp.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gtxvygdgnz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cashguo.top/Article/details/gtijduozdw.html

[Q78] 当前时间
来源：http://dali.sysykeji.top/Article/details/gtxvzqondo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fengsongda.top/Article/details/gtjgwbshae.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gtpdudkctv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zycfv.cn/Article/details/gtmeuelxyi.html

[Q80] 字符串截取
来源：http://dali.kuanghao11.cn/Article/details/gtnretjlnw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtzquqveql.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwcczazq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gtkillhpzn.html

[Q82] 字符长度与字节长度
来源：http://dali.snrcjt.cn/Article/details/gtgntvaekh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtofanhijg.html

[Q83] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtviwruapu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtlqyohqwu.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gtazvynuou.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtcryrlvqq.html

[Q85] 数值取整
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtuehliu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shangyingyoupin.top/Article/details/gttbbzcoip.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gtixjeqfzw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hysaishi.cn/Article/details/gtgdmrtuvh.html

[Q87] JSON 字段做条件
来源：http://dali.zhiwuduotai.top/Article/details/gtuwemnygu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pengpengdd.cyou/Article/details/gtcxiytjoa.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gtsjnqiibb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258.top/Article/details/gtyqexkjjj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gtpzfnhoak.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gtmxgzqyva.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gtddxknpqi.html

[Q90] 生成序号列
来源：http://dali.snrcjt.cn/Article/details/gtxtytlfmu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gtaystguwj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgvwzikf.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gtrpbfwxnc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtnkzcjfcs.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gttyokprys.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gtsmbdcblj.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtqkitbidm.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gtyyvkeifr.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gtsongrweb.html

[R03] 只读变量
来源：http://dali.guannengcc.top/Article/details/gtwwptrsbb.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gtfxmypuar.html

[R04] 位置参数
来源：http://dali.ivvv.top/Article/details/gtcudvrxpx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkapayhxg.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gtituiqhya.html

name="${1:-default}"
来源：http://dali.andypj.xyz/Article/details/gtcoyeznma.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gtgnwskzdd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtsdvycnla.html

[R07] if 判断文件
来源：http://dali.yj20258888.top/Article/details/gtsxdbhlso.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtspcaydix.html

[R08] 数值比较
来源：http://dali.jyoumei.cn/Article/details/gtjqzdilav.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxinkj.top/Article/details/gtpicsnhbc.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gthucukkei.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtyodkivjl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gtlhlmtjop.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gtpdcfvgkq.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gtmcwbzwsj.html

case "$1" in
来源：http://dali.xuetiantiany.cn/Article/details/gtqqjocsmj.html

start) echo "启动" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gttwotbdlo.html

stop)  echo "停止" ;;
来源：http://dali.snrcjt.cn/Article/details/gteaugrlvv.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gtkpxdidzh.html

esac
来源：http://dali.bjfxy.top/Article/details/gtierzarjw.html

[R12] for 遍历文件
来源：http://dali.wangdashe.top/Article/details/gtaksfshbn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gtmejnyraz.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gthygwukkr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtodxftqbt.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gtpdymtyqc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtcadctmwq.html

[R15] while 逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtcxeqruhn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gtxoaoyezt.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gtggxftefv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtmniecddt.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gtykvzfvxn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsflmmmqf.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gtdqckwiyz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliwedlqm.html

[R19] 数组长度
来源：http://dali.sweek.top/Article/details/gthswkutfg.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gtcmgrcgit.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhdreivp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gtwdunhhmy.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gttbexrphp.html

echo "${#s}"
来源：http://dali.shangyingyoupin.top/Article/details/gtmhxfiubj.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtvrmfjxhm.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gtazrqhtcz.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtqdfpzjck.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gtraylbqiq.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtbveeqwfh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gtkyehboui.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gtozdtafuv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojbgzgfp.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gtbqyggama.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gtxrurwewt.html

[R27] 算术展开
来源：http://dali.nanxuanxn.top/Article/details/gtwxpcrpmb.html

echo $((1 + 2 * 3))
来源：http://dali.ehwqpu.com/Article/details/gtucnmopei.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gtcvutwbtx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gtcvvtrpkx.html

[R29] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtwhvfvrdk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gtjxwebijf.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gtktgaptsv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gtjcjneths.html

[R31] 局部变量
来源：http://dali.jianghu66.top/Article/details/gtahutgeri.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gttawzigrk.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtykidabhp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtocaohkio.html

[R33] 捕获错误并提示行号
来源：http://dali.snrcjt.cn/Article/details/gtqynidiia.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gtufpdebex.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gtvhypfmtm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtcjoxqmsw.html

[R35] 后台执行并等待
来源：http://dali.chenzaomai.com/Article/details/gtpdrtuero.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.316326.xyz/Article/details/gtpijxrtwn.html

[R36] 并发执行多个任务
来源：http://dali.fzhhl.top/Article/details/gtrbqqhkub.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tian-w.cn/Article/details/gtrjyancyd.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gtqinebdcc.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gtuzaqnbps.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gtjytdrhmx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gtlsrafblo.html

[R39] 重定向标准输出与错误
来源：http://dali.chenzaomai.com/Article/details/gtxwnwtduk.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtmrftashw.html

[R40] 追加写日志
来源：http://dali.hywenlv.cn/Article/details/gtusimkqlj.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gtwtgrpzsb.html

[R41] 丢弃输出
来源：http://dali.andypj.xyz/Article/details/gtizrwawwz.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gtnuqdmqut.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gtjswoqmvb.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtopyoracl.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gtxdfvznpy.html

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gtedktkbuh.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gtyweebire.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gtamczalqo.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gtuhxijxql.html

find . -name "*.tmp" -delete
来源：http://dali.gotoacloud.top/Article/details/gtgmcmxsyk.html

[R46] 递归替换文件内容
来源：http://dali.zycfv.cn/Article/details/gtktqnnevy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gtyygolmoq.html

[R47] sed 单行替换
来源：http://dali.hnxiangtu.top/Article/details/gtvhsehuel.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtlehqhitt.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gtqmcgchit.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtpyardqol.html

[R49] awk 带条件
来源：http://dali.hammf.cn/Article/details/gttlwfglsv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gtlewhebjg.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gtpveajnnb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtjnzovyhf.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwnyzdzj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ydzc1.top/Article/details/gtkeohjzog.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gtsajiuljk.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gtspmnwekf.html

[R53] 查看文件头与实时尾
来源：http://dali.meibo888.top/Article/details/gtqhopakvd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gtzxxrtqxf.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gtdohkjhiy.html

diff a.txt b.txt
来源：http://dali.tian-w.cn/Article/details/gtskbwmvwa.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gtizbqfxhr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258888.top/Article/details/gtatiyghoy.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtmrijcpav.html

scp file user@host:/path/
来源：http://dali.sufxvd.cn/Article/details/gtuxbrrcpk.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gtkqmzfbfc.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gtnzwglijy.html

[R58] 下载文件
来源：http://dali.0kj1m.cn/Article/details/gtyinnivet.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gtptxudbgy.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtlxcewihu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258.top/Article/details/gtpkwkwxss.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtuveyivlj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gtwhgokigv.html

[R61] 磁盘占用
来源：http://dali.sysykeji.top/Article/details/gtcuokkram.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtwofjgszr.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gtteyucrtt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhongyouzk.top/Article/details/gtchmygmsn.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gthlpusixl.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gtnmtzgsot.html

[R64] 结束进程
来源：http://dali.pycfn.com/Article/details/gtxngkvhil.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gtbgjtekwy.html

[R65] 查看端口占用
来源：http://dali.redwolf501.top/Article/details/gtpajmyrxb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gtgfpecldk.html

[R66] 定时任务
来源：http://dali.hywenlv.cn/Article/details/gtsqagwkkp.html

crontab -e;  crontab -l
来源：http://dali.chenzaomai.com/Article/details/gtouxpqymp.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gtplnsclsa.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gtijenvbbh.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gtuiwokbrj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangdashe.top/Article/details/gttdqrnxjp.html

[R69] 生成随机密码
来源：http://dali.sxryk.cn/Article/details/gtinooevun.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gtwiygimlt.html

[R70] 时间戳与互转
来源：http://dali.pycfn.com/Article/details/gtreiwnfwg.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gtbsrznwwe.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtncqplbwi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cqqwz.cn/Article/details/gterfsmxyt.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gtuuycmazv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtmygbrsbm.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gtjuaqkewv.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gtcqgmxfuo.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gtgitczhbu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gtpniucsru.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtizhewcfe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.haohaochexian.top/Article/details/gtfrbwgtyy.html

[R76] 使用临时文件
来源：http://dali.daxiang520.top/Article/details/gtifbepntb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtwcfluzjm.html

[R77] 读取用户输入
来源：http://dali.zycfv.cn/Article/details/gtnmeuuqff.html

read -rp "请输入: " ans
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoznrzzjt.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gteawefhnu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gaohongyu789.top/Article/details/gtupbkvmxk.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gtkowbhqcr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhoulong.xyz/Article/details/gtznusmzqc.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gtqbeagsvl.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gtkjeusatz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtslmgpgwk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gtfjlslffi.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtktmkzgrc.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoswpxgsk.html

#include <stdio.h>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsscgcbp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gaohongyu789.top/Article/details/gtgfhebger.html

[S02] C：变量与格式化输出
来源：http://dali.316326.xyz/Article/details/gtyvvjmsuo.html

int a = 10; printf("%d\n", a);
来源：http://dali.shuidangran.top/Article/details/gtqcgtjnjq.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gtxtjltfrt.html

int x; scanf("%d", &x);
来源：http://dali.gaohongyu789.top/Article/details/gtdzidkxeq.html

[S04] C：字符串复制
来源：http://dali.gaohongyu789.top/Article/details/gtccigorjq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtbyfdkrrq.html

[S05] C：字符串长度
来源：http://dali.yj202588.top/Article/details/gtwqpfrxsf.html

strlen(s)
来源：http://dali.shuidangran.top/Article/details/gttcsmbygn.html

[S06] C：字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtjccslcbz.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gtdkzqqesd.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gtqlaqikqg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cucudq.cn/Article/details/gtpxxbhxlv.html

[S08] C：动态内存分配与释放
来源：http://dali.quarkkingdee.top/Article/details/gtpxzdnove.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.smart0.xyz/Article/details/gtrddzqawd.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gtjrhzesep.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gtwmrnrtox.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtyrsyudeb.html

int *p = &a;  *p = 5;
来源：http://dali.sxryk.cn/Article/details/gtwcklefnt.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtgljwetvl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gtajqkggom.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfarxvyfp.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtxwxzjfiw.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gtcgfoxojj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtyvsvcgme.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjgixxjl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gthljmnvgi.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gtqmokujgq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gtshudtxzt.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gtujkpyymr.html

(double) a / b
来源：http://dali.hywenlv.cn/Article/details/gtudkxxads.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gtrolregbj.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxveaawg.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtbjrunqsw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqjberrp.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gtslsthqmy.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gtvzudblzb.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gtoliyvejn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtrthctsvg.html

[S20] C：二分查找
来源：http://dali.jlsjyb.cn/Article/details/gtkyacrkzx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtorxrkwpa.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gtqabnxagm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.birdmap.top/Article/details/gthqxmrwsx.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gtysvrsauj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gtgzprxlru.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtpcdyllmt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.vqdsnc.cn/Article/details/gtbpxtphyc.html

[S24] C：获取本地时间
来源：http://dali.cdnleiting.top/Article/details/gtxfsubnpa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gtpofgbxmy.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtmmyywczk.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gtqqtqsmcc.html

[S26] C：内存清零
来源：http://dali.pycfn.com/Article/details/gtfsoawhkc.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gtcbecvybw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gtxxndbasx.html

const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtfpqtaxjr.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtimbkagla.html

static int counter = 0;
来源：http://dali.andypj.xyz/Article/details/gticpyuwwc.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gtcvpvopnm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gtchdeyise.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gtjcaxuzft.html

#ifndef X_H
来源：http://dali.tanke756.top/Article/details/gtkhtbzywl.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gtatjtgvqy.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gtgvhgavxr.html

[S31] C++：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtpdekjgus.html


<!-- 参考信息 -->