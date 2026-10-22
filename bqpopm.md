代发 wailian999

[Q61] 移动平均
来源：http://dali.havefunace.top/Article/details/gt2pfupuwrt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gt2dwnjebfq.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gt2zmcqlmpk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gt2kmgqlqnx.html

[Q63] 开启事务
来源：http://dali.ybcxt.top/Article/details/gt2kuafzpnh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.316326.xyz/Article/details/gt2nijuptbb.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gt2ppltcfrg.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gt2lseswoxv.html

[Q65] 回滚事务
来源：http://dali.daria6918.cn/Article/details/gt2nwhbdbmj.html

ROLLBACK;
来源：http://dali.ybcxt.top/Article/details/gt2ttxzpvin.html

[Q66] 行锁查询
来源：http://dali.yueranfly.top/Article/details/gt2zkmtphhb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigfzy.top/Article/details/gt2mvawbfet.html

[Q67] 设置隔离级别
来源：http://dali.hnqzz.top/Article/details/gt2shonbpsl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gt2xjgojwip.html

[Q68] 保存点
来源：http://dali.yj20258888.top/Article/details/gt2umjscwpd.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gt2ayqdyrgc.html

ROLLBACK TO sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjekcdlb.html

[Q69] 查看执行计划
来源：http://dali.mhx1999.top/Article/details/gt2ujxpuvwo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gt2qwpdhgum.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gt2kkhxhuqz.html

ANALYZE TABLE users;
来源：http://dali.jqgfzy.top/Article/details/gt2icqriukc.html

[Q71] 查看建表语句
来源：http://dali.yuanzhike.top/Article/details/gt2tsajqcch.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gt2nojrxmik.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2ddfajfpo.html

SHOW INDEX FROM users;
来源：http://dali.cashguo.top/Article/details/gt2briegqjf.html

[Q73] 查看表状态
来源：http://dali.tanke756.top/Article/details/gt2ujhyjzao.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gt2gbaisnjd.html

[Q74] 强制使用索引
来源：http://dali.hnxiangtu.top/Article/details/gt2yuspgfxj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnqzz.top/Article/details/gt2xnldwxnh.html

[Q75] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gt2lpvhrdkm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2orsuloqz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tian-w.cn/Article/details/gt2ajlusbsx.html

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gt2rnboobcx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gt2aqekholj.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gt2zwepvqtw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gt2bymwfzpr.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gt2xhdsscig.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gt2fsrasvyz.html

[Q79] 字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gt2kitxrlac.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gt2qechezwn.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gt2bdgtibcc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2fnkflqbr.html

[Q81] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gt2qtaihngo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhygsijw.html

[Q82] 字符长度与字节长度
来源：http://dali.meibo888.top/Article/details/gt2onqbyclg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2iljlrwjq.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gt2jjlbxsiz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2omzecumd.html

[Q84] 去除首尾空格
来源：http://dali.redwolf501.top/Article/details/gt2uopbhtzm.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2gxqvlhtf.html

[Q85] 数值取整
来源：http://dali.gzhubu.top/Article/details/gt2mvxeqiui.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xylfe.cn/Article/details/gt2dxixgttw.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigfzy.top/Article/details/gt2cmfoichd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gt2cruquzjt.html

[Q87] JSON 字段做条件
来源：http://dali.vqdsnc.cn/Article/details/gt2ufdafcrl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gotoacloud.top/Article/details/gt2jfgcyibo.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuanzx.com/Article/details/gt2drllllru.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gt2joausccn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2vapirgsn.html

[Q89] 判断表是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2injxodmc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqjgdgxk.html

[Q90] 生成序号列
来源：http://dali.jyoumei.cn/Article/details/gt2rkweueya.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.bjfxy.top/Article/details/gt2xeeybkmo.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2endboaor.html

R. Bash 专题
来源：http://dali.ppjwa.cn/Article/details/gt2annmjfyh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2rnzrenpz.html

[R01] shebang 与严格模式
来源：http://dali.nanxuanxn.top/Article/details/gt2qafocrvd.html

#!/usr/bin/env bash
来源：http://dali.daxiang520.top/Article/details/gt2prdthwru.html

