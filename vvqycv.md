代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgpubbtk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zycfv.cn/Article/details/gtegimxrsx.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gtpnlllbvq.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtgybtnwkx.html

ROLLBACK TO sp1;
来源：http://dali.aizwys.cn/Article/details/gtplclnzdp.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gtwlwdiprh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.mhx1999.top/Article/details/gtitoklcdo.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gtcbylqvja.html

ANALYZE TABLE users;
来源：http://dali.fengsongda.top/Article/details/gtshzfiomr.html

[Q71] 查看建表语句
来源：http://dali.kuanghao11.cn/Article/details/gtnvupzloi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tanke756.top/Article/details/gtkqagrdol.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gtnqeveefk.html

SHOW INDEX FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtxobarozq.html

[Q73] 查看表状态
来源：http://dali.xuetiantiany.cn/Article/details/gtuditnwez.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xylfe.cn/Article/details/gtzkuzrzon.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gtoelvamyp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pengpengdd.cyou/Article/details/gthphbwdcj.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtlriiiwgd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtuniydywb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuanzhike.top/Article/details/gtsauoylwk.html

[Q76] 按天统计
来源：http://dali.ybcxt.top/Article/details/gtgzyttizh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gtpevyqpid.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gtdhrdrbgk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gtfbfrfphx.html

[Q78] 当前时间
来源：http://dali.guowangkeji.top/Article/details/gtetkozetx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ppjwa.cn/Article/details/gtxvpsgeeq.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpnshwzt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigfzy.top/Article/details/gtjyobcegk.html

[Q80] 字符串截取
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhlbbwjh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtspzqkqcf.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gthovmyofw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gtglokchaa.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gtbqqapaqt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtrywfvefa.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gthosxfwkz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtjqabsyou.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gtallugugi.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtiipcntxm.html

[Q85] 数值取整
来源：http://dali.iojbl.cn/Article/details/gthljainfz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtwjrbdmug.html

[Q86] 读取 JSON 字段
来源：http://dali.tianlin.xyz/Article/details/gtpemfqzqr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhiwuduotai.top/Article/details/gtfgrtvsmi.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gturjcuhbz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.c1oappe.top/Article/details/gteurniwnm.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxinkj.top/Article/details/gtduowmcig.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gttgzvjzta.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtidmdmuxs.html

[Q89] 判断表是否存在
来源：http://dali.sxryk.cn/Article/details/gtakgesehe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gthcliflud.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyydjigo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yanxiufei.cn/Article/details/gtcivpniww.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzkvsjrnd.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gtplicggci.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqxygiwov.html

[R01] shebang 与严格模式
来源：http://dali.mhx1999.top/Article/details/gtwsstaxpy.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gtstnxsoza.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gtaxgrwywk.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gtufqnccyz.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gtfbrrychh.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gtewavofay.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gtfknbuclp.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gttwhvagja.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gtpgmjqvow.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gtabayyece.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gtquqvyyzg.html

[R06] 判断命令是否存在
来源：http://dali.guowangkeji.top/Article/details/gtwirhqync.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtcsiihjlz.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gtmfvfcmek.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gtitnykdll.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtuoleqhzl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gtgftsaxzm.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtckkvijqp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gtunmfjrum.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtvcvmoclj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gtwqoazevi.html

[R11] case 多分支
来源：http://dali.316326.xyz/Article/details/gtpsfdpakf.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gtpanfjxfo.html

start) echo "启动" ;;
来源：http://dali.0kj1m.cn/Article/details/gtvmumdoll.html

stop)  echo "停止" ;;
来源：http://dali.fengsongda.top/Article/details/gtwotttiau.html

*)     echo "未知命令" ;;
来源：http://dali.pycfn.com/Article/details/gtaaxxquit.html

esac
来源：http://dali.chenlongwang.top/Article/details/gtcebifhtj.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gtwbrjdteg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gtfyplvcdm.html

[R13] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gtqqjvitwo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfqlcsco.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gtbfwxfppq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtrtismbfe.html

[R15] while 逐行读文件
来源：http://dali.meibo888.top/Article/details/gtokmszfcj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgfzy.top/Article/details/gtfjwdthmh.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gtudkbjekw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtfobygzyn.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtferrfvrr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gtdkuijowh.html

[R18] 遍历数组
来源：http://dali.aizwys.cn/Article/details/gtgylkqkco.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.svipenyu.cn/Article/details/gtonnwcoia.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtjxknbfxx.html

echo "${#arr[@]}"
来源：http://dali.sysykeji.top/Article/details/gtkdoykcgz.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gtmedvrknv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gtdztehwfy.html

[R21] 字符串长度
来源：http://dali.jianghu66.top/Article/details/gtokpzetfo.html

echo "${#s}"
来源：http://dali.jianghu66.top/Article/details/gtgzygrsja.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtnzrjyirk.html

echo "${s:0:5}"
来源：http://dali.daria6918.cn/Article/details/gtapcugxed.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtycimyaue.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.quarkkingdee.top/Article/details/gtqjahpcmr.html

