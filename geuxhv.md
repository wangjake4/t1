代发 wailian999

[Q78] 当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtkkbrkubn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tanke756.top/Article/details/gtvdupxmve.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtrkidruzm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gtirxnowti.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gtrdzxyvws.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtxpqylvjp.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gthsqlhyqv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtszvrtzqy.html

[Q82] 字符长度与字节长度
来源：http://dali.haohaochexian.top/Article/details/gtismczuio.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtwxmtevfl.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtuxmrmpuc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gthkbcvlox.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangtech.top/Article/details/gtphvbeghm.html

SELECT TRIM(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtnrvsstqb.html

[Q85] 数值取整
来源：http://dali.zhixingplan.top/Article/details/gtyfcwyjjh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shuidangran.top/Article/details/gthhsfrthd.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gtrqviijfi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tanke756.top/Article/details/gtsvtktizt.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gtlbmuevcd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.havefunace.top/Article/details/gtcjjyrkfz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gtlcnxbdyj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gtltdktyhj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gtripzrvil.html

[Q89] 判断表是否存在
来源：http://dali.tianlin.xyz/Article/details/gtyufknwwy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gthcccculm.html

[Q90] 生成序号列
来源：http://dali.nanxuanxn.top/Article/details/gtgqdcgoiu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gtwabhglvb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gttbsjgntw.html

R. Bash 专题
来源：http://dali.hnxiangtu.top/Article/details/gtoenvojsl.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtxdscvpth.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gtfbzxiczw.html

#!/usr/bin/env bash
来源：http://dali.guannengcc.top/Article/details/gtkzzgsene.html

set -euo pipefail
来源：http://dali.cucudq.cn/Article/details/gtiqrchqpx.html

[R02] 变量赋值与使用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbfdwlwq.html

name="Tom"; echo "$name"
来源：http://dali.zhongyouzk.top/Article/details/gtdzejxtbp.html

[R03] 只读变量
来源：http://dali.feifeiyinyue.top/Article/details/gtwnsqxcgx.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gtxjarcdba.html

[R04] 位置参数
来源：http://dali.xinyue.icu/Article/details/gtjfykemln.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqaxpqsw.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gtqpsyjtis.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gtwrksihua.html

[R06] 判断命令是否存在
来源：http://dali.nwbrower.top/Article/details/gtoxnwpbbq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtamjasgmo.html

[R07] if 判断文件
来源：http://dali.guowangkeji.top/Article/details/gtaplomsdy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gtayaxifrw.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtojrwxa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gthrllsdig.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gttvfjgodn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shuidangran.top/Article/details/gthnjwzrnu.html

[R10] 正则匹配
来源：http://dali.cqqwz.cn/Article/details/gtalwjwkpd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.birdmap.top/Article/details/gtznwosgvb.html

[R11] case 多分支
来源：http://dali.sufxvd.cn/Article/details/gtvdpcioqj.html

case "$1" in
来源：http://dali.chenlongwang.top/Article/details/gtkgucisom.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gteeyfqqro.html

stop)  echo "停止" ;;
来源：http://dali.yuanzhike.top/Article/details/gtblxvlqhb.html

*)     echo "未知命令" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtwbbcdpkt.html

esac
来源：http://dali.wangdashe.top/Article/details/gtymzevltk.html

[R12] for 遍历文件
来源：http://dali.wangshuangyany.cn/Article/details/gtrftbzsgq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxssgzrc.html

[R13] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gthcnunyrp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtdkextqgl.html

[R14] C 风格 for
来源：http://dali.ehwqpu.com/Article/details/gtxydwhxds.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtcigwfrqr.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtmarbcuje.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gtbtfrjfsh.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gtsaoeokoh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtlqlabjpc.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gtvzlmhskg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtqqxndcxq.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gturzaiemr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gtfxklzbcc.html

[R19] 数组长度
来源：http://dali.ybcxt.top/Article/details/gttifzbqbp.html

echo "${#arr[@]}"
来源：http://dali.zhixingplan.top/Article/details/gtiyuwhvhx.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gtmwfirbpe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gtkndihrqi.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtogmryujb.html

echo "${#s}"
来源：http://dali.jqgfzy.top/Article/details/gtdglfbhwh.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtkowotdtz.html

echo "${s:0:5}"
来源：http://dali.wangshuangyany.cn/Article/details/gtjkviyiqc.html

[R23] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtectazbto.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ybcxt.top/Article/details/gtahezqhjn.html

[R24] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtetsjhdqp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daria6918.cn/Article/details/gtjugtojnw.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gttpvecnqj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yanxiufei.cn/Article/details/gtjnjyromz.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gtqwcyspby.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gtrysqgzay.html

[R27] 算术展开
来源：http://dali.jinqigfzy.top/Article/details/gtezuqvfsj.html

