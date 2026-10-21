代发 wailian999

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtccauawbr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfogmxdq.html

[Q79] 字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gtwljgnzwf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gtdfgyaefi.html

[Q80] 字符串截取
来源：http://dali.yj20258.top/Article/details/gtsleakiab.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gttddpdsld.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtxyimnkto.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvtviqdk.html

[Q82] 字符长度与字节长度
来源：http://dali.hnqzz.top/Article/details/gtgytafksx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtxmvygzzs.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyoumtrxd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtidfrvzxt.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gtkqnhmtcs.html

SELECT TRIM(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtgteestxy.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gtsnedqixj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhiwuduotai.top/Article/details/gtkqkrmmbc.html

[Q86] 读取 JSON 字段
来源：http://dali.zhengqikj.top/Article/details/gternffunn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.snrcjt.cn/Article/details/gtvfphtvxe.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gtgzqgxqub.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gtinbmjeqs.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuetiantiany.cn/Article/details/gtfrshzkmo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gthebuoyhi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjageixjq.html

[Q89] 判断表是否存在
来源：http://dali.jyoumei.cn/Article/details/gtifaknkxu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.birdmap.top/Article/details/gtktbwwnen.html

[Q90] 生成序号列
来源：http://dali.bjfxy.top/Article/details/gtyarnemfl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gtdsugtbpv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgerapsem.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtluosazcn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtzhgvtdbm.html

[R01] shebang 与严格模式
来源：http://dali.sxryk.cn/Article/details/gtfqpxsbey.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gtfgmrglau.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gtqchmweei.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gtutibcpjb.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gtlqqebfkt.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gtaupjxwnw.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtqxgsfwoq.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gthtdghoap.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.feifeiyinyue.top/Article/details/gttpqgvtvo.html

[R05] 参数默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gtwykpftlj.html

name="${1:-default}"
来源：http://dali.zycfv.cn/Article/details/gttuhurbac.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoowkvabr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtrunbjrdi.html

[R07] if 判断文件
来源：http://dali.cashguo.top/Article/details/gtlucesdtz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shuidangran.top/Article/details/gtdcmyehrt.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gtjjrxbhtl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gtiomcpzwo.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtnquftguc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yvedp.cn/Article/details/gtmbaqgyxh.html

[R10] 正则匹配
来源：http://dali.zhoulong.xyz/Article/details/gtsaqfaefh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtbgvaquqn.html

[R11] case 多分支
来源：http://dali.xylfe.cn/Article/details/gteewqtput.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtpnyfpvqs.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gtipamgpfv.html

stop)  echo "停止" ;;
来源：http://dali.guowangkeji.top/Article/details/gtoozqzbjt.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtwjqoxfpb.html

esac
来源：http://dali.svipenyu.cn/Article/details/gtnaqymqgm.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gteqexlpvu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fzhhl.top/Article/details/gtjobohipz.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gtiqlzwsui.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtxohepgpk.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gthpdkuomq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqattnvzi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gthpceqvkb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gtxydaslgv.html

[R16] until 等待条件
来源：http://dali.cqqwz.cn/Article/details/gthobzdbgk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtytadazbg.html

[R17] 数组定义与取值
来源：http://dali.jqgufenzy.top/Article/details/gtpzgltiwe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gtqaelybfl.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gtopdfuipo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.svipenyu.cn/Article/details/gtsrwiztex.html

[R19] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtkbnpnoyw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gtavwfturx.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gtakkxxtds.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdkmuupf.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtytqfwtjg.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gtujstlluu.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gtxszsfaar.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gtfdvcheab.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gtavfmxxcp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtkipraryh.html

[R24] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtwbzrxahl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gtbsqquvxq.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gtbmyakpwc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gtktqpwfmf.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gtnxleryfl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhongyouzk.top/Article/details/gttyactrri.html

[R27] 算术展开
来源：http://dali.quarkkingdee.top/Article/details/gtehiknxmn.html

echo $((1 + 2 * 3))
来源：http://dali.chenzaomai.com/Article/details/gtswfxawnh.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gtyydhwrux.html

echo "scale=2; 10/3" | bc
来源：http://dali.bjfxy.top/Article/details/gtuzjvgaih.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaleitlbr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gtmobxamxt.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtkcgldcdc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gtotipslev.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtrabonsnt.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvhixkcs.html

[R32] 参数个数校验
来源：http://dali.vqdsnc.cn/Article/details/gtyugyiroc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydnudzte.html

[R33] 捕获错误并提示行号
来源：http://dali.ydzc1.top/Article/details/gtegpbrbgc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.vqdsnc.cn/Article/details/gtjgoyzktj.html

[R34] 退出时清理
来源：http://dali.xuanzx.com/Article/details/gtgnfozmmj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtcsdsdwex.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gtbwrdzjon.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gtewpomagk.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gtbmrnazex.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gtfhytzuqw.html

