代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtmthnxfkp.html

[Q73] 查看表状态
来源：http://dali.zhiwuduotai.top/Article/details/gtzzpcjoaa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtidlkbmdg.html

[Q74] 强制使用索引
来源：http://dali.fzhhl.top/Article/details/gtofhblhtt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gtterongzb.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtebrliond.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtgpncltwk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuetiantiany.cn/Article/details/gtjanckhyb.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gtvryvrjey.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gtcgjpluxc.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gtspxlache.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tian-w.cn/Article/details/gtiftllmsb.html

[Q78] 当前时间
来源：http://dali.xylfe.cn/Article/details/gtmmqhqofp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gtmifrulry.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtodaatlts.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gtxxtbevqc.html

[Q80] 字符串截取
来源：http://dali.chenjidiqi.icu/Article/details/gtueolapxw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gtyslwezno.html

[Q81] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gtmobtefxn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtefglupwt.html

[Q82] 字符长度与字节长度
来源：http://dali.gogol.net.cn/Article/details/gtjfnfjagp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gttmxsqpfi.html

[Q83] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtxhgirvsz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtqnkqfnpr.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtqllkdtmu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtpwsnmmyd.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gtcccdkyde.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gtyiefcmrf.html

[Q86] 读取 JSON 字段
来源：http://dali.shzxlz.cn/Article/details/gtzjlkfsli.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjckvcft.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrffpqqg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gtowkfftwn.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gtljxrkglg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtvhjzivga.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gteozrbiuh.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gtzgwlqafh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtbmvubtvr.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gtigbcaeyu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gtkufjlqtj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvnaqkxl.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gtimblsywv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtiklrfanx.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gtqcmcewge.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gttrncynhs.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gtvdzumfrw.html

[R02] 变量赋值与使用
来源：http://dali.havefunace.top/Article/details/gtbdunyafs.html

name="Tom"; echo "$name"
来源：http://dali.meibo888.top/Article/details/gtknwmsxin.html

[R03] 只读变量
来源：http://dali.haohaochexian.top/Article/details/gtelirujww.html

readonly PI=3.14
来源：http://dali.jinqigfzy.top/Article/details/gtzljhnhpt.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gtqqpadjga.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.smart0.xyz/Article/details/gtbyimqgnm.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtcaiwglam.html

name="${1:-default}"
来源：http://dali.pycfn.com/Article/details/gtjygccufz.html

[R06] 判断命令是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtypzkrjmj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtrjgntjvx.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gtcpcdbtvo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzcdhjuu.html

[R08] 数值比较
来源：http://dali.hammf.cn/Article/details/gtpzquzapx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gtklxvofor.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gtvdzyyeet.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtlnzriern.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtrcbivzkh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aibaodan.cn/Article/details/gtpxvgnwfz.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gtquuantvw.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gtswoggsck.html

start) echo "启动" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtostqxkhj.html

stop)  echo "停止" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtuyblbzzy.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gtdfprkxes.html

esac
来源：http://dali.zdqjudy.top/Article/details/gtdcxlqoeb.html

[R12] for 遍历文件
来源：http://dali.vqdsnc.cn/Article/details/gtkrsbgrbd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtzafsrmip.html

[R13] for 计数循环
来源：http://dali.sweek.top/Article/details/gtucbwuueg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtjltcaiab.html

[R14] C 风格 for
来源：http://dali.hywenlv.cn/Article/details/gtajzpyflo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtlbctfzxa.html

[R15] while 逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtyimeamlm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yvedp.cn/Article/details/gtxlscukkd.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gtrluemwyf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtqnyxhgjx.html

[R17] 数组定义与取值
来源：http://dali.hnqzz.top/Article/details/gtgkkuuyyb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtwfwspurx.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gtlaaqokdd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.snrcjt.cn/Article/details/gtwsrmoqyq.html

[R19] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gtobxabykq.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gtqtikrzyd.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gtnhkypqxl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gzhubu.top/Article/details/gtlhsfhand.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtffzzxwaa.html

echo "${#s}"
来源：http://dali.chenjidiqi.icu/Article/details/gtaocixemz.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtoridgclx.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gttsogyhcx.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtmoddxral.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhoulong.xyz/Article/details/gtjqkfqhmx.html

[R24] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtuuarrxls.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgfzy.top/Article/details/gtolmmmqms.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gthnupidhn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guannengcc.top/Article/details/gtevknitar.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gtkenecxun.html

now=$(date +%F); echo "$now"
来源：http://dali.fzhhl.top/Article/details/gtzhjgnazd.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gtwemkiqgt.html

echo $((1 + 2 * 3))
来源：http://dali.ppjwa.cn/Article/details/gtgpqhjgpt.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gtaskcwbrn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gtxaolidbw.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrlzjkcb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gtnprrmfhs.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gtkiulazkj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.feifeiyinyue.top/Article/details/gtdfklezla.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gtaauqfnrt.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtkmggsqmj.html

