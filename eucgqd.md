代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gttvysnmja.html

[Q73] 查看表状态
来源：http://dali.bjfxy.top/Article/details/gthiqjhiyz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gtzwsghlnl.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gtrfrctgnj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sufxvd.cn/Article/details/gtnvsxuahl.html

[Q75] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtpptuuuek.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtxoennfue.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jlsjyb.cn/Article/details/gtvqlwpsyh.html

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gtatypvcao.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jlsjyb.cn/Article/details/gtrcjfurwt.html

[Q77] 时间加减
来源：http://dali.sweek.top/Article/details/gtfrdsmiso.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gtovjxdvqu.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gttqibrbrr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gtgvtjhlgz.html

[Q79] 字符串拼接
来源：http://dali.xinyue.icu/Article/details/gtvngdvwab.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenlongwang.top/Article/details/gtnikoqbmx.html

[Q80] 字符串截取
来源：http://dali.shangyingyoupin.top/Article/details/gtxotpqetq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gteyzmhldo.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gthywhufee.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtypzorrwv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhiwuduotai.top/Article/details/gtbtdyekok.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtjfotayec.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtopdaqzfy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtjsizhmbs.html

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gtvfubhogt.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaepvwamp.html

[Q85] 数值取整
来源：http://dali.jlsjyb.cn/Article/details/gtwkiumkse.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gtoeibyhwd.html

[Q86] 读取 JSON 字段
来源：http://dali.cdnleiting.top/Article/details/gtazoblvpl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhiwuduotai.top/Article/details/gtxoxypuck.html

[Q87] JSON 字段做条件
来源：http://dali.xziqi.cn/Article/details/gtczvcuqlr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangshuangyany.cn/Article/details/gtjsqhgtkb.html

[Q88] 行转列（条件聚合）
来源：http://dali.hfpthk.cn/Article/details/gtqfhmyjqe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gtddlahjmv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gtljvhvlpk.html

[Q89] 判断表是否存在
来源：http://dali.tianlin.xyz/Article/details/gtozfvtcgq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gtmpxlnchl.html

[Q90] 生成序号列
来源：http://dali.zhixingplan.top/Article/details/gtoozqodpe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gtuhxzidjx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtxdhiuafo.html

R. Bash 专题
来源：http://dali.ppjwa.cn/Article/details/gtqotrfjea.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtrceyriqy.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gtmqbwghuj.html

#!/usr/bin/env bash
来源：http://dali.guannengcc.top/Article/details/gtmpmpcyuy.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gtomkhyppo.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gtrazxqohb.html

name="Tom"; echo "$name"
来源：http://dali.yvedp.cn/Article/details/gtvcdbzuww.html

[R03] 只读变量
来源：http://dali.tianlin.xyz/Article/details/gttqtphqcd.html

readonly PI=3.14
来源：http://dali.havefunace.top/Article/details/gturzlktmi.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gtaxaapsdx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zycfv.cn/Article/details/gtpuegrhrd.html

[R05] 参数默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtqrnsxjep.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gttgoqpcta.html

[R06] 判断命令是否存在
来源：http://dali.sufxvd.cn/Article/details/gtpchjdlot.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtrzbwidis.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gtonjknqrd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gtfurzbgyx.html

[R08] 数值比较
来源：http://dali.zhongyouzk.top/Article/details/gtmfsgrbxl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gtgnxauctg.html

[R09] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtdkghssdr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gtabhgzblv.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpourkgod.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigufen.top/Article/details/gtmpabtuqx.html

[R11] case 多分支
来源：http://dali.hysaishi.cn/Article/details/gtfwphynfm.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gtjrpvbcle.html

start) echo "启动" ;;
来源：http://dali.yvedp.cn/Article/details/gttcmyirqr.html

stop)  echo "停止" ;;
来源：http://dali.dashuyun.cn/Article/details/gtmwcrqqcb.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmjooupw.html

esac
来源：http://dali.ivvv.top/Article/details/gtpseqaugm.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gtfvxpamgw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gtljbyarbm.html

[R13] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gtmfhtllfj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtyigtprhk.html

[R14] C 风格 for
来源：http://dali.cdnleiting.top/Article/details/gtdumthtll.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gthnivdhmd.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gtoxgclbms.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenjidiqi.icu/Article/details/gthbwhibvm.html

[R16] until 等待条件
来源：http://dali.gaohongyu789.top/Article/details/gtgvtknelx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtaqzwgbyz.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gtrgwtecwb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gtiahymtmb.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtpjnoxuov.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gtrlgtsehl.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtrosazynq.html

echo "${#arr[@]}"
来源：http://dali.shuidangran.top/Article/details/gtaxavtzsp.html

[R20] 关联数组（字典）
来源：http://dali.xinyue.icu/Article/details/gtmryyegbk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nwbrower.top/Article/details/gtuugaswcu.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gtlfhztzjm.html

echo "${#s}"
来源：http://dali.mhx1999.top/Article/details/gthzqnkndx.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gturlxqkbk.html

echo "${s:0:5}"
来源：http://dali.aizwys.cn/Article/details/gtvzgjkyzm.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtvzclwiwj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqlexpyj.html

