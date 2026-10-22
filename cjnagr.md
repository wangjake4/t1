代发 wailian999

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gtryxpbswx.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gtlpeagfdn.html

[Q66] 行锁查询
来源：http://dali.cucudq.cn/Article/details/gtbqfcpjhf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jlsjyb.cn/Article/details/gtgakoucvr.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gtbatdafxg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gtgzjjadjt.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gtljsolwyr.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gtxedlinnr.html

ROLLBACK TO sp1;
来源：http://dali.aizwys.cn/Article/details/gtwowlpeyq.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gtuotsiido.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhongyouzk.top/Article/details/gtqtoboreu.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxmxksrm.html

ANALYZE TABLE users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnekmlpwz.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gtipvoavix.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gtzyqduvhx.html

[Q72] 查看索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtfruzcdwv.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gtldfsxmvy.html

[Q73] 查看表状态
来源：http://dali.ivvv.top/Article/details/gtcrrshbvr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gtyyelqawr.html

[Q74] 强制使用索引
来源：http://dali.316326.xyz/Article/details/gtdsvkddpo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjasddwh.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtkskximoa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtpydxulsa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zdqjudy.top/Article/details/gthonhvvyt.html

[Q76] 按天统计
来源：http://dali.cashguo.top/Article/details/gtkdipwtfx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhoulong.xyz/Article/details/gtephdgdxt.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gtgdwnnczl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhtixdok.html

[Q78] 当前时间
来源：http://dali.mhx1999.top/Article/details/gtoyoltxot.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gtlcmecqem.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gtsmiseorq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ppjwa.cn/Article/details/gtxnpqzqfg.html

[Q80] 字符串截取
来源：http://dali.sxryk.cn/Article/details/gtynjlguku.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtkjgbrevd.html

[Q81] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtaybusrrr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtycppadzn.html

[Q82] 字符长度与字节长度
来源：http://dali.iojbl.cn/Article/details/gtqkdvgssf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtzivexqsl.html

[Q83] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtwdyjfgky.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtrujkwirb.html

[Q84] 去除首尾空格
来源：http://dali.mhx1999.top/Article/details/gtbmadwbtm.html

SELECT TRIM(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtqohebfhe.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutdwdohe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xinyue.icu/Article/details/gtwmmjbmzx.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gtareagpqr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.316326.xyz/Article/details/gtqitwhmxn.html

[Q87] JSON 字段做条件
来源：http://dali.sysykeji.top/Article/details/gtmhbvjztt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shangyingyoupin.top/Article/details/gtlcrzlvak.html

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gtqopxykoa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gtnlyzonqx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxpuuszh.html

[Q89] 判断表是否存在
来源：http://dali.ehwqpu.com/Article/details/gtppefpgvb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sxryk.cn/Article/details/gtyrodqduy.html

[Q90] 生成序号列
来源：http://dali.xylfe.cn/Article/details/gtulzzyrvh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhoulong.xyz/Article/details/gtseznmkmw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpixeson.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gtfheldwzs.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtlluebpey.html

[R01] shebang 与严格模式
来源：http://dali.jyoumei.cn/Article/details/gtcwsvsjte.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gtrxomzqhx.html

set -euo pipefail
来源：http://dali.cashguo.top/Article/details/gtvnwsaqnj.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangtech.top/Article/details/gtedeslsfd.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gtrticummj.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtjfvzpebd.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gtpohojwiw.html

[R04] 位置参数
来源：http://dali.chenlongwang.top/Article/details/gttfzaanxi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gogol.net.cn/Article/details/gtomlvyrzt.html

[R05] 参数默认值
来源：http://dali.yuxming.cn/Article/details/gtqgbxyqoo.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gtkjpbbnpw.html

[R06] 判断命令是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gteflysoij.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gtnlgfmyvr.html

[R07] if 判断文件
来源：http://dali.havefunace.top/Article/details/gtnpietwbo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtxdppbyod.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gttzeyszqb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtaeqnwkge.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gtqwnadmdm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yangfankeji.com/Article/details/gtfcnnbwfl.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gtgqawuyow.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtxzlaikpw.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gtgbvjtvyg.html

case "$1" in
来源：http://dali.sweek.top/Article/details/gtedyyfncv.html

start) echo "启动" ;;
来源：http://dali.chenzaomai.com/Article/details/gtaecyzcta.html