[R32] 参数个数校验
来源：http://dali.shangyingyoupin.top/Article/details/gttdsylxwx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtgwpmztgd.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlrmbcsu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cucudq.cn/Article/details/gtxysprfuo.html

[R34] 退出时清理
来源：http://dali.guowangkeji.top/Article/details/gtldghmgbn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtszehsifq.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtfiqppceb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gaohongyu789.top/Article/details/gtoffqyfpp.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gtehntskqd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuetiantiany.cn/Article/details/gtbcxexlzi.html

[R37] 把输出赋给变量
来源：http://dali.wangshuangyany.cn/Article/details/gtdjtndxrt.html

files=$(ls -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtypzzhthm.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gtwzhkbyha.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gttnerstwq.html

[R39] 重定向标准输出与错误
来源：http://dali.gogol.net.cn/Article/details/gtltwvlnop.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtnyujzcck.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gtagxwjelc.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gttpbhrtwt.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gtnhteypoh.html

cmd >/dev/null 2>&1
来源：http://dali.iojbl.cn/Article/details/gtnhqjcjxy.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gtfthqgnuz.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gtnfbiixtq.html

[R43] 按名字查找文件
来源：http://dali.zhengqikj.top/Article/details/gtrsarduip.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gtsconmgvg.html

[R44] 按修改时间查找
来源：http://dali.aibaodan.cn/Article/details/gtynlhdnsd.html

find . -mtime -7 -type f
来源：http://dali.hnxiangtu.top/Article/details/gtxvniryrc.html

[R45] 批量删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvzxraea.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gtlokgxdpr.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gtezfardus.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gtykqgxmvl.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtdapskmki.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtsdqmqrni.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gtcszobbms.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gtthjvpxyu.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gtovcqzbos.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfntajxw.html

[R50] awk 求和
来源：http://dali.fengsongda.top/Article/details/gtnkzhumxb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gthjojajzr.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gtreaojrqp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gtoxexovsg.html

[R52] 统计行数
来源：http://dali.haohaochexian.top/Article/details/gtamujyfyp.html

wc -l a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtykfsytyf.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gtkwmoqwij.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgufenzy.top/Article/details/gtybralrpj.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gtpjwmqwgh.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtecvdheyu.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gttdbtglpv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yueranfly.top/Article/details/gtrkplfyrd.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gtipssnjbz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gtpccjsoht.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfhcuxlj.html

ssh user@host 'uptime'
来源：http://dali.jianghu66.top/Article/details/gtnyhfwhri.html

[R58] 下载文件
来源：http://dali.mhx1999.top/Article/details/gteldanynk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gtbvdnkrym.html

[R59] 发 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtgjbdzpas.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tanke756.top/Article/details/gtyjhuhixy.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtyvjpitpb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cqqwz.cn/Article/details/gtltdeyfdb.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyckhtqgq.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtiwmllasy.html

[R62] 找最占空间的文件
来源：http://dali.shuidangran.top/Article/details/gtwgoefuof.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtvqflmjpn.html

[R63] 内存与进程
来源：http://dali.yonumen.top/Article/details/gtqhwwwekh.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gtitosnodc.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gtqoziabnn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gtigwmjhsc.html

[R65] 查看端口占用
来源：http://dali.yonumen.top/Article/details/gtpzknwjan.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cucudq.cn/Article/details/gtsmolpxqg.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gtcaidjlgj.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtzrsfirvc.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gtsrgtiixs.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gtkkfwqben.html

[R68] 计算文件校验值
来源：http://dali.svipenyu.cn/Article/details/gtrmurwtkt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gtblsivcxe.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtqzzbtmpt.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigufen.top/Article/details/gtvooycaoz.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gtgkueiqlp.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtjjkviyex.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtafizetdi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gtcyrcolkt.html

[R72] 等待端口就绪
来源：http://dali.wangshuangyany.cn/Article/details/gtemctlbxp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtdfdgjrrm.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gtwjesuwci.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gttqbkjmck.html

[R74] 批量重命名
来源：http://dali.daria6918.cn/Article/details/gtdpsyqvpj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yueranfly.top/Article/details/gtmaqbaouy.html

[R75] 导出环境变量
来源：http://dali.yongpay.top/Article/details/gtinofscgl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tian-w.cn/Article/details/gtryyavqie.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gtqfvdpyjd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtxolhwanq.html

[R77] 读取用户输入
来源：http://dali.redwolf501.top/Article/details/gtuaxgjilq.html

read -rp "请输入: " ans
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjhlzdeg.html

[R78] 交互式菜单
来源：http://dali.meibo888.top/Article/details/gtomksjnho.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gtwsgmxaou.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gtsfkmiqhq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.birdmap.top/Article/details/gttqpvduqz.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gteqwoxqtm.html

time ./run.sh
来源：http://dali.yj20258888.top/Article/details/gtiwciexqq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtwbgbzhsh.html

S. C / C++ 专题
来源：http://dali.haohaochexian.top/Article/details/gtqztjpnxz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnxdkqnyg.html

[S01] C：Hello World
来源：http://dali.cheryme.top/Article/details/gttnwdzosi.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gtxpkuaqrd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gtitpoomvy.html

[S02] C：变量与格式化输出
来源：http://dali.hammf.cn/Article/details/gtqvwjuvlu.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigfzy.top/Article/details/gteeddnewg.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gtlvjoedvz.html

int x; scanf("%d", &x);
来源：http://dali.sweek.top/Article/details/gtlbmaogln.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gtgpbxeibs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgfzy.top/Article/details/gtwxddhuit.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtpagsxfks.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gtpqzkslho.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtbuxffzcf.html

strcmp(a, b) == 0
来源：http://dali.kuanghao11.cn/Article/details/gtacijakvn.html

[S07] C：数组遍历求和
来源：http://dali.cdnleiting.top/Article/details/gtckhopijq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gtokiexhqe.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258.top/Article/details/gtelmemhpo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gtoqaadybv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabemqlgi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fengsongda.top/Article/details/gtunvokzpq.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtddvdduvk.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gtynvmcvyz.html

[S11] C：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtxljinjsy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gtztoxpiqj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuxming.cn/Article/details/gtuugkzexy.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtdddeqpxd.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtgrutmiwf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtgdnuonek.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gtsixyfdom.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gtqpdrolqb.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtfxfvazcw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aibaodan.cn/Article/details/gtvovvexoc.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtdbvygpth.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gtfmaydytu.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkljcyfx.html

x |= (1 << 3);
来源：http://dali.xylfe.cn/Article/details/gttqkgdzal.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtxopzjffw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gtaujyaeum.html

[S18] C：命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtloxgjcka.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gtncepgbov.html

[S19] C：快速排序
来源：http://dali.zhixingplan.top/Article/details/gtuuvkbyet.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtylzhcipi.html

[S20] C：二分查找
来源：http://dali.cheryme.top/Article/details/gthyyscjze.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtqcytshkr.html

[S21] C：字符类别判断
来源：http://dali.nwbrower.top/Article/details/gtwylmyprx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gttmtqycoq.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gthsuhhtxo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.birdmap.top/Article/details/gtwuhmonou.html

[S23] C：随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwgyvhts.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gtpamokeic.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gtyahixjtz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gtsijrxrga.html

[S25] C：内存拷贝
来源：http://dali.yonumen.top/Article/details/gthmcydrzc.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gtgjpznxfn.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gtkpxsfuvy.html

memset(a, 0, sizeof a);
来源：http://dali.shzxlz.cn/Article/details/gtdgbxyvck.html

[S27] C：定义常量
来源：http://dali.guowangkeji.top/Article/details/gtplrrmniw.html

const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtoaabwqdw.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gtcinatybc.html

static int counter = 0;
来源：http://dali.cashguo.top/Article/details/gtzfutuqad.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gtdimfsqpj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cashguo.top/Article/details/gtqaivvzgq.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gtqrzabzip.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gtlvommrbz.html

#define X_H
来源：http://dali.9152youxi.cn/Article/details/gtilezqjpm.html

#endif
来源：http://dali.yj202588.top/Article/details/gtlobfyfyy.html

[S31] C++：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtixnwtbte.html

#include <iostream>
来源：http://dali.hnxiangtu.top/Article/details/gthkptcmde.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yanxiufei.cn/Article/details/gtxfazhsgx.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gtmchlbsey.html

std::string s = "hi";  s += "!";
来源：http://dali.vqdsnc.cn/Article/details/gtwwefpsbe.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gtuzzpcwaa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ivvv.top/Article/details/gtuzdttnhj.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtizngtp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gtktzdxnec.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gtoyesvecp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtomjdmbgk.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gtkjicgaet.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtvzgbzgky.html

[S37] C++：set
来源：http://dali.hfpthk.cn/Article/details/gtseqtkqjt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gttkkfqtyz.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gtpkmwzyuz.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gtjpeaakme.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gtlbfejwns.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jyoumei.cn/Article/details/gtodfcqcmu.html

[S40] C++：查找元素
来源：http://dali.vqdsnc.cn/Article/details/gtzbqacluc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yonumen.top/Article/details/gtqlaskzzh.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gttboemtxx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gtkhktmafg.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gtlpketvmc.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gttpsbgkal.html


<!-- 参考信息 -->