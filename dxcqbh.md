代发 wailian999

[Q80] 字符串截取
来源：http://dali.cqqwz.cn/Article/details/gtnjihowzl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.havefunace.top/Article/details/gtpbcahyac.html

[Q81] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtpvoafjvh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtmpqyuoji.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gtmbxssjeg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtvgrcqous.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtkgsvzakp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtcregnich.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gtaennvigv.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtzysuikgb.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gtttbbzdnl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gtqtagjcxu.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gtukuixoxg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gtihzukiun.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gtzoffalwx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gtjraedael.html

[Q88] 行转列（条件聚合）
来源：http://dali.sufxvd.cn/Article/details/gttzrjxfib.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gthxfrhima.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gteabmycpc.html

[Q89] 判断表是否存在
来源：http://dali.sweek.top/Article/details/gtqefhrzwa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtzwmxzawk.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gtpcgdeivm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jiagoushi.top/Article/details/gttwftxiim.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gttlurmimv.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtfuumkeul.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtcrscusdo.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gtdjyqhlst.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gtlzfswkle.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtaoqbpelw.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtssuatqne.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtcizneffu.html

[R03] 只读变量
来源：http://dali.wangshuangyany.cn/Article/details/gtmpucpisx.html

readonly PI=3.14
来源：http://dali.hysaishi.cn/Article/details/gtvkeraayw.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gthdyoyrey.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yonumen.top/Article/details/gthllabfpe.html

[R05] 参数默认值
来源：http://dali.jianghu66.top/Article/details/gtwhnablml.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtwaddtclo.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtljekxfvo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gtpuaoazjn.html

[R07] if 判断文件
来源：http://dali.yanxiufei.cn/Article/details/gtbwljfcmr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.smart0.xyz/Article/details/gtglcmwdhv.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gtpqckgcqe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.meibo888.top/Article/details/gtbvnemfhw.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtkaxihxrp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjpafchx.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gtezaumggr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gtkkiwmntn.html

[R11] case 多分支
来源：http://dali.chenlongwang.top/Article/details/gtbvwwsqed.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gttfcqxrku.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtefnamonf.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gtxekmciqh.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gtjqadylny.html

esac
来源：http://dali.aibaodan.cn/Article/details/gtqqglltnj.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gtcqqnmcoj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhengqikj.top/Article/details/gtouzcxazg.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtdooroxvy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtnucmiepv.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gtzwtkuxcf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtxtkogqcf.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtspnsmxcs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cqqwz.cn/Article/details/gtyrikghwv.html

[R16] until 等待条件
来源：http://dali.jlsjyb.cn/Article/details/gtlfeifkaz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtlgkrotoj.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gtkoqygeud.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jlsjyb.cn/Article/details/gtdxuhcubv.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gtudvucltt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gtixyypoio.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtinsqzsxw.html

echo "${#arr[@]}"
来源：http://dali.zhengqikj.top/Article/details/gtnajsgvwc.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gtraeiamnd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ivvv.top/Article/details/gtrsrjaaoy.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtnydhutbz.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gtaptliwbf.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtuofyqodm.html

echo "${s:0:5}"
来源：http://dali.tian-w.cn/Article/details/gtyapwzgxh.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gtezkemtmq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gtvhjpcaqk.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtlnsvmxqf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gtkwbgoeso.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gtojoxwtnu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhongyouzk.top/Article/details/gtecpiibbz.html

[R26] 命令替换
来源：http://dali.xylfe.cn/Article/details/gtablkukyr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawnuhoye.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfoshujo.html

echo $((1 + 2 * 3))
来源：http://dali.ehwqpu.com/Article/details/gtcduechyl.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gtolmoaazu.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gtrfrqtwux.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtzvogupmu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dashuyun.cn/Article/details/gthnubqmhp.html

[R30] 函数返回状态码
来源：http://dali.yj20258.top/Article/details/gthkimicyc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.birdmap.top/Article/details/gtdfwzsjks.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtgzmzxyll.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gtgksloven.html

[R32] 参数个数校验
来源：http://dali.xziqi.cn/Article/details/gtjkmvqkev.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjluukucg.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gthdlvetzl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gtxqkrdmaa.html

[R34] 退出时清理
来源：http://dali.quarkkingdee.top/Article/details/gtjenfmchl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtxtigrlly.html

[R35] 后台执行并等待
来源：http://dali.jyoumei.cn/Article/details/gtjwlvgund.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.iojbl.cn/Article/details/gtkuqijptj.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gtnsnpqikt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.mhx1999.top/Article/details/gtfdzneofi.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gtzzxfwqvb.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gttzwppawt.html

