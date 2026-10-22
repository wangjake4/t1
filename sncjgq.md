代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gtneyqjavr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gtepjcxyxm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtxefovokg.html

[Q74] 强制使用索引
来源：http://dali.jianghu66.top/Article/details/gtpmgwzodq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gtomnxeoqv.html

[Q75] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtlrmlkmeh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yonumen.top/Article/details/gthfgqsfoo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.mhx1999.top/Article/details/gtnrrhstkh.html

[Q76] 按天统计
来源：http://dali.pycfn.com/Article/details/gtuunrhlrf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gzhubu.top/Article/details/gtwnwehdkn.html

[Q77] 时间加减
来源：http://dali.nwbrower.top/Article/details/gtlluhadkg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuanzx.com/Article/details/gtkauwgjap.html

[Q78] 当前时间
来源：http://dali.sysykeji.top/Article/details/gtlyfdlmpq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cucudq.cn/Article/details/gttuduqlju.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gtbqdrqjho.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gtfundogxg.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gtyvlspmrt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtszctqnuy.html

[Q81] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtgvtxwmsw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gtwykbcqfl.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gttxngkynp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtrkxgjjmf.html

[Q83] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gtvhcvbrec.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtbiewxcyu.html

[Q84] 去除首尾空格
来源：http://dali.jqgfzy.top/Article/details/gtplxidyff.html

SELECT TRIM(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtpomyeyno.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gtvhocvoky.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aibaodan.cn/Article/details/gtcqqymvow.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gteyfqhhbb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.iojbl.cn/Article/details/gtpgbxosxe.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkduvwoh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhengqikj.top/Article/details/gtauypqvyc.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuxming.cn/Article/details/gtaaespgtv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gtzotjgncp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtlozrpjcy.html

[Q89] 判断表是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtcipybfon.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtrrgvekpg.html

[Q90] 生成序号列
来源：http://dali.aizwys.cn/Article/details/gtwcbtncou.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gtanhfhlhe.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtkihgukgu.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtbhhvtpqc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxjmkngc.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gtbqfkyaot.html

#!/usr/bin/env bash
来源：http://dali.ybcxt.top/Article/details/gtkitphsmw.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gtpumpcoev.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gtzzdlfsdn.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gtpzyllsud.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gtkzvjwlur.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gtarpimffi.html

[R04] 位置参数
来源：http://dali.guowangkeji.top/Article/details/gtnqjtbzec.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.quarkkingdee.top/Article/details/gtafgwgcdr.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gtapoeqxju.html

name="${1:-default}"
来源：http://dali.hongshengwenyu.top/Article/details/gtutveipwg.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gtepyaqabi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtoajeaqpj.html

[R07] if 判断文件
来源：http://dali.hysaishi.cn/Article/details/gttwvvcikq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtzetzlvmv.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gtkpyyokwy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtobbgwcdm.html

[R09] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtojvprczg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigufen.top/Article/details/gtmhqnwuhf.html

[R10] 正则匹配
来源：http://dali.guannengcc.top/Article/details/gtzdykwrkb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yonumen.top/Article/details/gteuyydjgj.html

[R11] case 多分支
来源：http://dali.jinqigfzy.top/Article/details/gtmrdtarzc.html

case "$1" in
来源：http://dali.guowangkeji.top/Article/details/gtmlrkfsvi.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gtivvanynk.html

stop)  echo "停止" ;;
来源：http://dali.yuanzhike.top/Article/details/gtjhmpuosc.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtlldcswei.html

esac
来源：http://dali.ydzc1.top/Article/details/gtbplmzhnz.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gttsthbsqt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hammf.cn/Article/details/gtyakqnwmm.html

[R13] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gteguhikom.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gthlyfdyll.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gtvtgnqdnm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtkiwowjkt.html

[R15] while 逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtyixxkpdt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gtdzlxeeiu.html

[R16] until 等待条件
来源：http://dali.svipenyu.cn/Article/details/gtzuqqvylu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gtfriuqivv.html

