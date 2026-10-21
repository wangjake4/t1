代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gtyzrwqlsn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gtpbevbrwf.html

[Q68] 保存点
来源：http://dali.c1oappe.top/Article/details/gtpgupwstk.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcogksqhx.html

ROLLBACK TO sp1;
来源：http://dali.xuanzx.com/Article/details/gtqvaymsld.html

[Q69] 查看执行计划
来源：http://dali.jinqigfzy.top/Article/details/gtwofkypgy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jlsjyb.cn/Article/details/gtgqquewsh.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gtsjrxczli.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gtumnrsbfl.html

[Q71] 查看建表语句
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmlzxbzo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj202588.top/Article/details/gtoeurqsvp.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gtfbwsosui.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtvhwkadha.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gtylhvjpez.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gtvcuxhrmd.html

[Q74] 强制使用索引
来源：http://dali.zhiwuduotai.top/Article/details/gtrnpajnwm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gtefbejtwg.html

[Q75] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtxrxyfuzq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtycxfaofy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yueranfly.top/Article/details/gtyahmrreo.html

[Q76] 按天统计
来源：http://dali.jyoumei.cn/Article/details/gtlbmxbxlx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258888.top/Article/details/gthzrppuvr.html

[Q77] 时间加减
来源：http://dali.gotoacloud.top/Article/details/gtgvtoftli.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gtzjkokpau.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gtcaxtruul.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gtpacflvwr.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtnizszjdu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.kuanghao11.cn/Article/details/gtuyflxcii.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gtluxzzlrx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtyqddbotc.html

[Q81] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtevxldodh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtmscymvef.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gtnmklmiht.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtspofbvil.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtdziixrva.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrtnicxb.html

[Q84] 去除首尾空格
来源：http://dali.dashuyun.cn/Article/details/gtznhlcqss.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gteszfowbf.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gtswpuyblc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zdqjudy.top/Article/details/gtoeeocfuj.html

[Q86] 读取 JSON 字段
来源：http://dali.cqqwz.cn/Article/details/gtwzdesgqx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hongshengwenyu.top/Article/details/gtlqpktggs.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gtqhcnyxdd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tian-w.cn/Article/details/gtaepfuheo.html

[Q88] 行转列（条件聚合）
来源：http://dali.havefunace.top/Article/details/gtzwsgytru.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuanzhike.top/Article/details/gtoqzriohq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtdzfnhowg.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gtivouddbf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtcviaeyrt.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gtkcchfoic.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gtabfifdgd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlhznhilq.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtlqumgpsl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfadqkxbq.html

[R01] shebang 与严格模式
来源：http://dali.smart0.xyz/Article/details/gtlrklpwdz.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtygarptnz.html

set -euo pipefail
来源：http://dali.nanxinkj.top/Article/details/gtpbiqusiy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gtrnodpyvq.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrgtfdtv.html

[R03] 只读变量
来源：http://dali.tianlin.xyz/Article/details/gthdugyumf.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gtamaolsxp.html

[R04] 位置参数
来源：http://dali.zhongyouzk.top/Article/details/gtkmahjnmz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dashuyun.cn/Article/details/gtkucplgtu.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gtblfrfkkc.html

name="${1:-default}"
来源：http://dali.hongshengwenyu.top/Article/details/gtvlayirfe.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtedpqysjp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtbvojidgg.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gtvroisbib.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gtrcgoliww.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gtbwqspnyi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jyoumei.cn/Article/details/gtbvizymfh.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtzzkcbkxw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtfbmvrzrf.html

[R10] 正则匹配
来源：http://dali.sxryk.cn/Article/details/gtomikrboc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtfkdyiiii.html

[R11] case 多分支
来源：http://dali.xuanzx.com/Article/details/gtpxifyddw.html

case "$1" in
来源：http://dali.wangshuangyany.cn/Article/details/gtjgohqwnt.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtfbnzlmye.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gtdvqocsag.html

*)     echo "未知命令" ;;
来源：http://dali.yuxming.cn/Article/details/gtcgztpmwa.html

esac
来源：http://dali.birdmap.top/Article/details/gtvfdodics.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gtmfqfltpx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gtwsqvblzr.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gtnyamaekl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gtgmvsmppu.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzelbryop.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtvlouxvll.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtysabdddt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtycmqmqvm.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gtvormdnyh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtnbslfuhg.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gtcpbcuauj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gtualglfpw.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gtvriteuhk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtfqnrxqjy.html

[R19] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtqsvsnvir.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gtrqbnhksi.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gtwdrulzbx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gtolbxewlr.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtcfkrptsc.html

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gtwpmwcewf.html

[R22] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gtbkxcegex.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gtapilhsgs.html

[R23] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtafkcwpga.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gtlmwdkzyk.html

[R24] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtiobmsgzn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gtwvgtrcka.html

[R25] 去后缀 / 去前缀
来源：http://dali.zycfv.cn/Article/details/gtdkphekoo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gtudmuedda.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gtmdrngofn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gtcjykpwro.html