set -euo pipefail
来源：http://dali.smart0.xyz/Article/details/gt2skmxrbng.html

[R02] 变量赋值与使用
来源：http://dali.hnqzz.top/Article/details/gt2zsscdljc.html

name="Tom"; echo "$name"
来源：http://dali.jlsjyb.cn/Article/details/gt2nbesydvu.html

[R03] 只读变量
来源：http://dali.daria6918.cn/Article/details/gt2kseldylc.html

readonly PI=3.14
来源：http://dali.yuxming.cn/Article/details/gt2dayrubbs.html

[R04] 位置参数
来源：http://dali.yonumen.top/Article/details/gt2qazntmfi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gt2fudayrql.html

[R05] 参数默认值
来源：http://dali.snrcjt.cn/Article/details/gt2levazvyt.html

name="${1:-default}"
来源：http://dali.chenzaomai.com/Article/details/gt2udmrrvxk.html

[R06] 判断命令是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2uwfzmxpy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gt2qucdrdot.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gt2urhuayrc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xinyue.icu/Article/details/gt2nmmxxmlx.html

[R08] 数值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxhpdkwn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2nzzukoku.html

[R09] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gt2fbpaccin.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmcscekt.html

[R10] 正则匹配
来源：http://dali.cdnleiting.top/Article/details/gt2akuiwfuf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2wldqglel.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gt2crkdluci.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gt2muliibpg.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gt2szuululm.html

stop)  echo "停止" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2yvqoqdlr.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gt2bqrlprgg.html

esac
来源：http://dali.gotoacloud.top/Article/details/gt2ijrtsoix.html

[R12] for 遍历文件
来源：http://dali.dashuyun.cn/Article/details/gt2owseflif.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufohqcdb.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gt2ryapxlse.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gt2bcoyphne.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gt2csuohtof.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gt2qrjfnuwa.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vzheocdk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gt2kuinvghj.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gt2hzfidcaq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2taaidcew.html

[R17] 数组定义与取值
来源：http://dali.tanke756.top/Article/details/gt2uxsrbfhu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnqzz.top/Article/details/gt2gioicmak.html

[R18] 遍历数组
来源：http://dali.pycfn.com/Article/details/gt2vhibncbd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.bjfxy.top/Article/details/gt2zozvuggd.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gt2mwlppwxl.html

echo "${#arr[@]}"
来源：http://dali.sysykeji.top/Article/details/gt2ourwyqqh.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gt2rgwctsau.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fengsongda.top/Article/details/gt2xqotviiv.html

[R21] 字符串长度
来源：http://dali.fzhhl.top/Article/details/gt2qfdcrgbp.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gt2ypytnkxo.html

[R22] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2byidmwot.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gt2venqhmzb.html

[R23] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gt2gfrhyunn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gt2cpeowzfd.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2dellcvns.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ydzc1.top/Article/details/gt2fquvsaie.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvopqzgd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zdqjudy.top/Article/details/gt2ssjtyzcz.html

[R26] 命令替换
来源：http://dali.hfpthk.cn/Article/details/gt2bmcfulzn.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gt2jafbzipz.html

[R27] 算术展开
来源：http://dali.chenzaomai.com/Article/details/gt2auzjqlyj.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gt2cwajuiii.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gt2sesoqbjz.html

echo "scale=2; 10/3" | bc
来源：http://dali.hysaishi.cn/Article/details/gt2vxcpseum.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gt2vanhvapu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gt2yjntbydf.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gt2bzxoapcx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gt2bmrxueae.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gt2xkhpylzp.html

f() { local x=1; echo "$x"; }
来源：http://dali.0kj1m.cn/Article/details/gt2ipmtcxyh.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wjehoyvs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2xzjxgyol.html

[R33] 捕获错误并提示行号
来源：http://dali.cdnleiting.top/Article/details/gt2bveynmjr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gt2djuwmydj.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gt2odvpfrvm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gt2uksqucxo.html

[R35] 后台执行并等待
来源：http://dali.yuanzhike.top/Article/details/gt2ylgxjfua.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cucudq.cn/Article/details/gt2zauquszl.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gt2yimdythh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gt2oftbmean.html

[R37] 把输出赋给变量
来源：http://dali.jlsjyb.cn/Article/details/gt2tdfschqt.html