[R37] 把输出赋给变量
来源：http://dali.havefunace.top/Article/details/gtwnejzfsq.html

files=$(ls -1)
来源：http://dali.9152youxi.cn/Article/details/gtyyundqjp.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gtzittrdqb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gtqgazwdgq.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtlvoasnsh.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtlxqycqzt.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gtnnafdggq.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gtxtjxzjdg.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gtcfaskqty.html

cmd >/dev/null 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtrnmlzlwm.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gtnjzanmfc.html

wc -l < a.txt
来源：http://dali.fzhhl.top/Article/details/gtfgwehrqq.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gtuurhubiw.html

find . -name "*.log" -type f
来源：http://dali.chenzaomai.com/Article/details/gtimuwkejx.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gttwiatyyj.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gtvviksujf.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtadyjqywy.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gtwjcabopi.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gtuqnbohll.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gtodlqfhby.html

[R47] sed 单行替换
来源：http://dali.yvedp.cn/Article/details/gtktugddus.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtbijmvaue.html

[R48] awk 取指定列
来源：http://dali.c1oappe.top/Article/details/gtucndicdn.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtygibpdtv.html

[R49] awk 带条件
来源：http://dali.gotoacloud.top/Article/details/gtclwpwwlh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.svipenyu.cn/Article/details/gttfacohaj.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gtnzvkuakr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtpkidrbhf.html

[R51] 排序去重取前几
来源：http://dali.chenzaomai.com/Article/details/gtjtkytztd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cdnleiting.top/Article/details/gtoexomthw.html

[R52] 统计行数
来源：http://dali.wangdashe.top/Article/details/gtbbskejck.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gtqyiuzzxr.html

[R53] 查看文件头与实时尾
来源：http://dali.feifeiyinyue.top/Article/details/gtziwtxitv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yangfankeji.com/Article/details/gtrmyrkuqx.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gtizzeunki.html

diff a.txt b.txt
来源：http://dali.tian-w.cn/Article/details/gtodyofxgp.html

[R55] 压缩与解压
来源：http://dali.gaohongyu789.top/Article/details/gttrlfrefv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ydzc1.top/Article/details/gteyrqlejy.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzcakixn.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gtbhyuflfl.html

[R57] 远程执行命令
来源：http://dali.daxiang520.top/Article/details/gtzxammhqs.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangtech.top/Article/details/gtuifojwrt.html

[R58] 下载文件
来源：http://dali.guannengcc.top/Article/details/gtatznknlq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenzaomai.com/Article/details/gtghzxehkd.html

[R59] 发 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtvbwdidvf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.havefunace.top/Article/details/gtkptzosef.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtwdinwnqz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gtjmvfawmh.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gtwtopobkw.html

df -h;  du -sh *
来源：http://dali.hammf.cn/Article/details/gtwnlihdqj.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gtwxnvcajq.html

du -ah . | sort -rh | head -10
来源：http://dali.andypj.xyz/Article/details/gtwojkwpjp.html

[R63] 内存与进程
来源：http://dali.pengpengdd.cyou/Article/details/gtztmuontd.html

free -h;  ps aux | grep nginx
来源：http://dali.meibo888.top/Article/details/gtbgooknjf.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gtongyjzfl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gttumehnjk.html

[R65] 查看端口占用
来源：http://dali.havefunace.top/Article/details/gtlijzloqe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ppjwa.cn/Article/details/gtwyqnkxlv.html

[R66] 定时任务
来源：http://dali.0kj1m.cn/Article/details/gtdwhjrvac.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gtdthdigna.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gtvtutmyxx.html

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gtvcnihrls.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsgxkuje.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gtnhlmdact.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gthxpraniq.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtrfvnyflp.html

[R70] 时间戳与互转
来源：http://dali.zhixingplan.top/Article/details/gtamsnthbe.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gtcndprumj.html

[R71] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gtorppddos.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ydzc1.top/Article/details/gtjycnznyu.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gtfzokmorn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtqjhoycah.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gtjaxbciqm.html

split -l 1000 big.log part_
来源：http://dali.svipenyu.cn/Article/details/gtupunxqxj.html

[R74] 批量重命名
来源：http://dali.hywenlv.cn/Article/details/gtegsnwhkl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.mhx1999.top/Article/details/gtfcjctsax.html

[R75] 导出环境变量
来源：http://dali.yongpay.top/Article/details/gtkyzlrcxz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jlsjyb.cn/Article/details/gtnpfdveag.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gtvfpxsiui.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtgueobzti.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gtbinxeooo.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gtpwksmtzt.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gtzdondwhw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozssdzbq.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gtkuamlxuz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.iojbl.cn/Article/details/gtgijqhdon.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gtprrsbgsy.html

time ./run.sh
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfkumhuh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnenuazlr.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gtwyarviqk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtuiyewnli.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gtrncwehyo.html