[R27] 算术展开
来源：http://dali.vqdsnc.cn/Article/details/gtxqqawjkn.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gtajebxvec.html

[R28] 浮点运算
来源：http://dali.cqqwz.cn/Article/details/gtasklrwje.html

echo "scale=2; 10/3" | bc
来源：http://dali.yongpay.top/Article/details/gtacfvyufv.html

[R29] 定义函数
来源：http://dali.316326.xyz/Article/details/gtfzmanlux.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hysaishi.cn/Article/details/gtgrfmpvkz.html

[R30] 函数返回状态码
来源：http://dali.zhixingplan.top/Article/details/gtzfyaqevc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gtvidyewnh.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gttthzqlfj.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gthfudvxrx.html

[R32] 参数个数校验
来源：http://dali.dashuyun.cn/Article/details/gtarvgfdps.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtgtfyleoz.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gtrfdjglra.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gtdbcpljld.html

[R34] 退出时清理
来源：http://dali.guowangkeji.top/Article/details/gtbwbqunww.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtjmjbwrao.html

[R35] 后台执行并等待
来源：http://dali.zhengqikj.top/Article/details/gtfmlydxxq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gtnhircqbw.html

[R36] 并发执行多个任务
来源：http://dali.pycfn.com/Article/details/gtwanwyzyi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gtijrbsyvc.html

[R37] 把输出赋给变量
来源：http://dali.hywenlv.cn/Article/details/gtcvcgygib.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gttatraohh.html

[R38] 管道串联
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfsiynmo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258888.top/Article/details/gtajnexrbf.html

[R39] 重定向标准输出与错误
来源：http://dali.andypj.xyz/Article/details/gtrbrjsinh.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtulzpgdow.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gtgqhtzdgu.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gtysjvndar.html

[R41] 丢弃输出
来源：http://dali.tianlin.xyz/Article/details/gtcxqgeejx.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtzrpcvchj.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gtgxieykwv.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gtgfmqyzak.html

[R43] 按名字查找文件
来源：http://dali.zycfv.cn/Article/details/gtpzztsnol.html

find . -name "*.log" -type f
来源：http://dali.gzhubu.top/Article/details/gtonubfnmp.html

[R44] 按修改时间查找
来源：http://dali.andypj.xyz/Article/details/gtominsstw.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gteefmjcwf.html

[R45] 批量删除
来源：http://dali.fzhhl.top/Article/details/gtassrehmw.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gtxozmfiui.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gttfmnhiow.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gttyerjpav.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtizudmtfx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtdeopmojv.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gtuckqzwmp.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtofcoeaks.html

[R49] awk 带条件
来源：http://dali.haohaochexian.top/Article/details/gtrepkqkuj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xziqi.cn/Article/details/gtahfuirkh.html

[R50] awk 求和
来源：http://dali.yj20258888.top/Article/details/gtjtlhwsrn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvohnhdl.html

[R51] 排序去重取前几
来源：http://dali.fzhhl.top/Article/details/gtomkwlumu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sxryk.cn/Article/details/gtdmqqphst.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gtbdclfjqd.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtbfcekrjh.html

[R53] 查看文件头与实时尾
来源：http://dali.shangyingyoupin.top/Article/details/gtaibqhknx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gtelkpmomq.html

[R54] 比较两个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtmnpntktq.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gtbvtvxbec.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivlxjckx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gtkwyhtves.html

[R56] 远程拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtznnhvtwk.html

scp file user@host:/path/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdipaalu.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gtqpakkwzn.html

ssh user@host 'uptime'
来源：http://dali.hnqzz.top/Article/details/gtpfrnqxnf.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gtzgvvinhx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dashuyun.cn/Article/details/gtvhptpjlh.html

[R59] 发 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtzttkrojq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxktbsqcq.html

[R60] 只看 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gtctagiaaz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jyoumei.cn/Article/details/gtpzzypxyw.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gtmwovqtjc.html

df -h;  du -sh *
来源：http://dali.bjfxy.top/Article/details/gtpnwvecat.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gtaxdszhjk.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gtztrcjqkb.html

[R63] 内存与进程
来源：http://dali.hongshengwenyu.top/Article/details/gtrwufocmr.html

free -h;  ps aux | grep nginx
来源：http://dali.cucudq.cn/Article/details/gtympptdpp.html

[R64] 结束进程
来源：http://dali.c1oappe.top/Article/details/gtycqufkhw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gtchzmtjyj.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gtkcncpbxw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfgasqvo.html

[R66] 定时任务
来源：http://dali.jianghu66.top/Article/details/gtrvuiyqdc.html

crontab -e;  crontab -l
来源：http://dali.cashguo.top/Article/details/gtftfnuueu.html

[R67] 生成随机十六进制串
来源：http://dali.ybcxt.top/Article/details/gtccejejru.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gttgdigiyk.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gtehfbqjjz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhengqikj.top/Article/details/gtzwmfgzid.html