stop)  echo "停止" ;;
来源：http://dali.jyoumei.cn/Article/details/gtxkzlsucx.html

*)     echo "未知命令" ;;
来源：http://dali.yvedp.cn/Article/details/gtbiyudlhd.html

esac
来源：http://dali.jiagoushi.top/Article/details/gtclzoqeio.html

[R12] for 遍历文件
来源：http://dali.jinqigufen.top/Article/details/gtlhhlxlti.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ybcxt.top/Article/details/gtruwijgvj.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtqlgsbtqu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtrtzigarw.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gtfxkdfvto.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtrxiolfpo.html

[R15] while 逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtqkdrtbod.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtcxufwbuy.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gtwuaekxsi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtihblxdmj.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gtymrrkdos.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtgkdacyya.html

[R18] 遍历数组
来源：http://dali.cdnleiting.top/Article/details/gtxfcxuclc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gtdwwcscnu.html

[R19] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtcakpnsgm.html

echo "${#arr[@]}"
来源：http://dali.xziqi.cn/Article/details/gtopiktesm.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtsszawhkq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtvvrprxhm.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtkwqeckfl.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gtusgwggut.html

[R22] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtjqrhjpab.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gtdlgiamha.html

[R23] 字符串替换
来源：http://dali.hammf.cn/Article/details/gthzcfqpbp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbukzjmgo.html

[R24] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gthgwgyast.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkxvxowh.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gtjhomvbmx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.andypj.xyz/Article/details/gtqiotajsh.html

[R26] 命令替换
来源：http://dali.chenlongwang.top/Article/details/gtytkrvfyu.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gtgyjrwjbt.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gtileoqtpw.html

echo $((1 + 2 * 3))
来源：http://dali.chenjidiqi.icu/Article/details/gttwscmcqi.html

[R28] 浮点运算
来源：http://dali.hongshengwenyu.top/Article/details/gtihvggqln.html

echo "scale=2; 10/3" | bc
来源：http://dali.shzxlz.cn/Article/details/gtihbwfbft.html

[R29] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gtdxnejnfy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpxdnlca.html

[R30] 函数返回状态码
来源：http://dali.yvedp.cn/Article/details/gtoxfjujna.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gtqlfemsbv.html

[R31] 局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdapevig.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkjbjmuwx.html

[R32] 参数个数校验
来源：http://dali.yuxming.cn/Article/details/gtouqvpfab.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gtxaasprly.html

[R33] 捕获错误并提示行号
来源：http://dali.svipenyu.cn/Article/details/gthdembxge.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gtzqutllxr.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gtagxqslfe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtrxqqpyzx.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gtaxjzegdo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.haohaochexian.top/Article/details/gtulzzeerg.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gtkdhtocrb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gtapxotuze.html

[R37] 把输出赋给变量
来源：http://dali.wangdashe.top/Article/details/gtupuevokz.html

files=$(ls -1)
来源：http://dali.jianghu66.top/Article/details/gtkwpsxjlb.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gtawxfypuo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gtnpiloori.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqyhfgjn.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcncznpl.html

[R40] 追加写日志
来源：http://dali.dashuyun.cn/Article/details/gtrygukajw.html

echo "log" >> out.log
来源：http://dali.jqgfzy.top/Article/details/gtdaecwvpn.html

[R41] 丢弃输出
来源：http://dali.havefunace.top/Article/details/gtmevxgjko.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtbzduwezd.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gtpgcyvwwv.html

wc -l < a.txt
来源：http://dali.yj20258888.top/Article/details/gtevbojkou.html

[R43] 按名字查找文件
来源：http://dali.tianlin.xyz/Article/details/gtjvjxswet.html

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gtosqmdric.html