[R38] 管道串联
来源：http://dali.c1oappe.top/Article/details/gtrnudbeeo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gaohongyu789.top/Article/details/gtrywdbtij.html

[R39] 重定向标准输出与错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxlhgesm.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gtebeicxiu.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gthxzfapmg.html

echo "log" >> out.log
来源：http://dali.wangdashe.top/Article/details/gtsitxtnud.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gtlbhzjqjg.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gtcjjejmci.html

[R42] 输入重定向
来源：http://dali.xuanzx.com/Article/details/gtlhfunjxo.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gteegdwium.html

[R43] 按名字查找文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsjornvz.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gtulxheopw.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gtzlsuvdpd.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gtriruexqr.html

[R45] 批量删除
来源：http://dali.316326.xyz/Article/details/gtcjpflmri.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258.top/Article/details/gtrylxxzqx.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gtqvxdmyab.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xziqi.cn/Article/details/gtokwqopmz.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtlmgwxlkq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yongpay.top/Article/details/gtepaqpznu.html

[R48] awk 取指定列
来源：http://dali.aizwys.cn/Article/details/gtikizjlxe.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtwobupwlq.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gtzecutzfw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgttoqphg.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gtbtzzqjis.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdjptbgd.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gtkdsbkyzw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gtqskacyfy.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gtykszljrs.html

wc -l a.txt
来源：http://dali.daria6918.cn/Article/details/gtlarihzvl.html

[R53] 查看文件头与实时尾
来源：http://dali.yongpay.top/Article/details/gtfhdnaxgu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gtqkzffwlx.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gtilnznchw.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gtuqcvaqac.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrldjfni.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gtnbxtbiin.html

[R56] 远程拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtnsrzbqjt.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gtiokmfrwk.html

[R57] 远程执行命令
来源：http://dali.yanxiufei.cn/Article/details/gtabreusje.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gtacqeavgp.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gthkjhkldf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yongpay.top/Article/details/gtpzbzymyp.html

[R59] 发 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtlygaymtv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sysykeji.top/Article/details/gtdvyvpbsx.html

[R60] 只看 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gtjwqczuqi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258888.top/Article/details/gtlghoeiio.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtctgyhauo.html

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gtmgggqdpv.html

[R62] 找最占空间的文件
来源：http://dali.316326.xyz/Article/details/gtwjsjkubh.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gtygoxfodn.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gtskhzoovt.html

free -h;  ps aux | grep nginx
来源：http://dali.316326.xyz/Article/details/gtonytqgst.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gtwboypxgh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gtvkuuzygd.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gtbphrvjwe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.9152youxi.cn/Article/details/gtixtgxmtw.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gtwaonidsx.html

crontab -e;  crontab -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpgemwbd.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gtmxphijgd.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gtcfomryzg.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzudbbqe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtyevxiwvh.html

[R69] 生成随机密码
来源：http://dali.zhengqikj.top/Article/details/gtxxzzutwr.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gtvbhyfdfp.html

[R70] 时间戳与互转
来源：http://dali.ybcxt.top/Article/details/gtvfadhovs.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gttbpymsub.html

[R71] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtrfrzvzrv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gtomraxrnc.html

[R72] 等待端口就绪
来源：http://dali.hongshengwenyu.top/Article/details/gtvvkarghs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtixrfqvdf.html

[R73] 分割大日志
来源：http://dali.ydzc1.top/Article/details/gtxusqyqwm.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gtovgfgoek.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtushazigc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gtjwngyajr.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gtxitnulcq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gtxlujscqd.html

[R76] 使用临时文件
来源：http://dali.yueranfly.top/Article/details/gtxqwazpqy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gteqzrcojt.html

[R77] 读取用户输入
来源：http://dali.hnxiangtu.top/Article/details/gtfhygzrig.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gtjliewjya.html

[R78] 交互式菜单
来源：http://dali.nanxuanxn.top/Article/details/gtumoawise.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gtjoixesms.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gtnjzhdosd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gttoxpmmjp.html

[R80] 查看脚本执行耗时
来源：http://dali.sysykeji.top/Article/details/gtcpqoqthl.html

time ./run.sh
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqsoaruc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtewvowfxk.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gtqouhvtub.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgctenpbt.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtegmzdvug.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gthlscecih.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gtinnntuxm.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gtnphbtldv.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gtgpbjxiwg.html

[S03] C：读入整数
来源：http://dali.zycfv.cn/Article/details/gtkmpkgesi.html

