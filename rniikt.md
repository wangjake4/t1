代发 wailian999

[Q78] 当前时间
来源：http://dali.mhx1999.top/Article/details/gtlreidnnc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xylfe.cn/Article/details/gtemomssdg.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gteptzrvui.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yangfankeji.com/Article/details/gtrquyqums.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gtetpungzc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hammf.cn/Article/details/gtaefdddlr.html

[Q81] 字符串替换
来源：http://dali.birdmap.top/Article/details/gthyqakaqm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nwbrower.top/Article/details/gtkkythsdf.html

[Q82] 字符长度与字节长度
来源：http://dali.chenjidiqi.icu/Article/details/gtmtpoffiy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtzpcndkid.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtwcoakunv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtibphoini.html

[Q84] 去除首尾空格
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbceaixpe.html

SELECT TRIM(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtfpnvxnfa.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gtbmsujyts.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xziqi.cn/Article/details/gtbxfqxmnk.html

[Q86] 读取 JSON 字段
来源：http://dali.svipenyu.cn/Article/details/gtmzupgjpv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gtkwjuxibn.html

[Q87] JSON 字段做条件
来源：http://dali.yangfankeji.com/Article/details/gtmtfmucgs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangtech.top/Article/details/gtznfbftkp.html

[Q88] 行转列（条件聚合）
来源：http://dali.sufxvd.cn/Article/details/gtyrhobjfu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gtulephbmx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gtngdkifuk.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtfxyatgha.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aibaodan.cn/Article/details/gtioesgbxc.html

[Q90] 生成序号列
来源：http://dali.yongpay.top/Article/details/gtfszagqsa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gtrlzgppou.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtfozbvdyc.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtcjsbplkt.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtfgfdyttp.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gtnbcslkjo.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gthvhohwqc.html

set -euo pipefail
来源：http://dali.iojbl.cn/Article/details/gtzaqejzvo.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gtursygpix.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gthmalloyz.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gtxqgsudnw.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gtcmtholdm.html

[R04] 位置参数
来源：http://dali.aibaodan.cn/Article/details/gtrypihedl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hywenlv.cn/Article/details/gtjdcbfwuc.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtgligmeyz.html

name="${1:-default}"
来源：http://dali.andypj.xyz/Article/details/gtsswgqeki.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gthvdrorzj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtpkqtwenk.html

[R07] if 判断文件
来源：http://dali.gogol.net.cn/Article/details/gtztuymugg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gthqqvznbo.html

[R08] 数值比较
来源：http://dali.hnxiangtu.top/Article/details/gtpdtmcdwy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtclbilyma.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtyuulirrd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gtohtfpqii.html

[R10] 正则匹配
来源：http://dali.hnxiangtu.top/Article/details/gttiizmhld.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tianlin.xyz/Article/details/gtrfqjnafb.html

[R11] case 多分支
来源：http://dali.haohaochexian.top/Article/details/gtnjjyyaif.html

case "$1" in
来源：http://dali.yuxming.cn/Article/details/gtuofqmomq.html

start) echo "启动" ;;
来源：http://dali.pycfn.com/Article/details/gtaygsxpao.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gtbeiwgmpi.html

*)     echo "未知命令" ;;
来源：http://dali.cashguo.top/Article/details/gtmjeewskn.html

esac
来源：http://dali.bjfxy.top/Article/details/gtokwvjhsk.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gtbmfvfuwu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtjckppdtn.html

[R13] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gtvixfyvkr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtbmtxuzfp.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gtynfocoyy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtnfjxjwrq.html

[R15] while 逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gteoqkilio.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.snrcjt.cn/Article/details/gtpizirhhv.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gtatqokqxt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtoenwbyeu.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gtahcftkov.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtmjlnvgyy.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gtwibhnjoh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gtbhwysmbb.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtqsiovmrm.html

echo "${#arr[@]}"
来源：http://dali.shuidangran.top/Article/details/gtlsttmryp.html

[R20] 关联数组（字典）
来源：http://dali.jqgfzy.top/Article/details/gtlgtxiqmx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjuxykerf.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtfpofrsve.html