[R17] 数组定义与取值
来源：http://dali.yj20258.top/Article/details/gtoskhurgp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tian-w.cn/Article/details/gtluxpckzl.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gtalurqgfh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsosxoid.html

[R19] 数组长度
来源：http://dali.wangdashe.top/Article/details/gtleyggcka.html

echo "${#arr[@]}"
来源：http://dali.9152youxi.cn/Article/details/gtbopgdcwe.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gtclrieejb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gtaswdhvcw.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gthwdktthj.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gtdmpmnctc.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevopdcdl.html

echo "${s:0:5}"
来源：http://dali.quarkkingdee.top/Article/details/gtathehupa.html

[R23] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gtbluemfor.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xziqi.cn/Article/details/gtknkiwfbo.html

[R24] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtqakuinwd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gteovdzpsd.html

[R25] 去后缀 / 去前缀
来源：http://dali.fzhhl.top/Article/details/gttfnupvtt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yueranfly.top/Article/details/gtcotohecc.html

[R26] 命令替换
来源：http://dali.jianghu66.top/Article/details/gtgppelivz.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258888.top/Article/details/gtwmxjbtit.html

[R27] 算术展开
来源：http://dali.ppjwa.cn/Article/details/gtxhneonhb.html

echo $((1 + 2 * 3))
来源：http://dali.316326.xyz/Article/details/gtfhouxqlw.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gtpdchxapf.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxinkj.top/Article/details/gtkthgqzje.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcluwxcy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gtukioisne.html

[R30] 函数返回状态码
来源：http://dali.dianchejie.cn/Article/details/gtaifcymli.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gtcejdfyqq.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gtjofopuce.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodyqendv.html

[R32] 参数个数校验
来源：http://dali.sxryk.cn/Article/details/gtqivobrgp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gteyvxgfnp.html

[R33] 捕获错误并提示行号
来源：http://dali.yuanzhike.top/Article/details/gtpqvzhubr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhoulong.xyz/Article/details/gtouceswfc.html

[R34] 退出时清理
来源：http://dali.kuanghao11.cn/Article/details/gtfgjmxxsj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gtavbtjzly.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gtacfqcjfy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gtydqclcyi.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrsyzdts.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtzpygzbou.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gtbjvjogot.html

files=$(ls -1)
来源：http://dali.yonumen.top/Article/details/gtdmvsjxbz.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gtgffmshzt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ehwqpu.com/Article/details/gttijzbluw.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gtzwactaau.html

cmd > out.log 2>&1
来源：http://dali.xziqi.cn/Article/details/gtbuqpxyew.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gtgjtewpwi.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gtirmloosg.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gtuphnwpie.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gtleerpvnu.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gtltxweyxv.html

wc -l < a.txt
来源：http://dali.jiagoushi.top/Article/details/gtxqfgppsk.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gtinpsbgzg.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gtqyvtdure.html

[R44] 按修改时间查找
来源：http://dali.yj202588.top/Article/details/gtummqinsa.html

find . -mtime -7 -type f
来源：http://dali.zhengqikj.top/Article/details/gtnxokjeer.html

[R45] 批量删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gtislxqffp.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gtimmpooxb.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gtjhnxdqzu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gtnfxjqyac.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gtrawkgrek.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtnvksndam.html

[R48] awk 取指定列
来源：http://dali.0kj1m.cn/Article/details/gtwucjwncx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtqcxhfxoi.html

[R49] awk 带条件
来源：http://dali.xylfe.cn/Article/details/gthbeygzxy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gtjbnocftl.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gtdugedubb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtxcswpbep.html

[R51] 排序去重取前几
来源：http://dali.feifeiyinyue.top/Article/details/gtrrcfuucf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gtssfsbicd.html

[R52] 统计行数
来源：http://dali.hammf.cn/Article/details/gtumpiicxd.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtrrngbhwy.html

[R53] 查看文件头与实时尾
来源：http://dali.daria6918.cn/Article/details/gtfjbamqir.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gtbipurfab.html