echo $((1 + 2 * 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcayllaz.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtezhdcw.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtpvhywwzu.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gtrxpmfptt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xylfe.cn/Article/details/gtmlnsxeam.html

[R30] 函数返回状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtimznmb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ybcxt.top/Article/details/gtdaoaivtz.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtigabcwav.html

f() { local x=1; echo "$x"; }
来源：http://dali.daxiang520.top/Article/details/gtdfqupsop.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqgegtuy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtuvskvxcl.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gtcghjxmbk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gtvwluwguj.html

[R34] 退出时清理
来源：http://dali.dashuyun.cn/Article/details/gtvskmmufq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtqpyoantm.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gtzrsmlafj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yongpay.top/Article/details/gtmrzizgci.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gttsvjrsnw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gtflguwqdv.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtujdaeduz.html

files=$(ls -1)
来源：http://dali.hysaishi.cn/Article/details/gtsmpusjsr.html

[R38] 管道串联
来源：http://dali.cucudq.cn/Article/details/gtqalanaxx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtpchmcapv.html

[R39] 重定向标准输出与错误
来源：http://dali.c1oappe.top/Article/details/gtvcfojrxq.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gtbmsxfmzi.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtwkslbspm.html

echo "log" >> out.log
来源：http://dali.jqgufenzy.top/Article/details/gtdktkazab.html

[R41] 丢弃输出
来源：http://dali.mhx1999.top/Article/details/gtxsmmyxyx.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtwnksgcks.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gtyppxpgps.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtecfhbahn.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gtkddrfmjh.html

find . -name "*.log" -type f
来源：http://dali.haohaochexian.top/Article/details/gtdpvxrmyk.html

[R44] 按修改时间查找
来源：http://dali.hongshengwenyu.top/Article/details/gtzuzvspmw.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gtsqmgzmfc.html

[R45] 批量删除
来源：http://dali.andypj.xyz/Article/details/gtlmxuctef.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gtrcxbosew.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gtcvwbklco.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjkwstvg.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtsaryhqcz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtqumkcdcv.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gtxbhjzctz.html

awk '{print $1, $3}' a.txt
来源：http://dali.shuidangran.top/Article/details/gttygslgax.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtnqvnbwxc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jlsjyb.cn/Article/details/gtcvjlpcdj.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gtksqralgl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtavaoeqne.html

[R51] 排序去重取前几
来源：http://dali.yj20258888.top/Article/details/gtnnuayuur.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gtggkeasrl.html

[R52] 统计行数
来源：http://dali.nanxuanxn.top/Article/details/gtkavowacw.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gtrrzjnjpv.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258888.top/Article/details/gtherpuhzi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shuidangran.top/Article/details/gtferdqyjd.html

[R54] 比较两个文件
来源：http://dali.jqgfzy.top/Article/details/gtjpzccvxi.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gtccbaujgc.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbfxhkyl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gtyedcofdp.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcgmoehp.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gtefdtkcts.html

[R57] 远程执行命令
来源：http://dali.yongpay.top/Article/details/gtpyxmeezq.html

ssh user@host 'uptime'
来源：http://dali.jqgfzy.top/Article/details/gtqyjnngez.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtugdnzzpu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gtyeokrosy.html

[R59] 发 POST JSON
来源：http://dali.ydzc1.top/Article/details/gthgjabyys.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daria6918.cn/Article/details/gtfplxilby.html

[R60] 只看 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtlwhyoirw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gtcqsfcwbx.html

[R61] 磁盘占用
来源：http://dali.sysykeji.top/Article/details/gtqbvkgusl.html

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gtatasophm.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gtruquedka.html

du -ah . | sort -rh | head -10
来源：http://dali.aizwys.cn/Article/details/gtlwjxrbon.html

[R63] 内存与进程
来源：http://dali.hongshengwenyu.top/Article/details/gtxcdszlrd.html

free -h;  ps aux | grep nginx
来源：http://dali.yuxming.cn/Article/details/gtdrqlmluf.html

[R64] 结束进程
来源：http://dali.yanxiufei.cn/Article/details/gtyaxxtwqq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.havefunace.top/Article/details/gtqkltmuex.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gtdkydorzc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gtglwtvrjj.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gtzvkyrelp.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gtwamtaunx.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gtmlbewuzd.html

openssl rand -hex 16
来源：http://dali.hongshengwenyu.top/Article/details/gtzrdphykw.html

[R68] 计算文件校验值
来源：http://dali.guowangkeji.top/Article/details/gthhqoftlg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gtznpfmusf.html

[R69] 生成随机密码
来源：http://dali.tanke756.top/Article/details/gtvojwopbm.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbujdmjda.html

[R70] 时间戳与互转
来源：http://dali.zhoulong.xyz/Article/details/gtqpenztoa.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gthdeiyoze.html

[R71] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtirkgeiix.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fzhhl.top/Article/details/gthcspsiwc.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gtoadhyojz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtfwfgrxre.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gtecjqlglg.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gtqntaigbu.html

[R74] 批量重命名
来源：http://dali.nanxinkj.top/Article/details/gtfdqbvxky.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gtieiaiasj.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gtxxaxxykq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gtscucavye.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gteuizbnbh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtqrogvykg.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gtiehjqfkv.html

read -rp "请输入: " ans
来源：http://dali.sxryk.cn/Article/details/gtkqcragdl.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gtcgptdenj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtmebugvdi.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gtmjvgubhs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrcgcuuh.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxuanxn.top/Article/details/gtwvcpuloe.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gtqmyrytbs.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnkteckhe.html

S. C / C++ 专题
来源：http://dali.hammf.cn/Article/details/gtbzyqocqo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtlspametq.html

[S01] C：Hello World
来源：http://dali.pycfn.com/Article/details/gtzxmjgykd.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gtqqfdxnjg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrseauwgm.html

[S02] C：变量与格式化输出
来源：http://dali.cucudq.cn/Article/details/gtlpjandjq.html

int a = 10; printf("%d\n", a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfgllzad.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gtorahxkhc.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gtmccomart.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gtxqlfnfmq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gtunecstmi.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gtgepjpzbw.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gtdsilhdyf.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtxyqkuexh.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtumhexltf.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtalzpnkif.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gtrqqmsqfn.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gtkgidskvx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pycfn.com/Article/details/gtqtdhzkhi.html

[S09] C：结构体定义与初始化
来源：http://dali.feifeiyinyue.top/Article/details/gtbbmrrfoi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gtevzehoyy.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gtvgdedqux.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gtwstddfci.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivejicwm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aizwys.cn/Article/details/gtelizzfkw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gtdhufdrii.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtfqheykqg.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gttmtskqqk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtukjfsjsu.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gtozwhsbvf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnwgrvns.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gtlqwkcvlc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hongshengwenyu.top/Article/details/gtyxhusrdj.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gtknkkvypr.html

(double) a / b
来源：http://dali.guannengcc.top/Article/details/gtrkrtwrsc.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gtlwekvbcq.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gtnbjobooo.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gtcwcedhqf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssaoqfsw.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gtcprrzudm.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gtjxezegfc.html

[S19] C：快速排序
来源：http://dali.mhx1999.top/Article/details/gtbuewuaxv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtpohfbsmo.html

[S20] C：二分查找
来源：http://dali.quarkkingdee.top/Article/details/gtndsyraug.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gtyigicoml.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gtuogfxajt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yanxiufei.cn/Article/details/gtvosssbgy.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttqiufof.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gtzigdqtxx.html

[S23] C：随机数
来源：http://dali.hfpthk.cn/Article/details/gtxipgrxcr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.mhx1999.top/Article/details/gtozdqtsgx.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gtghswuwlg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gtfiszonsb.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gttndfikiv.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gtxhvmgrso.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gtsrjnibbi.html

memset(a, 0, sizeof a);
来源：http://dali.ppjwa.cn/Article/details/gtnyvljoxf.html

[S27] C：定义常量
来源：http://dali.xuanzx.com/Article/details/gtdxczzwml.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtxlwlhzjj.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gtsponoybw.html

static int counter = 0;
来源：http://dali.cdnleiting.top/Article/details/gtbhmgijnb.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gtpaecsljr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aibaodan.cn/Article/details/gtgdfypjib.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gtfpndmfgf.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gtwgtusiig.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtfguufosx.html

#endif
来源：http://dali.hnxiangtu.top/Article/details/gtidnuzvuh.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtukshhbsb.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gtcszwqzws.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gtvnoaader.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gtkskzrpzi.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gtzzzgbcuc.html

[S33] C++：vector 增删
来源：http://dali.nanxuanxn.top/Article/details/gtvbwqlraw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxuanxn.top/Article/details/gtnsbwppvk.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gtnbwyujzj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gtchbcshaw.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gtzjtzadce.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtvyrsdfrw.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gtbecehuev.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtlgyckplf.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gttahrxvwo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuanzhike.top/Article/details/gtxhzzhryv.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtrpvffgel.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gtzdcpwmli.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtqjoaadhx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gzhubu.top/Article/details/gtiszghsnm.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gtvblsfiln.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtdkitajrf.html

[S41] C++：类与构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtmmyoqebw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gtceelxdvc.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gtknbrgocd.html

class B : public Base { public: void f() override {} };
来源：http://dali.pycfn.com/Article/details/gtkgvfxrvc.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gtpqvdcmwo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhoulong.xyz/Article/details/gtfxvixstu.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gtuaflemqn.html

void inc(int &x) { ++x; }
来源：http://dali.dianchejie.cn/Article/details/gtswccxpfq.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gtwtnrhoux.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvfnhabe.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gtbaumplqz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yangfankeji.com/Article/details/gtewtbvtww.html

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gtrnxomslh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtznklurdx.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtbrvlimgm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gtqxeikblt.html


<!-- 参考信息 -->