files=$(ls -1)
来源：http://dali.shzxlz.cn/Article/details/gt2qyacnoag.html

[R38] 管道串联
来源：http://dali.chenlongwang.top/Article/details/gt2nghistfh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgufenzy.top/Article/details/gt2minwaszf.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gt2cyovtoot.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gt2mhomvwib.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gt2aoorhkvx.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gt2aawjrblw.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gt2tgohohpb.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gt2mmcerugo.html

[R42] 输入重定向
来源：http://dali.guannengcc.top/Article/details/gt2ywffimid.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gt2kklhqdgm.html

[R43] 按名字查找文件
来源：http://dali.dashuyun.cn/Article/details/gt2qmywveyn.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gt2jlyijbtb.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gt2uxlqestd.html

find . -mtime -7 -type f
来源：http://dali.hfpthk.cn/Article/details/gt2jsnvjiyt.html

[R45] 批量删除
来源：http://dali.havefunace.top/Article/details/gt2fjbxucqp.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gt2kkxnizno.html

[R46] 递归替换文件内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwdbqgnd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gaohongyu789.top/Article/details/gt2xrhwvswv.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gt2wsyhnguy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2japjzvhl.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gt2erecvhqk.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbwohhuy.html

[R49] awk 带条件
来源：http://dali.jinqigufen.top/Article/details/gt2wnvuzjcx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikzeonho.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gt2migkglyd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2vuvyowqh.html

[R51] 排序去重取前几
来源：http://dali.hammf.cn/Article/details/gt2rgyvmsqy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gt2aheccoqm.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gt2wcowtljb.html

wc -l a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2vktvuiex.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjjviqxv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gt2sertouct.html

[R54] 比较两个文件
来源：http://dali.xziqi.cn/Article/details/gt2dlakrpyk.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2bcakikps.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gt2gdfjktjz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gt2vumgomsr.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gt2ktcvuhps.html

scp file user@host:/path/
来源：http://dali.fengsongda.top/Article/details/gt2fvifrcdz.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gt2jynvgevr.html

ssh user@host 'uptime'
来源：http://dali.hysaishi.cn/Article/details/gt2erdvoulj.html

[R58] 下载文件
来源：http://dali.jinqigfzy.top/Article/details/gt2bkpwtkfk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjqbzurs.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2yycmbafh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gt2iglgoqoy.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2bhxvrdoy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.iojbl.cn/Article/details/gt2npiptdbk.html

[R61] 磁盘占用
来源：http://dali.kuanghao11.cn/Article/details/gt2vtumnyoa.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gt2gdbvwpde.html

[R62] 找最占空间的文件
来源：http://dali.guannengcc.top/Article/details/gt2chevwtxa.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258.top/Article/details/gt2uqgjcpqo.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gt2stwnrvqn.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gt2ydkfvdrq.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gt2qupuvsjn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hywenlv.cn/Article/details/gt2hiehdxfu.html

[R65] 查看端口占用
来源：http://dali.tianlin.xyz/Article/details/gt2drsxniko.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwzlnvlx.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gt2nwhdidxj.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gt2gdbhrsth.html

[R67] 生成随机十六进制串
来源：http://dali.yj202588.top/Article/details/gt2xhijjnxo.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gt2fxdbjwek.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gt2dcahaygk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2uchmwmoq.html

[R69] 生成随机密码
来源：http://dali.ppjwa.cn/Article/details/gt2mhxmfyvd.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gt2mfzeeoxh.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zytgidmy.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gt2wgjurnxx.html

[R71] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2jjkstyyi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gt2sujuspmy.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gt2vojvjgow.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvproqlo.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gt2uewgdvfj.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gt2chyjgknt.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gt2fegbungk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.c1oappe.top/Article/details/gt2utveeguh.html

[R75] 导出环境变量
来源：http://dali.ehwqpu.com/Article/details/gt2fnowcsny.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gt2azvhvcxi.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gt2qrgwhsdn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gt2htnovszp.html

[R77] 读取用户输入
来源：http://dali.cqqwz.cn/Article/details/gt2porqtrhn.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gt2hqhdeqgf.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gt2omvbmsoe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tian-w.cn/Article/details/gt2gwsmuuap.html