[R24] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gtknourzue.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gaohongyu789.top/Article/details/gtczvglbjl.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gtcutaeway.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.haohaochexian.top/Article/details/gtifsairyy.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtsxjsepct.html

now=$(date +%F); echo "$now"
来源：http://dali.hongshengwenyu.top/Article/details/gtbjnyufwi.html

[R27] 算术展开
来源：http://dali.quarkkingdee.top/Article/details/gthemuercq.html

echo $((1 + 2 * 3))
来源：http://dali.aibaodan.cn/Article/details/gttnjylxxo.html

[R28] 浮点运算
来源：http://dali.fzhhl.top/Article/details/gtsfburqkg.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtzfbsaons.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtefqkocus.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gtenxvfoyo.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gtqhnjzugv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gtzlaihwpi.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtppurdbqi.html

f() { local x=1; echo "$x"; }
来源：http://dali.tianlin.xyz/Article/details/gthjswkrka.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gtbzssivlv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhtoihea.html

[R33] 捕获错误并提示行号
来源：http://dali.yongpay.top/Article/details/gtvlpqueht.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gtlvwlkvnv.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gtfdwfolqp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtibtuubva.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbqqqino.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtqapdyglh.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcgheihg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gtpztgyyvl.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrmhqbfz.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gtigknpdgi.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gtelmggtlr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj202588.top/Article/details/gtnjdkuyas.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gtnvqpjcxw.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtyekpblfx.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gtohpbksok.html

echo "log" >> out.log
来源：http://dali.9152youxi.cn/Article/details/gtolwvveor.html

[R41] 丢弃输出
来源：http://dali.snrcjt.cn/Article/details/gtfefigapn.html

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtwzmpgzan.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gtbeaozekj.html

wc -l < a.txt
来源：http://dali.hysaishi.cn/Article/details/gtjtsthgbh.html

[R43] 按名字查找文件
来源：http://dali.tianlin.xyz/Article/details/gtmyzouxys.html

find . -name "*.log" -type f
来源：http://dali.havefunace.top/Article/details/gtslfmmxdi.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gtanlspjrz.html

find . -mtime -7 -type f
来源：http://dali.guannengcc.top/Article/details/gtmgzxvyvf.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gtgwzqzknv.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gtueswmrjx.html

[R46] 递归替换文件内容
来源：http://dali.pengpengdd.cyou/Article/details/gtsdlpigjg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gtlfxphixd.html

[R47] sed 单行替换
来源：http://dali.tianlin.xyz/Article/details/gtyyydxtta.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.iojbl.cn/Article/details/gtwpwmlqrx.html

[R48] awk 取指定列
来源：http://dali.haohaochexian.top/Article/details/gtsnsmhwec.html

awk '{print $1, $3}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtirmxcyay.html

[R49] awk 带条件
来源：http://dali.ydzc1.top/Article/details/gtgtpirbhz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gtwxnvdayh.html

[R50] awk 求和
来源：http://dali.bjfxy.top/Article/details/gtosfdxehg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtybucjpdp.html

[R51] 排序去重取前几
来源：http://dali.pengpengdd.cyou/Article/details/gtpsauawus.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtsxcinebp.html

[R52] 统计行数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyddhtxcs.html

wc -l a.txt
来源：http://dali.yuanzhike.top/Article/details/gtbtznugpq.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gtnsawbyrl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gtbjhjupiw.html

[R54] 比较两个文件
来源：http://dali.yj20258888.top/Article/details/gteepncbtg.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gtxcvvigxl.html

[R55] 压缩与解压
来源：http://dali.ppjwa.cn/Article/details/gtywnmbpeh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shzxlz.cn/Article/details/gtvqadkfcs.html

[R56] 远程拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gteoysxqfr.html

scp file user@host:/path/
来源：http://dali.havefunace.top/Article/details/gtiupwnbxl.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gthrerojbl.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gtrznocpvb.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gtcjesovdp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.meibo888.top/Article/details/gtcjdhazvc.html

[R59] 发 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtovkcopui.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daxiang520.top/Article/details/gttwksivoc.html

[R60] 只看 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtspquknuk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sufxvd.cn/Article/details/gtqkrglilt.html

[R61] 磁盘占用
来源：http://dali.yongpay.top/Article/details/gtxrqtyvmj.html

df -h;  du -sh *
来源：http://dali.chenlongwang.top/Article/details/gtmnqekheb.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gtdzawzmgo.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gtswedvegk.html

[R63] 内存与进程
来源：http://dali.316326.xyz/Article/details/gtthetiafq.html

free -h;  ps aux | grep nginx
来源：http://dali.ppjwa.cn/Article/details/gtalremhhj.html

[R64] 结束进程
来源：http://dali.vqdsnc.cn/Article/details/gtwreohkpd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tianlin.xyz/Article/details/gtadjrohmk.html

[R65] 查看端口占用
来源：http://dali.zhoulong.xyz/Article/details/gteicsapcv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fengsongda.top/Article/details/gtqccjfmje.html

[R66] 定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtmyofizad.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gtcijyjxwi.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gtgdregjhr.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gtbkhuitsy.html