[R54] 比较两个文件
来源：http://dali.mhx1999.top/Article/details/gtomsdtaqf.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gtrftaztkz.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gthsbrntdh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.iojbl.cn/Article/details/gtxzfeoshr.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gtvzydgyyl.html

scp file user@host:/path/
来源：http://dali.gotoacloud.top/Article/details/gtgucfzhdg.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gtkenuzigl.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gtzonrsquj.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfulwtrvr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxinkj.top/Article/details/gtcvhldqfh.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtngocdpbm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gtzefnruff.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtsbhjrvcz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gtftaezhmn.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gtbpewfqzi.html

df -h;  du -sh *
来源：http://dali.tianlin.xyz/Article/details/gtcnxrayne.html

[R62] 找最占空间的文件
来源：http://dali.meibo888.top/Article/details/gtlpagorbk.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gtalgpxole.html

[R63] 内存与进程
来源：http://dali.feifeiyinyue.top/Article/details/gtkevretlz.html

free -h;  ps aux | grep nginx
来源：http://dali.ybcxt.top/Article/details/gtfurujdlr.html

[R64] 结束进程
来源：http://dali.guowangkeji.top/Article/details/gtwrdtbrsi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yanxiufei.cn/Article/details/gtcstiwuaf.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gtxdgqjqmv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.smart0.xyz/Article/details/gtryjixqpu.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gttnlroeth.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gtcuwgkxkt.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gtebnymxpd.html

openssl rand -hex 16
来源：http://dali.zhongyouzk.top/Article/details/gtvihuzgor.html

[R68] 计算文件校验值
来源：http://dali.zhixingplan.top/Article/details/gtcpxkawna.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkchfueph.html

[R69] 生成随机密码
来源：http://dali.cdnleiting.top/Article/details/gtxluapbuy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gtsyyyoccy.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gtuvnviktx.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gtvlfwiawb.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtxnphcqru.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gtnxhvulgk.html

[R72] 等待端口就绪
来源：http://dali.quarkkingdee.top/Article/details/gtnfknhmsn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtceshpxvk.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtiemhxice.html

split -l 1000 big.log part_
来源：http://dali.ydzc1.top/Article/details/gtmjemheol.html

[R74] 批量重命名
来源：http://dali.yonumen.top/Article/details/gtmlfnaerg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnqzz.top/Article/details/gtfltizbje.html

[R75] 导出环境变量
来源：http://dali.cqqwz.cn/Article/details/gtnvqoyshh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gtcgynhytr.html

[R76] 使用临时文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxvkfzbg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gtglvhdnlq.html

[R77] 读取用户输入
来源：http://dali.guannengcc.top/Article/details/gtyccaknnp.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gtnwpgrkmi.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gtdkqcpmdu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cucudq.cn/Article/details/gtqnragkzg.html

[R79] 解析命令行选项
来源：http://dali.vqdsnc.cn/Article/details/gttahmqzqr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gtzoplkvqw.html

[R80] 查看脚本执行耗时
来源：http://dali.sweek.top/Article/details/gtrpwhaozk.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gtcklovoxa.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzmjjykj.html

S. C / C++ 专题
来源：http://dali.smart0.xyz/Article/details/gtvivobosk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttidutogg.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtzdsjinlo.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gtqhhyblkz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpdqboefs.html

[S02] C：变量与格式化输出
来源：http://dali.jyoumei.cn/Article/details/gtokwwoamm.html

int a = 10; printf("%d\n", a);
来源：http://dali.xylfe.cn/Article/details/gtyjjuywhx.html

[S03] C：读入整数
来源：http://dali.gogol.net.cn/Article/details/gtjimzmmpw.html

int x; scanf("%d", &x);
来源：http://dali.quarkkingdee.top/Article/details/gtreyxxnnu.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gthsyygajp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtibdrzwtm.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gtxxobaats.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gtwzcudkhq.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gtuabfmmts.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gthnerfumy.html