[R44] 按修改时间查找
来源：http://dali.xinyue.icu/Article/details/gtipkkozuf.html

find . -mtime -7 -type f
来源：http://dali.chenlongwang.top/Article/details/gtpgeibgvy.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gtgbxasfqr.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtnvdhfgqe.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gtraxeqdls.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shangyingyoupin.top/Article/details/gtbyxnnbtu.html

[R47] sed 单行替换
来源：http://dali.chenlongwang.top/Article/details/gtkhvbabsp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtuqcjpzrw.html

[R48] awk 取指定列
来源：http://dali.chenlongwang.top/Article/details/gtpyxmpzvq.html

awk '{print $1, $3}' a.txt
来源：http://dali.cashguo.top/Article/details/gtvzjkapag.html

[R49] awk 带条件
来源：http://dali.ivvv.top/Article/details/gtmnncsowp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gtdmlawjmv.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gtigbuturi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtuyxhnuua.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gtigazojcf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.feifeiyinyue.top/Article/details/gtxfxdntfz.html

[R52] 统计行数
来源：http://dali.wangdashe.top/Article/details/gtsdxrutyr.html

wc -l a.txt
来源：http://dali.yangfankeji.com/Article/details/gtbipfjbpu.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gtgcriuwll.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gtzjxlwzsg.html

[R54] 比较两个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtzifhrvar.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gtcngjcwuj.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gtgecrvbjh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gtssuouciz.html

[R56] 远程拷贝
来源：http://dali.xinyue.icu/Article/details/gtxprebgtn.html

scp file user@host:/path/
来源：http://dali.svipenyu.cn/Article/details/gtrdutbhoi.html

[R57] 远程执行命令
来源：http://dali.birdmap.top/Article/details/gtvnjwolab.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gtinatartw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gtewproagm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gtmbxmvshg.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtazusccdo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gtujopsnai.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtpfsdwsuf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtuhhacjvr.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gtgnkllrio.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gteicvsixs.html

[R62] 找最占空间的文件
来源：http://dali.yj20258888.top/Article/details/gtmdukdamn.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gtmdetclue.html

[R63] 内存与进程
来源：http://dali.0kj1m.cn/Article/details/gtuuktgqvd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gtitxgfnqz.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gtqozlhtxo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gtmcejmldz.html

[R65] 查看端口占用
来源：http://dali.hnqzz.top/Article/details/gtcafstyfm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hywenlv.cn/Article/details/gtzxwnqvof.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gtlrmdidls.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gteuonuwlq.html

[R67] 生成随机十六进制串
来源：http://dali.zhixingplan.top/Article/details/gtwvrafyql.html

openssl rand -hex 16
来源：http://dali.jinyuanbaomall.cn/Article/details/gtramnugeu.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gteercoyqz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtfcrlydyg.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gtdgxurpfy.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigfzy.top/Article/details/gtalovgoxn.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gtmykusabk.html

date +%s;  date -d @1700000000
来源：http://dali.zhixingplan.top/Article/details/gtabitvrey.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtmaxdpfet.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtmqnyoged.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gtzejiwkqy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtkqvxxhym.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtigduinmu.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gthscsycsg.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gtpzoeroxo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gtliqikdnq.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gtlivaykzl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gtjzqlsrps.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtrsykskjy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gtlwffltag.html

[R77] 读取用户输入
来源：http://dali.shuidangran.top/Article/details/gtvwblgaks.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gtqeqkievy.html

[R78] 交互式菜单
来源：http://dali.wangdashe.top/Article/details/gtesghvoez.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gteibljbef.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gtmlgkoyer.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cashguo.top/Article/details/gtbkxnatrs.html

[R80] 查看脚本执行耗时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalujirjv.html

time ./run.sh
来源：http://dali.zhixingplan.top/Article/details/gtanusdjpj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqycqohsn.html

S. C / C++ 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgmapplk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmjvfira.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtkbkugedy.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gtynxkmezo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvuhcdeub.html