[R24] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gthjtzoono.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtpmktueoe.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gttvtudnkw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gtnxpwamvf.html

[R26] 命令替换
来源：http://dali.sufxvd.cn/Article/details/gtsuvxfvbl.html

now=$(date +%F); echo "$now"
来源：http://dali.chenjidiqi.icu/Article/details/gtppmakuux.html

[R27] 算术展开
来源：http://dali.jlsjyb.cn/Article/details/gtzmbhjnld.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gtseivzptt.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gtlugvwdku.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gtiqnmtziz.html

[R29] 定义函数
来源：http://dali.birdmap.top/Article/details/gtwntbeume.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ivvv.top/Article/details/gtvmaozrfp.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gtfumwvery.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnxiangtu.top/Article/details/gtjyiwhfbz.html

[R31] 局部变量
来源：http://dali.tianlin.xyz/Article/details/gtcowahytg.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtycqgaykm.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gtjpzxywin.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqjazphsn.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtmaksbrcs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gtopawxpmp.html

[R34] 退出时清理
来源：http://dali.tian-w.cn/Article/details/gtllxpkqtm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtedftzeto.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gtzgrbmqxa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gtoeipscpg.html

[R36] 并发执行多个任务
来源：http://dali.xylfe.cn/Article/details/gtylxxdshd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gtbvdovcuz.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gtnbueungq.html

files=$(ls -1)
来源：http://dali.svipenyu.cn/Article/details/gtxtlhguya.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gticciplhf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.andypj.xyz/Article/details/gthcvmwetn.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gtkocftaid.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtudfzxghq.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwjgcyeu.html

echo "log" >> out.log
来源：http://dali.nanxuanxn.top/Article/details/gtxpbrblll.html

[R41] 丢弃输出
来源：http://dali.tian-w.cn/Article/details/gtflphhvsa.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gtwadjtvql.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsuzemim.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtvgjqawbq.html

[R43] 按名字查找文件
来源：http://dali.xziqi.cn/Article/details/gtfrdncsac.html

find . -name "*.log" -type f
来源：http://dali.tanke756.top/Article/details/gtgnjlbutn.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gtnlniwsav.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gtudunkvnr.html

[R45] 批量删除
来源：http://dali.ppjwa.cn/Article/details/gtkadcrtkb.html

find . -name "*.tmp" -delete
来源：http://dali.zhiwuduotai.top/Article/details/gtrwdibdga.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gtfdvariww.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gtyvgmjffl.html

[R47] sed 单行替换
来源：http://dali.sxryk.cn/Article/details/gtqugsksso.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtwoyotiaz.html

[R48] awk 取指定列
来源：http://dali.jiagoushi.top/Article/details/gtnjbseefl.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtyudgxfpp.html

[R49] awk 带条件
来源：http://dali.hnxiangtu.top/Article/details/gtrgfouiwq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guowangkeji.top/Article/details/gtpcbmifib.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gtfdabxnxi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtdzhpjxzf.html

[R51] 排序去重取前几
来源：http://dali.bjfxy.top/Article/details/gttkskwqug.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gtjpwolzye.html

[R52] 统计行数
来源：http://dali.yj202588.top/Article/details/gtwiqbqvsq.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gtwgjpiolv.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gtbodzcbdd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gtgxtepuxp.html

[R54] 比较两个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjzahedl.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gtssrdoshl.html

[R55] 压缩与解压
来源：http://dali.zycfv.cn/Article/details/gtndturbql.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sysykeji.top/Article/details/gtuhiywbjo.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtlivunzse.html

scp file user@host:/path/
来源：http://dali.mhx1999.top/Article/details/gtieghpome.html

[R57] 远程执行命令
来源：http://dali.dashuyun.cn/Article/details/gtqdxuslub.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gthhnxyooc.html

[R58] 下载文件
来源：http://dali.shzxlz.cn/Article/details/gttfkblsgu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ydzc1.top/Article/details/gtjsyvvegm.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtzjdzfsgb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gtlembgdiq.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gttzwwwsyv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgbetazb.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuxwqeqj.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gtjkqdpdgh.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gtwamagbfl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhongyouzk.top/Article/details/gtylgqbplx.html

[R63] 内存与进程
来源：http://dali.jiagoushi.top/Article/details/gtiyeuvubc.html

free -h;  ps aux | grep nginx
来源：http://dali.ybcxt.top/Article/details/gtlqvlrzyg.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqqnmlgv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gtzghmjaql.html

[R65] 查看端口占用
来源：http://dali.ybcxt.top/Article/details/gtrtiapglh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gzhubu.top/Article/details/gtgvcbugyk.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gtowjhfyrj.html

crontab -e;  crontab -l
来源：http://dali.havefunace.top/Article/details/gtqlciepyk.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gtyknalxnw.html

openssl rand -hex 16
来源：http://dali.aizwys.cn/Article/details/gtpfogdbjz.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gtkvuxbhuc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdevapjc.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gtnauqhbmh.html