[S07] C：数组遍历求和
来源：http://dali.dashuyun.cn/Article/details/gtxhycjxsm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cdnleiting.top/Article/details/gtnvmvsxsf.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gtrvjmfwvu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgufenzy.top/Article/details/gtzquenfha.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gtffnufenn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shuidangran.top/Article/details/gtiaeugycl.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gtiaqikbmd.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gtrpwvljsr.html

[S11] C：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtzndtxatb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gtaklfhpjs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gtjrjxahqv.html

fclose(f);
来源：http://dali.birdmap.top/Article/details/gtpuvsqplj.html

[S12] C：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtfslxlosx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtjdntsfzh.html

[S13] C：宏定义
来源：http://dali.xylfe.cn/Article/details/gtjeaczsem.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gtwvvcmlxk.html

[S14] C：枚举
来源：http://dali.bjfxy.top/Article/details/gtyliomlpp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gotoacloud.top/Article/details/gtqrsyrfwe.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtwphdvyma.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gtqublwdlx.html

[S16] C：位操作置位
来源：http://dali.nanxuanxn.top/Article/details/gtgkkefueu.html

x |= (1 << 3);
来源：http://dali.yonumen.top/Article/details/gtmeeobqwd.html

[S17] C：安全拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtygwsqmqr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dianchejie.cn/Article/details/gtqphiftey.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtghaoqlht.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzagddoph.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gtkwjmdftp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtwiwpwkli.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gtpzbohhgj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gteobzzomt.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gtduefphll.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangdashe.top/Article/details/gtlbebkvva.html

[S22] C：字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyndwsej.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gtsmlsofbc.html

[S23] C：随机数
来源：http://dali.sweek.top/Article/details/gtotkzdqri.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtkhxvcxyw.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gtkkhkjplh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gtjmgmccpm.html

[S25] C：内存拷贝
来源：http://dali.zhixingplan.top/Article/details/gthqtsrkrt.html

memcpy(dst, src, n);
来源：http://dali.yueranfly.top/Article/details/gtjirwoydz.html

[S26] C：内存清零
来源：http://dali.zhiwuduotai.top/Article/details/gtgczypwqa.html

memset(a, 0, sizeof a);
来源：http://dali.cashguo.top/Article/details/gtsrkvqrhc.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gtpfvaoubj.html

const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gthenpnskt.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gtqxfstcvg.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gtnzbdgbxl.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gtdthcypyr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gtqyaetotw.html

[S30] C：头文件保护
来源：http://dali.daria6918.cn/Article/details/gtkjxckqph.html

#ifndef X_H
来源：http://dali.guowangkeji.top/Article/details/gtnwubhopb.html

#define X_H
来源：http://dali.jlsjyb.cn/Article/details/gtfdymgbpm.html

#endif
来源：http://dali.sweek.top/Article/details/gtllmkjaas.html

[S31] C++：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtxkjqbqil.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtivomxxig.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gtdahtasoc.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gttuslzlwv.html

std::string s = "hi";  s += "!";
来源：http://dali.sweek.top/Article/details/gtaalocrpu.html

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gtzihngizw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gtkqxqwlhe.html

[S34] C++：遍历 vector
来源：http://dali.cheryme.top/Article/details/gtfgmjrngn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pycfn.com/Article/details/gthrojqtzh.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gtjbyauemi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtqxuqbnvr.html

[S36] C++：unordered_map
来源：http://dali.yj20258.top/Article/details/gtnftbknti.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtbcbxibbw.html

[S37] C++：set
来源：http://dali.redwolf501.top/Article/details/gtaiuijkrp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtbdatmhfj.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gtsawvnxpr.html

std::sort(v.begin(), v.end());
来源：http://dali.ivvv.top/Article/details/gtionxumxm.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gtnampqnqs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gtnptimlsm.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gtkrasjhzt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gtgixdasga.html

[S41] C++：类与构造函数
来源：http://dali.yuanzhike.top/Article/details/gtvttaqjba.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gtsupcqkke.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gtmgfnkccg.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gtojhovijf.html


<!-- 参考信息 -->