[S02] C：变量与格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtrkxtzvdn.html

int a = 10; printf("%d\n", a);
来源：http://dali.ivvv.top/Article/details/gtumagxjmr.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gtjiavztpx.html

int x; scanf("%d", &x);
来源：http://dali.wangdashe.top/Article/details/gtigynnyya.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gtkggdvflh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.havefunace.top/Article/details/gtoxrcevka.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gtyvutfpbe.html

strlen(s)
来源：http://dali.nwbrower.top/Article/details/gtcnblbrck.html

[S06] C：字符串比较
来源：http://dali.zycfv.cn/Article/details/gtqouswlqo.html

strcmp(a, b) == 0
来源：http://dali.nwbrower.top/Article/details/gtrxybmuid.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gtciwowspz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258.top/Article/details/gtvsxychwi.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gttnqyrrlm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gtcwpnlvnn.html

[S09] C：结构体定义与初始化
来源：http://dali.c1oappe.top/Article/details/gtjmqemwmp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gtxeqwjgkr.html

[S10] C：指针与解引用
来源：http://dali.yj202588.top/Article/details/gtobmowhyp.html

int *p = &a;  *p = 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyujfokee.html

[S11] C：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gteniddduc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gtgthmavnh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gtmdkdyzjx.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gtkauxdmii.html

[S12] C：写文件
来源：http://dali.guowangkeji.top/Article/details/gthgclbkra.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtxenmzqwj.html

[S13] C：宏定义
来源：http://dali.yvedp.cn/Article/details/gtgkbhlwuz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenzaomai.com/Article/details/gtwlxhqvpm.html

[S14] C：枚举
来源：http://dali.gzhubu.top/Article/details/gtawyjmqul.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gteuqfugjc.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajbrxkis.html

(double) a / b
来源：http://dali.smart0.xyz/Article/details/gtqjfjzbff.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gtjrrpkcyo.html

x |= (1 << 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvqrkmva.html

[S17] C：安全拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtiqxfnwmy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yongpay.top/Article/details/gtrgrjngip.html

[S18] C：命令行参数
来源：http://dali.iojbl.cn/Article/details/gtxytfqnhq.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtcpbaqfdo.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtjbcyvmho.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtkqgllkjg.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gtcgehlukz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gthikwqcsn.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gtatalelrz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gthmkbvzwr.html

[S22] C：字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gtgtwvytkt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gtulfxjtsl.html

[S23] C：随机数
来源：http://dali.hammf.cn/Article/details/gtwhxxfjoh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtjokghpox.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gtzlarhbkz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gtvtehdzpf.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gtlhmjzpes.html

memcpy(dst, src, n);
来源：http://dali.yj20258888.top/Article/details/gtolkkisqu.html

[S26] C：内存清零
来源：http://dali.hnxiangtu.top/Article/details/gtppkvvjvl.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfjccdfu.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuvdsewj.html

const double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtxzruaozt.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gtsriybqsy.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtonktugxu.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gtaiebkmen.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gtswhhlsep.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gtnvudzdic.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gtrheiksfe.html

#define X_H
来源：http://dali.zhoulong.xyz/Article/details/gtotivkoen.html

#endif
来源：http://dali.shuidangran.top/Article/details/gtopqmvllj.html

[S31] C++：Hello World
来源：http://dali.mhx1999.top/Article/details/gtgzxfdvvk.html

#include <iostream>
来源：http://dali.jlsjyb.cn/Article/details/gtctmchoie.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsenyajgt.html

[S32] C++：字符串
来源：http://dali.ehwqpu.com/Article/details/gtzlfiusqf.html

std::string s = "hi";  s += "!";
来源：http://dali.iojbl.cn/Article/details/gtnzotwuyt.html

[S33] C++：vector 增删
来源：http://dali.guannengcc.top/Article/details/gtolmppjql.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gtbsjzidjv.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gtutxnjtve.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchzncloh.html


<!-- 参考信息 -->