echo "${#s}"
来源：http://dali.chenjidiqi.icu/Article/details/gtqurgodvx.html

[R22] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gtwpwpvbcl.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gtwyvkabtu.html

[R23] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtljfxtnrc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gtaxlxhqhm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtuyevepcr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.vqdsnc.cn/Article/details/gtqiavuddo.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gtrgyqthmx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.redwolf501.top/Article/details/gtedyyjpyt.html

[R26] 命令替换
来源：http://dali.svipenyu.cn/Article/details/gtghosxadk.html

now=$(date +%F); echo "$now"
来源：http://dali.bjfxy.top/Article/details/gtaxoqkuhg.html

[R27] 算术展开
来源：http://dali.yonumen.top/Article/details/gtidtlbqot.html

echo $((1 + 2 * 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofxsysnb.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gtknqasnyq.html

echo "scale=2; 10/3" | bc
来源：http://dali.hfpthk.cn/Article/details/gtssxzgspi.html

[R29] 定义函数
来源：http://dali.ydzc1.top/Article/details/gtdhzvtoib.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zycfv.cn/Article/details/gtuvycdqda.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gtiqrfeclf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhixingplan.top/Article/details/gtfzfrpdfe.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gtgmmhjgio.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gtfklhdxhd.html

[R32] 参数个数校验
来源：http://dali.c1oappe.top/Article/details/gtwsuyhhqe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtqiabtxgu.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gtqbwxcauu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgufenzy.top/Article/details/gtfzgxuswt.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gtxzcvliwr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtwsetjbfx.html

[R35] 后台执行并等待
来源：http://dali.9152youxi.cn/Article/details/gtythlysvk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gttndgrwci.html

[R36] 并发执行多个任务
来源：http://dali.zhixingplan.top/Article/details/gtjygmslgb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdncigait.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gtrbihiwat.html

files=$(ls -1)
来源：http://dali.316326.xyz/Article/details/gtyoymyfdr.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gtdbbrrmeq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.meibo888.top/Article/details/gtadgrlpbw.html

[R39] 重定向标准输出与错误
来源：http://dali.zdqjudy.top/Article/details/gtqzmjljab.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gtsbvvoqgu.html

[R40] 追加写日志
来源：http://dali.sysykeji.top/Article/details/gtamnfqosc.html

echo "log" >> out.log
来源：http://dali.fengsongda.top/Article/details/gtuvajrcyg.html

[R41] 丢弃输出
来源：http://dali.snrcjt.cn/Article/details/gtpfckbebj.html

cmd >/dev/null 2>&1
来源：http://dali.yj202588.top/Article/details/gtbkxvtmop.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gtamxhgfdh.html

wc -l < a.txt
来源：http://dali.0kj1m.cn/Article/details/gtzmiqckcg.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gtdjopjrzy.html

find . -name "*.log" -type f
来源：http://dali.zycfv.cn/Article/details/gtlesquvoe.html

[R44] 按修改时间查找
来源：http://dali.haohaochexian.top/Article/details/gtdclfcptn.html

find . -mtime -7 -type f
来源：http://dali.tanke756.top/Article/details/gtvjquezgv.html

[R45] 批量删除
来源：http://dali.cheryme.top/Article/details/gtxssbqfyn.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gtkjxfnnck.html

[R46] 递归替换文件内容
来源：http://dali.sysykeji.top/Article/details/gtfqfzhala.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gtzglglyzz.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gtkkumzibr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cucudq.cn/Article/details/gtqzlgdghu.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gtoybdxdoh.html

awk '{print $1, $3}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtpyrwvghs.html

[R49] awk 带条件
来源：http://dali.sweek.top/Article/details/gtydxozmai.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gtyabmijqu.html

[R50] awk 求和
来源：http://dali.dianchejie.cn/Article/details/gtprmuxqpb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtbzvcvkvp.html

[R51] 排序去重取前几
来源：http://dali.hysaishi.cn/Article/details/gtytibitna.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gtfkmlmdgs.html

[R52] 统计行数
来源：http://dali.jinqigufen.top/Article/details/gtspguelsr.html

wc -l a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcmfquqa.html

[R53] 查看文件头与实时尾
来源：http://dali.hnxiangtu.top/Article/details/gtpqlmhooi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gtiawbgrjt.html

[R54] 比较两个文件
来源：http://dali.zdqjudy.top/Article/details/gtgzhgjicq.html

diff a.txt b.txt
来源：http://dali.birdmap.top/Article/details/gtrdxhihox.html

[R55] 压缩与解压
来源：http://dali.sysykeji.top/Article/details/gtcmgcsvxx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gthfqatpyh.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gtddkvlrdb.html

scp file user@host:/path/
来源：http://dali.xylfe.cn/Article/details/gtpiluxxan.html

[R57] 远程执行命令
来源：http://dali.guannengcc.top/Article/details/gtzvtgipdy.html

ssh user@host 'uptime'
来源：http://dali.chenzaomai.com/Article/details/gtmjstbzpu.html

[R58] 下载文件
来源：http://dali.snrcjt.cn/Article/details/gtjlpeyqkr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gtkumeqrgf.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtmjbjeryw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhoulong.xyz/Article/details/gtlbvibdgw.html

[R60] 只看 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gttplysffl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gtzpakpqpr.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gtlcseqedy.html

df -h;  du -sh *
来源：http://dali.dianchejie.cn/Article/details/gtddmdhswz.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gtewdcydcw.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfrytbkf.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxxdkdmt.html

free -h;  ps aux | grep nginx
来源：http://dali.sysykeji.top/Article/details/gtcqhupmhe.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gtforhkubb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ehwqpu.com/Article/details/gtfymwmzdu.html

[R65] 查看端口占用
来源：http://dali.hysaishi.cn/Article/details/gtptcgguys.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daxiang520.top/Article/details/gtavmqznmc.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gtybgyansx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gtuimnwnhi.html

[R67] 生成随机十六进制串
来源：http://dali.316326.xyz/Article/details/gtddxnwccc.html

openssl rand -hex 16
来源：http://dali.jinqigfzy.top/Article/details/gthrzeaiiv.html

[R68] 计算文件校验值
来源：http://dali.vqdsnc.cn/Article/details/gttyoiwbwh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gtmeenwmwm.html

[R69] 生成随机密码
来源：http://dali.aizwys.cn/Article/details/gtllgkblwf.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtscospemp.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtrhyaskjm.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gtkpmomuzp.html

[R71] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtvfwwyrhg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gtmiizpjbn.html

[R72] 等待端口就绪
来源：http://dali.daxiang520.top/Article/details/gtbdomtgew.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gtxdbnbdix.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gtvhesqxxx.html

split -l 1000 big.log part_
来源：http://dali.tianlin.xyz/Article/details/gtzvcoiefa.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gtlhcxgdho.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daxiang520.top/Article/details/gtrqwuxkfk.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtzkjhvhca.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gtkskgmgmk.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gtrddfqsqo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtbgciqhfg.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gtulvewyxt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gtaefrjpqd.html

[R78] 交互式菜单
来源：http://dali.nwbrower.top/Article/details/gtaocjywab.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gtgoxuahkg.html

[R79] 解析命令行选项
来源：http://dali.haohaochexian.top/Article/details/gtnyovwlzb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gtzgmqebgr.html

[R80] 查看脚本执行耗时
来源：http://dali.sweek.top/Article/details/gtbqchehmo.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gttufqmbku.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtznxlqfle.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtlfpdcbtv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmwpdeqej.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtrmnfjbhh.html

#include <stdio.h>
来源：http://dali.tianlin.xyz/Article/details/gtoevryirk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gtgrwsfsgw.html

[S02] C：变量与格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtwapaoqgn.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gtwtndcwkx.html

[S03] C：读入整数
来源：http://dali.chenjidiqi.icu/Article/details/gtwehknhzs.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gtaytiltyx.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gtkijrycba.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtxvqfkcld.html

[S05] C：字符串长度
来源：http://dali.ydzc1.top/Article/details/gtrvzhlrub.html

strlen(s)
来源：http://dali.chenzaomai.com/Article/details/gtaqnixiiq.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gttxddrihy.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gtahbnsgbt.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gtdbslinjf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xziqi.cn/Article/details/gtngcrqjsx.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gttrtjljwu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gthmpzuqnu.html

[S09] C：结构体定义与初始化
来源：http://dali.wangdashe.top/Article/details/gtoptoirkr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtouzjuhet.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gtkvifidmq.html

int *p = &a;  *p = 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvktmqbzv.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtyyqqimpu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sweek.top/Article/details/gtnqqrexxe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.mhx1999.top/Article/details/gtqtfotequ.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtkfybyiaq.html

[S12] C：写文件
来源：http://dali.hnqzz.top/Article/details/gtuopksecj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtmqqcypni.html

[S13] C：宏定义
来源：http://dali.jinqigufen.top/Article/details/gtqcceobij.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljvgajbo.html

[S14] C：枚举
来源：http://dali.hnqzz.top/Article/details/gtwluxfkno.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gtmamnaswg.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gtectgsjfm.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gttvtpbpkc.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gtbdipifrq.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gtkvwshmek.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gthxvnslnp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pengpengdd.cyou/Article/details/gtmieechnd.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtsqconpyc.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gtzyodfzlj.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtvchemolr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtowmoarjh.html

[S20] C：二分查找
来源：http://dali.hysaishi.cn/Article/details/gtoijzyztt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gtzadkgead.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gtepfmwxin.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tianlin.xyz/Article/details/gtigfnovoo.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gtadnqytzt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gtqhbaomta.html

[S23] C：随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gthjkcmajq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gthqcwjklh.html

[S24] C：获取本地时间
来源：http://dali.sufxvd.cn/Article/details/gtdzmtrdxe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtcqsgpdsu.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gtkprwcebp.html

memcpy(dst, src, n);
来源：http://dali.0kj1m.cn/Article/details/gtbnmpscos.html

[S26] C：内存清零
来源：http://dali.redwolf501.top/Article/details/gtdzrwfnqq.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gtoihvcjgw.html

[S27] C：定义常量
来源：http://dali.smart0.xyz/Article/details/gtzbmopbmj.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtgmyibsti.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gtteuvhfqk.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gtynpwpbbz.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gtsmcmjxcl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pycfn.com/Article/details/gtvpqzrfex.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gtyjcpzlwl.html

#ifndef X_H
来源：http://dali.yuxming.cn/Article/details/gteioamgas.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gthdudrnzc.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gtnvygnxcj.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gttexmgezr.html

#include <iostream>
来源：http://dali.haohaochexian.top/Article/details/gtyyvlcpzw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gtjzlsysil.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gthjtdvbvl.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtfilcmlpr.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gtioytuhsi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtindhuowk.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gttboiyhaw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj202588.top/Article/details/gtevrfduby.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gtkwnclfgy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtdgvejosu.html

[S36] C++：unordered_map
来源：http://dali.ehwqpu.com/Article/details/gtdhdbymuv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtpflinzdk.html

[S37] C++：set
来源：http://dali.iojbl.cn/Article/details/gtjthmffqm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yanxiufei.cn/Article/details/gtfsdoubrh.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gtcpbnzqiq.html

std::sort(v.begin(), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtotflpyry.html

[S39] C++：自定义比较器排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsxmmdbc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gtqsjxzuvp.html

[S40] C++：查找元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtoeomhlqd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gtkrltdyjs.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthudwmus.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hammf.cn/Article/details/gtwdeddmxu.html

[S42] C++：继承与虚函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyvvvvjg.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnqzz.top/Article/details/gtrdrxslzr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gthuaqloow.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gthztdqslv.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gteqvrisqv.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gtwyuijcrs.html

[S45] C++：lambda
来源：http://dali.ppjwa.cn/Article/details/gtjxtjtmdj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoirkquo.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gtriqrrjtb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gtygcnddye.html

[S47] C++：结构化绑定遍历
来源：http://dali.andypj.xyz/Article/details/gtnbokpbgw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqyjbvti.html

[S48] C++：逐行读文件
来源：http://dali.pycfn.com/Article/details/gttkleknqg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tian-w.cn/Article/details/gtbttfxmka.html


<!-- 参考信息 -->