#include <stdio.h>
来源：http://dali.aizwys.cn/Article/details/gtihpltqzn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gtmqpcqicd.html

[S02] C：变量与格式化输出
来源：http://dali.sysykeji.top/Article/details/gttkynmhhq.html

int a = 10; printf("%d\n", a);
来源：http://dali.xinyue.icu/Article/details/gtmhcaikui.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtpeejbtoe.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmluywppj.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gtzjmsokoj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtoojmzbno.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtsmoqyylc.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gtqrjjmbki.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gthrfiybeg.html

strcmp(a, b) == 0
来源：http://dali.cqqwz.cn/Article/details/gtdffhjijy.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtjybxqdfw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.c1oappe.top/Article/details/gtmnmwntxy.html

[S08] C：动态内存分配与释放
来源：http://dali.kuanghao11.cn/Article/details/gtdgtybayp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gzhubu.top/Article/details/gtwjbdiikg.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gtgutxhfwv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gtldnhtcjs.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gtfoudpxhy.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gtdqqqsrza.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtahudnqng.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gtlpnlzbwu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gtchapokws.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtlsucyuua.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gtrdlubyek.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtlzvpftos.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gtrzvdpyuv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gtozhozmzx.html

[S14] C：枚举
来源：http://dali.jianghu66.top/Article/details/gtvvjcojag.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gttfsvbgyv.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gtuorkhtbz.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gtxkwvxtaz.html

[S16] C：位操作置位
来源：http://dali.yuanzhike.top/Article/details/gtsaiuhtmu.html

x |= (1 << 3);
来源：http://dali.zhoulong.xyz/Article/details/gthxdjyncu.html

[S17] C：安全拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtfihmirtt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tianlin.xyz/Article/details/gtzpnusdut.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtjdgholdh.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gtoxjsoidz.html

[S19] C：快速排序
来源：http://dali.zdqjudy.top/Article/details/gtexsffvxc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpbdmgtr.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gtlviipglo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gttiqdxyra.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gtdwdjfbqn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gtbjoovhlj.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gtyyqhsnen.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gtasvwurzj.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gtufertfjt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gtyszdeyjp.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gteplgisyw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gtmjyuxvqj.html

[S25] C：内存拷贝
来源：http://dali.gogol.net.cn/Article/details/gteqcgiecq.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gtepyiccvq.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gtsyumqbfq.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gtzstwjkeu.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gtzykzurnh.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfdglsuw.html

[S28] C：静态变量
来源：http://dali.316326.xyz/Article/details/gtwruiicng.html

static int counter = 0;
来源：http://dali.gzhubu.top/Article/details/gtspmdolib.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtsmqfzptf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhiwuduotai.top/Article/details/gtqmlubqiu.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gtzclrgwlm.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gtppwevjft.html

#define X_H
来源：http://dali.havefunace.top/Article/details/gtgbmutonk.html

#endif
来源：http://dali.ivvv.top/Article/details/gtieufsvzo.html

[S31] C++：Hello World
来源：http://dali.ivvv.top/Article/details/gtojorjpzn.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtnvgelmtr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aibaodan.cn/Article/details/gtjsvkrkvr.html

[S32] C++：字符串
来源：http://dali.ybcxt.top/Article/details/gtzbcbidtu.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gtxsagykzc.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtrbfkzzfq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflfemzbp.html

[S34] C++：遍历 vector
来源：http://dali.zycfv.cn/Article/details/gtdnqmccxx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gtlmzifnpb.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gtbucwgtoq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtznbybxbf.html

[S36] C++：unordered_map
来源：http://dali.cheryme.top/Article/details/gtybfzuxhm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gteklzjizz.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gttxetcgiw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gtxjipnkjt.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gtikqgeicm.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtkernsszt.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gttldprooe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aibaodan.cn/Article/details/gtczpjleyt.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gtxeuxpcfm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gtaqzngsda.html

[S41] C++：类与构造函数
来源：http://dali.yonumen.top/Article/details/gtzlofijhc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gtyzjclihy.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gtwrdxpece.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhongyouzk.top/Article/details/gtkfwspfsf.html

[S43] C++：智能指针
来源：http://dali.bjfxy.top/Article/details/gtijpojfrl.html

auto p = std::make_unique<int>(5);
来源：http://dali.daxiang520.top/Article/details/gttodjbfot.html

[S44] C++：引用传参
来源：http://dali.shuidangran.top/Article/details/gtemjjosrq.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gtrxymmhdj.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gthiqdvhum.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gotoacloud.top/Article/details/gtwefhwrtf.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gtmqfhdgvq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gtmrgttfxa.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gtpveycwbe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gtydotnaua.html

[S48] C++：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtspueimnv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gtvsdlimuo.html


<!-- 参考信息 -->