[R79] 解析命令行选项
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwhzvbjj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sxryk.cn/Article/details/gt2prhjxtqs.html

[R80] 查看脚本执行耗时
来源：http://dali.xylfe.cn/Article/details/gt2hqztskst.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhuzluzi.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2bdwdapql.html

S. C / C++ 专题
来源：http://dali.haohaochexian.top/Article/details/gt2ijvldnzy.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2mqzflwjk.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2rmyyriwo.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gt2ukqgrvcd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2asagyxdg.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gt2idcbcjfy.html

int a = 10; printf("%d\n", a);
来源：http://dali.cqqwz.cn/Article/details/gt2npulitsh.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mubcqfgq.html

int x; scanf("%d", &x);
来源：http://dali.bjfxy.top/Article/details/gt2ovdxkqan.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gt2plyokgyz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2fofmkkcz.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gt2mpghglnk.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gt2tojyaqzy.html

[S06] C：字符串比较
来源：http://dali.tanke756.top/Article/details/gt2hhdtgqaf.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gt2jdhpicoc.html

[S07] C：数组遍历求和
来源：http://dali.yuxming.cn/Article/details/gt2cwhrjcyc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xziqi.cn/Article/details/gt2uyzkyrmq.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gt2ltbvyjnn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhixingplan.top/Article/details/gt2masyxaiw.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258.top/Article/details/gt2vmnwbagt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gt2zsbkcxfs.html

[S10] C：指针与解引用
来源：http://dali.mhx1999.top/Article/details/gt2pjqrucnc.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzwbihib.html

[S11] C：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2doumdqfs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ydzc1.top/Article/details/gt2hrcvopqz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gt2dctdbhgs.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gt2basfczfj.html

[S12] C：写文件
来源：http://dali.guowangkeji.top/Article/details/gt2nryvwums.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gt2umxvdqzv.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gt2ztkbxyqu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gt2pgyjgdob.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2cuqknjvo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gt2pddvxpgu.html

[S15] C：类型转换
来源：http://dali.cdnleiting.top/Article/details/gt2qnlgnkgd.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gt2vizgcaiq.html

[S16] C：位操作置位
来源：http://dali.cashguo.top/Article/details/gt2caodkbgd.html

x |= (1 << 3);
来源：http://dali.jinqigufen.top/Article/details/gt2ibodgqfz.html

[S17] C：安全拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2eyzmrbfi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj202588.top/Article/details/gt2unwzbqgy.html

[S18] C：命令行参数
来源：http://dali.zhixingplan.top/Article/details/gt2ntgtzgwu.html

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gt2osthsoer.html

[S19] C：快速排序
来源：http://dali.mhx1999.top/Article/details/gt2nidyncdi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gt2zernchqi.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gt2tqqijygs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gt2imkqcojx.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2ichdqdlz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gt2xqgxcaxb.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbvvoflh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gt2mmzuxqia.html

[S23] C：随机数
来源：http://dali.ppjwa.cn/Article/details/gt2bjygeqqa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gt2wwfoqhel.html

[S24] C：获取本地时间
来源：http://dali.ehwqpu.com/Article/details/gt2etztmeev.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gt2obzaeabq.html

[S25] C：内存拷贝
来源：http://dali.aibaodan.cn/Article/details/gt2tdnjhunw.html

memcpy(dst, src, n);
来源：http://dali.hnqzz.top/Article/details/gt2mooiylrl.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gt2mcsxciud.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gt2wkptjyqt.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbjtnket.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2qbmeoyhh.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gt2eughwoop.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gt2rydntowl.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gt2epeultkb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sysykeji.top/Article/details/gt2cmischre.html

[S30] C：头文件保护
来源：http://dali.yonumen.top/Article/details/gt2eluxpzms.html

#ifndef X_H
来源：http://dali.jiagoushi.top/Article/details/gt2kgsryxdb.html

#define X_H
来源：http://dali.jqgufenzy.top/Article/details/gt2liogiwoh.html

#endif
来源：http://dali.yanxiufei.cn/Article/details/gt2ievzazzx.html

[S31] C++：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2sjdumkrz.html


<!-- 参考信息 -->