head -c 16 /dev/urandom | base64
来源：http://dali.cdnleiting.top/Article/details/gtledoavsc.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gtehkdssyk.html

date +%s;  date -d @1700000000
来源：http://dali.sysykeji.top/Article/details/gtnjthrspo.html

[R71] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtqzsugsma.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyiloidaz.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gtqkyixdmk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtfxqmfxau.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gtrutipicu.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gtbnefbhyh.html

[R74] 批量重命名
来源：http://dali.yj20258.top/Article/details/gtjyvunuwd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnxiangtu.top/Article/details/gtfgmxhcre.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyxebkbz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.quarkkingdee.top/Article/details/gtuagfbxji.html

[R76] 使用临时文件
来源：http://dali.vqdsnc.cn/Article/details/gtpbdbjhzc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtbvxfbxna.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gtgzextbwu.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gtoctwgxpd.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gtfkdhflyi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenjidiqi.icu/Article/details/gtgkzspbex.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gtwwicqkru.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gaohongyu789.top/Article/details/gthwekusyf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gtmjlkbuks.html

time ./run.sh
来源：http://dali.sxryk.cn/Article/details/gtmakfrrwx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxvrtagkd.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gtpgryyjbe.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtllxsvkia.html

[S01] C：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtabqbduel.html

#include <stdio.h>
来源：http://dali.jlsjyb.cn/Article/details/gttkawgasv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqhghmxae.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtkfyjmvis.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gtrkrnfvld.html

[S03] C：读入整数
来源：http://dali.zhongyouzk.top/Article/details/gtjzibxoze.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gtzfhszpbq.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmspjjnb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gtrxjevpto.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gtuxfsebfn.html

strlen(s)
来源：http://dali.kuanghao11.cn/Article/details/gtpxrybmlk.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gtnoavzumb.html

strcmp(a, b) == 0
来源：http://dali.iojbl.cn/Article/details/gtxvdlyyxv.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gtiunmtpkr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aibaodan.cn/Article/details/gtnrkmuizz.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gtqwfpisgh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jyoumei.cn/Article/details/gtjvxneike.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gttombfjdo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gttxaiftqc.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gtzhvalfax.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtxdronlcm.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtcuivnvuv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gtfypmfxpx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sufxvd.cn/Article/details/gtqrhlhugb.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtpudyxiyd.html

[S12] C：写文件
来源：http://dali.tian-w.cn/Article/details/gtfsfjdbsv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtcoftefjx.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gtvwukvgoy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gtabrdbnem.html

[S14] C：枚举
来源：http://dali.pycfn.com/Article/details/gttazackkp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gtjgyptbvz.html

[S15] C：类型转换
来源：http://dali.zhixingplan.top/Article/details/gtpqnavcte.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gtsodtmrov.html

[S16] C：位操作置位
来源：http://dali.snrcjt.cn/Article/details/gtryynbaic.html

x |= (1 << 3);
来源：http://dali.jinqigfzy.top/Article/details/gtbukykdnd.html

[S17] C：安全拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtodsxwjew.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gtgzbnkion.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtosnlvfqm.html

int main(int argc, char **argv)
来源：http://dali.cqqwz.cn/Article/details/gtvpigukzz.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gtgtcamddu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gtviduzunm.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gtkdjlptal.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtbnwzzwjm.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gtopriylum.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gtlwvonjfc.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gtoisszwym.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jianghu66.top/Article/details/gtcewfllxf.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gtatxibtib.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tianlin.xyz/Article/details/gtvfowxdzn.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gtpqqmwbfu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gtnjwvutnl.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gtuyxaynln.html

memcpy(dst, src, n);
来源：http://dali.zhengqikj.top/Article/details/gtgkwuwqzm.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrymqgbki.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gtvazglpcu.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gtcbzpadxj.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtjvcfbybd.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gtmerwcgtx.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gthizpgqlw.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gtakafinau.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gtpfcszagz.html

[S30] C：头文件保护
来源：http://dali.aibaodan.cn/Article/details/gtsziposdo.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gtpiiybrts.html

#define X_H
来源：http://dali.svipenyu.cn/Article/details/gtykfdzvhf.html

#endif
来源：http://dali.daria6918.cn/Article/details/gtgzlkklhx.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtjzujnliy.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gtcjnpychw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.birdmap.top/Article/details/gtbprjhlco.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gtufjfggqn.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gtiwfdljyx.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gtyblolrau.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gtdnuxahsg.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtheoglafx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gtrgnlnqal.html

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gthbaabgdz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtcidzhxjw.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gtzoukckip.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtssdblrqi.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtluibosfq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gtqvnwrqwr.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gthfglhfnl.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gtqmrptjvj.html

[S39] C++：自定义比较器排序
来源：http://dali.fzhhl.top/Article/details/gtglrhmpup.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.haohaochexian.top/Article/details/gtbtuetahd.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gtbvjqehzw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sweek.top/Article/details/gttlmxbegp.html

[S41] C++：类与构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gthaxuebsu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtcixbiuoo.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gtedzfpwye.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gtzmkvgmwi.html


<!-- 参考信息 -->