[R68] 计算文件校验值
来源：http://dali.yj20258888.top/Article/details/gtfzymqzvq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gthsucrmfb.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtgdxcziak.html

head -c 16 /dev/urandom | base64
来源：http://dali.yonumen.top/Article/details/gtcozwkhmr.html

[R70] 时间戳与互转
来源：http://dali.pycfn.com/Article/details/gtnuvwwrss.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gtwmjgynnq.html

[R71] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtnmcuokmk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shzxlz.cn/Article/details/gtcbltvslr.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gthezwhasx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtlqdduunv.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gtkrlxqkkd.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gtugzmcnvp.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gtjfduzpae.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gtoxatjzfs.html

[R75] 导出环境变量
来源：http://dali.gzhubu.top/Article/details/gtbdjcpnzu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gtrgwbyimb.html

[R76] 使用临时文件
来源：http://dali.9152youxi.cn/Article/details/gtjfdmybfe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtxlnjgbio.html

[R77] 读取用户输入
来源：http://dali.hammf.cn/Article/details/gtkveyuqsx.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gtgggbiops.html

[R78] 交互式菜单
来源：http://dali.zhixingplan.top/Article/details/gtdjgvfcxr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gtcahoyfin.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gtlmndzmsg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guowangkeji.top/Article/details/gtqtbzjaoz.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gtrxnzumno.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gtweuhqxqu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfcummhdz.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gtolhshlit.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtnopxrjzp.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtuwnrikjx.html

#include <stdio.h>
来源：http://dali.aizwys.cn/Article/details/gtcenaowyu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gtxeqwlsgg.html

[S02] C：变量与格式化输出
来源：http://dali.mhx1999.top/Article/details/gtgbqmonfb.html

int a = 10; printf("%d\n", a);
来源：http://dali.yanxiufei.cn/Article/details/gtwagxtqmo.html

[S03] C：读入整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflhbgtgm.html

int x; scanf("%d", &x);
来源：http://dali.vqdsnc.cn/Article/details/gtcddmhurp.html

[S04] C：字符串复制
来源：http://dali.hammf.cn/Article/details/gtnpfacykg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gtqioggzxa.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtovtraanv.html

strlen(s)
来源：http://dali.hammf.cn/Article/details/gtmfxokgea.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gttmsdnnbu.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gtqudoxsap.html

[S07] C：数组遍历求和
来源：http://dali.wangshuangyany.cn/Article/details/gtnamgjmwf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gttbnixerm.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxuanxn.top/Article/details/gtwjiwbdzp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258.top/Article/details/gtmvzqmspr.html

[S09] C：结构体定义与初始化
来源：http://dali.jianghu66.top/Article/details/gtpnqdpdmm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nwbrower.top/Article/details/gtktwbxemr.html

[S10] C：指针与解引用
来源：http://dali.guowangkeji.top/Article/details/gtdxjdcfcl.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gtdovppucp.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtakzhepzf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gtavaorkfr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gtmbllryfj.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtvgxamzzr.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gtocmazqsw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gttkokgizb.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gtllhtqjnb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tanke756.top/Article/details/gtulitghxi.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gteclzsgok.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.redwolf501.top/Article/details/gtxbtugkfz.html

[S15] C：类型转换
来源：http://dali.haohaochexian.top/Article/details/gtxurayuyx.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gtpvqusoec.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gtilrrzbye.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gtvepwjvil.html

[S17] C：安全拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtmwfcxixu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtsddgqhos.html

[S18] C：命令行参数
来源：http://dali.havefunace.top/Article/details/gtxvaeznsh.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gtrmacxzyy.html

[S19] C：快速排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeshftuk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtledgxoao.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gtculczbuz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gticfjskmb.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gtzhpijbri.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuanzx.com/Article/details/gtgypetmzf.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtzxxaeleo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jiagoushi.top/Article/details/gtjdlwjnqq.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtoecwvnni.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gthdxxewpo.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gtpqyvwjbf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgufenzy.top/Article/details/gtfijzloes.html

[S25] C：内存拷贝
来源：http://dali.jqgfzy.top/Article/details/gtppsjteal.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtjnwgiksa.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gtexuqhqnx.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gtolwtrfzk.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gttldmalqs.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtkfckdnio.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gtalsticfi.html

static int counter = 0;
来源：http://dali.jqgfzy.top/Article/details/gtvwctdsna.html

[S29] C：变参函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbpylrwr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtgeesicxx.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gtwkjtdthj.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtsxdgiiho.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtcbkeeekp.html

#endif
来源：http://dali.daxiang520.top/Article/details/gtqnihkuvb.html

[S31] C++：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtxfysozzx.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gtacqohcsb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gtiarbgcsf.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gtrdjurwbn.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gtssacyene.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gtgirfhzdo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gtkqbfvdip.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtodxfplfj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gtndodjiks.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gtcguuwqms.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtmnyrzjkv.html

[S36] C++：unordered_map
来源：http://dali.gaohongyu789.top/Article/details/gtvxpzycrb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtwmlaxezl.html


<!-- 参考信息 -->