[R69] 生成随机密码
来源：http://dali.sysykeji.top/Article/details/gtqgolsrxj.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gtrnfhzifj.html

[R70] 时间戳与互转
来源：http://dali.jinqigfzy.top/Article/details/gtpkfdehyy.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gtjkwkygoe.html

[R71] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gteuxjzxhk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtdmuygoaf.html

[R72] 等待端口就绪
来源：http://dali.hnxiangtu.top/Article/details/gtlvookkdo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gthxxevxng.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gtlbvimiwz.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtzgzthyyy.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gtvipqqunm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.iojbl.cn/Article/details/gtjfunbhcq.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtedlaptjf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xinyue.icu/Article/details/gtumwwrcqq.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gttpcrnjuj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtdkaypytw.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtxvyrntet.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gtaeoliaag.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gtekpviiak.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xylfe.cn/Article/details/gttavdhahy.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gtoprifhbs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gtkuzwrybv.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gtwilxuugs.html

time ./run.sh
来源：http://dali.smart0.xyz/Article/details/gttbnechit.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtoegowiyo.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gtqsnfrbsf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtjoiwxshh.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtlvkxfuod.html

#include <stdio.h>
来源：http://dali.nanxinkj.top/Article/details/gtctddmbrb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgufenzy.top/Article/details/gtakljbgpo.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gtohubiiga.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gtxxugdoli.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gtkialopsk.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gtreuxumxv.html

[S04] C：字符串复制
来源：http://dali.zhengqikj.top/Article/details/gtycyvbgtt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gtvpzjmozc.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtbyylfrco.html

strlen(s)
来源：http://dali.ppjwa.cn/Article/details/gtzqhgzdhn.html

[S06] C：字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtjtkxxghd.html

strcmp(a, b) == 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtogupxv.html

[S07] C：数组遍历求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfxpdndd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.smart0.xyz/Article/details/gtjycxwmkm.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpqzrvnt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gtzhtdzhbp.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gtjpuvgkwl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.birdmap.top/Article/details/gthexnggoh.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewrbhbkp.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gtrxyrhqyn.html

[S11] C：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtkdakcviz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gtamhaghmk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gtmytbkhrw.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvbpjnmf.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gtsllgjzic.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtspfjqbni.html

[S13] C：宏定义
来源：http://dali.gzhubu.top/Article/details/gtgqdobhrs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtlhlwhljp.html

[S14] C：枚举
来源：http://dali.pycfn.com/Article/details/gtjhseftwr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pengpengdd.cyou/Article/details/gtmdcvfeot.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gtialwiewf.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gtlvjugvsg.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gtpfufgqoi.html

x |= (1 << 3);
来源：http://dali.zycfv.cn/Article/details/gtthytjaoh.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtvdaonhrg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gogol.net.cn/Article/details/gtwxledqxc.html

[S18] C：命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtgmyjbvyr.html

int main(int argc, char **argv)
来源：http://dali.redwolf501.top/Article/details/gtwqeryjla.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gtqdfedidc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtlfngtcgl.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gtlzeqwxta.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gtfjgxlbje.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gtlxvrkqes.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gtwwdclxii.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gtznbiihkl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gtbccfhlbw.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gtjaglecob.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aizwys.cn/Article/details/gtrzihcvbc.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gtyyjybbdm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gtprtnafod.html

[S25] C：内存拷贝
来源：http://dali.smart0.xyz/Article/details/gtkgiddvil.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gtyzosqnii.html

[S26] C：内存清零
来源：http://dali.hnxiangtu.top/Article/details/gthivvwisp.html

memset(a, 0, sizeof a);
来源：http://dali.chenzaomai.com/Article/details/gtacwxoupj.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gtqkgdttui.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtrpocvyag.html

[S28] C：静态变量
来源：http://dali.sysykeji.top/Article/details/gthhhlnskn.html

static int counter = 0;
来源：http://dali.meibo888.top/Article/details/gtvmnbaxvx.html

[S29] C：变参函数
来源：http://dali.9152youxi.cn/Article/details/gtvprorrpy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gtvisaqykf.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gtfcljsais.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gtkasaqolg.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gtjnohiywg.html

#endif
来源：http://dali.yuxming.cn/Article/details/gtaowrfxql.html

[S31] C++：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtaqinkmvh.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gtljevecrc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuanzhike.top/Article/details/gtyvbgszdm.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gtecqpnxse.html

std::string s = "hi";  s += "!";
来源：http://dali.iojbl.cn/Article/details/gtcotnglpa.html

[S33] C++：vector 增删
来源：http://dali.xziqi.cn/Article/details/gtdbawgyqx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gthnouubzy.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gteblrdjgw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtncfihjva.html

[S35] C++：map
来源：http://dali.cashguo.top/Article/details/gtxbssheee.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtxuitazun.html

[S36] C++：unordered_map
来源：http://dali.jinqigfzy.top/Article/details/gtsbpqzyoz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtezzzrhtx.html


<!-- 参考信息 -->