int x; scanf("%d", &x);
来源：http://dali.cucudq.cn/Article/details/gtwnsqkpbd.html

[S04] C：字符串复制
来源：http://dali.9152youxi.cn/Article/details/gtflxngjgy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtysuhrgbo.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtgvijbwrz.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gtuonidunb.html

[S06] C：字符串比较
来源：http://dali.yj202588.top/Article/details/gtglxlpwpx.html

strcmp(a, b) == 0
来源：http://dali.cqqwz.cn/Article/details/gtcsloukhy.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gtslubkroi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnxiangtu.top/Article/details/gtmkxxtbpe.html

[S08] C：动态内存分配与释放
来源：http://dali.smart0.xyz/Article/details/gtnafzupwb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenjidiqi.icu/Article/details/gtvgjnobyy.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gttiuknpcb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sufxvd.cn/Article/details/gtiomnkpah.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gtkepmhkkz.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gtxbytcube.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtetzclsnn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gtlqxywwme.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuanzhike.top/Article/details/gttfkowctc.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gtglzcmclv.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gtcrnxedzn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gttrcjmomo.html

[S13] C：宏定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkszqbisb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gtbnbnmyyu.html

[S14] C：枚举
来源：http://dali.xinyue.icu/Article/details/gtnzwgnvgs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gtitbiuges.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtkayxnjfk.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gtttruuuxm.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gttozrhrgg.html

x |= (1 << 3);
来源：http://dali.yuxming.cn/Article/details/gtocssumfi.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtacncffvg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gttjjzqskv.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gtsogdbshc.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gtfefgqmlu.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gtlxqsrrpi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtkhyescev.html

[S20] C：二分查找
来源：http://dali.gotoacloud.top/Article/details/gtnhummdms.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtinaychyw.html

[S21] C：字符类别判断
来源：http://dali.chenlongwang.top/Article/details/gtnqcbpmpx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zycfv.cn/Article/details/gtuoyhdysf.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gtwmxciues.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxasmebiq.html

[S23] C：随机数
来源：http://dali.zdqjudy.top/Article/details/gtapchipta.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gtbbtgkvjf.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gthyfqjfjr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dashuyun.cn/Article/details/gtnohmlzgo.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gtwehngwzf.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gtzcpffdjt.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gtqtwchhlg.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gthlhdqgnm.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gtqqsmzpcd.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtkkjlpkfk.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluuwmekg.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtcrjhxexd.html

[S29] C：变参函数
来源：http://dali.sweek.top/Article/details/gtodyeuett.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gthhnbprzc.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gttjnepgdl.html

#ifndef X_H
来源：http://dali.gotoacloud.top/Article/details/gtwlyewghf.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gtnllzskav.html

#endif
来源：http://dali.xylfe.cn/Article/details/gtociluwym.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gtgacajyxu.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gtpdpixkwg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gtjkkkbxgc.html

[S32] C++：字符串
来源：http://dali.yanxiufei.cn/Article/details/gteoytcozi.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gthhyezxwd.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gtgfcyoytz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gtrizxgrzq.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gtaogsfeds.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtgpdnvacm.html

[S35] C++：map
来源：http://dali.ybcxt.top/Article/details/gtfmgwntfi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gthitbatvy.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gtiedayplc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtcfqlddxh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gtnkcclafc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gtmlshdhrs.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gtenqvhwir.html

std::sort(v.begin(), v.end());
来源：http://dali.c1oappe.top/Article/details/gtvqyxuxrb.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gtinhnhmmx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenzaomai.com/Article/details/gtzsutrhdj.html

[S40] C++：查找元素
来源：http://dali.dashuyun.cn/Article/details/gtmuibrtjd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gtgbllallz.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtnbjcgaze.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hywenlv.cn/Article/details/gtjppfssae.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gtqdomdchn.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gtmpjkcsms.html

[S43] C++：智能指针
来源：http://dali.zhixingplan.top/Article/details/gtdymhibll.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gtolwkrsgu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gttqnojwjb.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gtlrwbwzay.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtsmcqtpxg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhiwuduotai.top/Article/details/gtipxxjgyb.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtouapegly.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aizwys.cn/Article/details/gtqtdjctnk.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gtormwjemn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jlsjyb.cn/Article/details/gttrdtiyqf.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtdgcibdxo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigfzy.top/Article/details/gtilqdxzeb.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gtbpfwygkd.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gtiozhqsgv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gthwcdneya.html

[S50] C++：格式化数字
来源：http://dali.ivvv.top/Article/details/gtbovwjrpg.html


<!-- 参考信息 -->