代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.zycfv.cn/Article/details/gt2nvlgqzvt.html

SELECT TRIM(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmkwfaif.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gt2suvdjfcq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gt2sojghnsj.html

[Q86] 读取 JSON 字段
来源：http://dali.xuanzx.com/Article/details/gt2vwngiwhu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhixingplan.top/Article/details/gt2hxbhwwwi.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dleirnhc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gt2wrrzeasc.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mkxxhhss.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gt2iytngbow.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2erualhwx.html

[Q89] 判断表是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2syekqnfx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gt2rjjalukh.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gt2lomvehbl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.vqdsnc.cn/Article/details/gt2rezxffar.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2occjmrnf.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gt2sefbhrjg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2nioteajq.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gt2ezzmqgst.html

#!/usr/bin/env bash
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnbfqceb.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gt2osbatkyz.html

[R02] 变量赋值与使用
来源：http://dali.yj20258888.top/Article/details/gt2lhyvthon.html

name="Tom"; echo "$name"
来源：http://dali.cdnleiting.top/Article/details/gt2twebywlr.html

[R03] 只读变量
来源：http://dali.vqdsnc.cn/Article/details/gt2frhxgzcz.html

readonly PI=3.14
来源：http://dali.snrcjt.cn/Article/details/gt2nrwmmcbh.html

[R04] 位置参数
来源：http://dali.daxiang520.top/Article/details/gt2pebrmsya.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zdqjudy.top/Article/details/gt2vlyzfiya.html

[R05] 参数默认值
来源：http://dali.jiagoushi.top/Article/details/gt2hozqlqsv.html

name="${1:-default}"
来源：http://dali.shuidangran.top/Article/details/gt2qbunkmoa.html

[R06] 判断命令是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2anoldeze.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2txhkfbks.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gt2lbgezpco.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yonumen.top/Article/details/gt2mdcgirsm.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gt2nqnlanhw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gt2qoxwiqye.html

[R09] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gt2vmmsrjit.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.c1oappe.top/Article/details/gt2citfqcly.html

[R10] 正则匹配
来源：http://dali.mhx1999.top/Article/details/gt2ukuglqon.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vkingshi.html

[R11] case 多分支
来源：http://dali.hysaishi.cn/Article/details/gt2ddbjpggr.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gt2stmgwwzi.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2hzhmtkxy.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gt2miefhprp.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gt2dtosmiti.html

esac
来源：http://dali.xylfe.cn/Article/details/gt2hrvwmmpz.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gt2dniqmmdr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gt2uhrzztjm.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gt2hfmuvzbu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gt2fnhnxatc.html

[R14] C 风格 for
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkpmhwll.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gt2svfipeju.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2pdphwaky.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hysaishi.cn/Article/details/gt2uvxnzqry.html

[R16] until 等待条件
来源：http://dali.andypj.xyz/Article/details/gt2qhofzuht.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gt2mwotannb.html

[R17] 数组定义与取值
来源：http://dali.nanxuanxn.top/Article/details/gt2qgegvhfr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gt2mzyjscjt.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gt2dwdkfvfy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gt2vsmbyrsz.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2aafosozi.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gt2zojcjioj.html

[R20] 关联数组（字典）
来源：http://dali.ppjwa.cn/Article/details/gt2dyplguav.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.c1oappe.top/Article/details/gt2qbavweit.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyhacvd.html

echo "${#s}"
来源：http://dali.cheryme.top/Article/details/gt2mjsbrnid.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gt2yyuvtbbg.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gt2idmijbkx.html

[R23] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gt2xvhuobdh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2syleymyl.html

[R24] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gt2ptjydrnc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gt2hsjfixrx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gt2blflbwgm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zdqjudy.top/Article/details/gt2dgvtooqa.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gt2lhrlnivp.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258888.top/Article/details/gt2bnxwfxon.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gt2xhnzfljv.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmirdnyk.html

[R28] 浮点运算
来源：http://dali.hnxiangtu.top/Article/details/gt2jrnitvkt.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gt2roxijmcb.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gt2buiaxhov.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gt2qkowqvzb.html

[R30] 函数返回状态码
来源：http://dali.guannengcc.top/Article/details/gt2yqpusdbe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gt2qdjsfwhv.html

[R31] 局部变量
来源：http://dali.tanke756.top/Article/details/gt2bkqoebew.html

f() { local x=1; echo "$x"; }
来源：http://dali.yonumen.top/Article/details/gt2wihimqwu.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gt2xkikezmc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gt2dyawctdg.html

[R33] 捕获错误并提示行号
来源：http://dali.hnqzz.top/Article/details/gt2yesmjlgj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2byjnfjwm.html

[R34] 退出时清理
来源：http://dali.yuanzhike.top/Article/details/gt2kmodvrsq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gt2khpiggek.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gt2qpscspop.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cashguo.top/Article/details/gt2qszcenvf.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gt2ivarbzle.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.birdmap.top/Article/details/gt2agrprszr.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gt2yaunnbht.html

files=$(ls -1)
来源：http://dali.daxiang520.top/Article/details/gt2zestpgyy.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gt2vomayiuo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gt2gcfqecvd.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gt2rvzymypw.html

cmd > out.log 2>&1
来源：http://dali.yj20258.top/Article/details/gt2uyfmolow.html

[R40] 追加写日志
来源：http://dali.xuanzx.com/Article/details/gt2onbmqwdy.html

echo "log" >> out.log
来源：http://dali.meibo888.top/Article/details/gt2chornrzg.html

[R41] 丢弃输出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hcgnpmkn.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gt2mzhbbjvg.html

[R42] 输入重定向
来源：http://dali.9152youxi.cn/Article/details/gt2repiqugn.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gt2gwpcdofb.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gt2siogfbmy.html

find . -name "*.log" -type f
来源：http://dali.yueranfly.top/Article/details/gt2dakcurja.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gt2nyblsgbv.html

find . -mtime -7 -type f
来源：http://dali.yj20258.top/Article/details/gt2kblrkeul.html

[R45] 批量删除
来源：http://dali.redwolf501.top/Article/details/gt2lfzrlesp.html

find . -name "*.tmp" -delete
来源：http://dali.gzhubu.top/Article/details/gt2fpwzqjke.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gt2uxdeaclp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbarjsbz.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gt2zhnrnvet.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2baoxddyj.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gt2psxththu.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2zirhrspc.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gt2nnhnsfgj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gt2ptehvdrn.html

[R50] awk 求和
来源：http://dali.dashuyun.cn/Article/details/gt2jtocyojb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gt2pucgsuqd.html

[R51] 排序去重取前几
来源：http://dali.mhx1999.top/Article/details/gt2xezaqbco.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gt2igzvcmud.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gt2ossrwfgo.html

wc -l a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2bqzuabum.html

[R53] 查看文件头与实时尾
来源：http://dali.jyoumei.cn/Article/details/gt2hbbsanvr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gt2dfhpvhop.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gt2rswcddtw.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2acldxrqf.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gt2yhojfpuq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.meibo888.top/Article/details/gt2tygkxtac.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gt2iibzdluk.html

scp file user@host:/path/
来源：http://dali.tianlin.xyz/Article/details/gt2blcjgpra.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gt2khnvregs.html

ssh user@host 'uptime'
来源：http://dali.pengpengdd.cyou/Article/details/gt2nyzfdydl.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gt2xfvbtarj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gt2lczlpjhp.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gt2djopltls.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hfpthk.cn/Article/details/gt2zzmfvgka.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2elilelpz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fengsongda.top/Article/details/gt2rhrjozqu.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gt2fykjoluh.html

df -h;  du -sh *
来源：http://dali.pycfn.com/Article/details/gt2jrvnrrkn.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gt2ipaklzyj.html

du -ah . | sort -rh | head -10
来源：http://dali.jianghu66.top/Article/details/gt2imleosdy.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gt2gnxfrskk.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gt2jqtsrgkk.html

[R64] 结束进程
来源：http://dali.hfpthk.cn/Article/details/gt2uzuqmxpc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nryhbryp.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gt2qpnqcwxh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ivvv.top/Article/details/gt2zbdaszyn.html

[R66] 定时任务
来源：http://dali.zhixingplan.top/Article/details/gt2rcvopgxn.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gt2zbxchlps.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gt2lxphknuu.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gt2clwrlqfl.html

[R68] 计算文件校验值
来源：http://dali.pycfn.com/Article/details/gt2nqpjdmsu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2vfsbwsyo.html

[R69] 生成随机密码
来源：http://dali.hysaishi.cn/Article/details/gt2bffotbeo.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gt2vfjpbdvl.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sosicwax.html

date +%s;  date -d @1700000000
来源：http://dali.ppjwa.cn/Article/details/gt2hsfioler.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gt2ohboidcm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cdnleiting.top/Article/details/gt2wblmcreg.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gt2yobwyoqy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gt2tkmxqlho.html

[R73] 分割大日志
来源：http://dali.redwolf501.top/Article/details/gt2mmxdklnc.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gt2cnmbukdu.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gt2cgzjznpo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gt2xufhywbp.html

[R75] 导出环境变量
来源：http://dali.ehwqpu.com/Article/details/gt2dxntetsy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jyoumei.cn/Article/details/gt2ohpgwwaj.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gt2jhsrgbhi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gt2htrdypvs.html

[R77] 读取用户输入
来源：http://dali.daxiang520.top/Article/details/gt2irjnxzky.html

read -rp "请输入: " ans
来源：http://dali.yvedp.cn/Article/details/gt2hwkwbbmd.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gt2loxrwkqa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tian-w.cn/Article/details/gt2vvggllzh.html

[R79] 解析命令行选项
来源：http://dali.gotoacloud.top/Article/details/gt2hagtdfoy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gt2dyvylqdq.html

[R80] 查看脚本执行耗时
来源：http://dali.cashguo.top/Article/details/gt2ucfnbgyh.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gt2jsoozlcu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2vhnfwktv.html

S. C / C++ 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qiaavfjs.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2prsgcqvq.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gt2dqrbnecr.html

#include <stdio.h>
来源：http://dali.tanke756.top/Article/details/gt2xwxauyaa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangdashe.top/Article/details/gt2exurrrxd.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2dqwuhabj.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuanzx.com/Article/details/gt2etwwnted.html

[S03] C：读入整数
来源：http://dali.fzhhl.top/Article/details/gt2uwzdozwj.html

int x; scanf("%d", &x);
来源：http://dali.cdnleiting.top/Article/details/gt2uowedegp.html

[S04] C：字符串复制
来源：http://dali.cqqwz.cn/Article/details/gt2ullxtqmf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gt2zgpqwacu.html

[S05] C：字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gt2euwswhyn.html

strlen(s)
来源：http://dali.yvedp.cn/Article/details/gt2fzlvdjrg.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2trurqmrw.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gt2jcftktxa.html

[S07] C：数组遍历求和
来源：http://dali.ppjwa.cn/Article/details/gt2ptpqadex.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gt2qlkrdyxy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vfxreouq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gt2dltfgvef.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gt2vunhjnet.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gt2tjtcjaad.html

[S10] C：指针与解引用
来源：http://dali.cashguo.top/Article/details/gt2hkyiamyy.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gt2qmtesvsv.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2fnfrbqer.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gt2hfdbtynm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gt2degvcouf.html

fclose(f);
来源：http://dali.fengsongda.top/Article/details/gt2dzzlmkqm.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gt2swdpfjyq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gt2qblcglhc.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gt2ojjozqpx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gt2oornieyc.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gt2xeolsrdn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.snrcjt.cn/Article/details/gt2vzspzkeo.html

[S15] C：类型转换
来源：http://dali.cucudq.cn/Article/details/gt2kukvfapc.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gt2hcnzwozo.html

[S16] C：位操作置位
来源：http://dali.tian-w.cn/Article/details/gt2qtjearlr.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjypvfkf.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2kwyoozdp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenlongwang.top/Article/details/gt2hkrtfaek.html

[S18] C：命令行参数
来源：http://dali.tanke756.top/Article/details/gt2bjabtngy.html

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gt2jaofvxhy.html

[S19] C：快速排序
来源：http://dali.hnxiangtu.top/Article/details/gt2ttcghkcr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gt2sjimymwf.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gt2ukkglvej.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2yszrjylt.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gt2jaqibhpn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shzxlz.cn/Article/details/gt2stgmsyhn.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gt2eclgzhmn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnzmqrzz.html

[S23] C：随机数
来源：http://dali.jyoumei.cn/Article/details/gt2zcegmbcz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xziqi.cn/Article/details/gt2ntyctntd.html

[S24] C：获取本地时间
来源：http://dali.shuidangran.top/Article/details/gt2nqrdeyok.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gt2hjiauqoh.html

[S25] C：内存拷贝
来源：http://dali.cucudq.cn/Article/details/gt2tqkzkznb.html

memcpy(dst, src, n);
来源：http://dali.jinqigufen.top/Article/details/gt2wosbsymx.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gt2dcfvpcqt.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258.top/Article/details/gt2icinxioq.html

[S27] C：定义常量
来源：http://dali.smart0.xyz/Article/details/gt2llbjprdz.html

const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2lxhjntpv.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqywflfx.html

static int counter = 0;
来源：http://dali.mhx1999.top/Article/details/gt2nepqlppx.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gt2dsrfaqzb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shzxlz.cn/Article/details/gt2fprifqdh.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gt2mpnrnkjd.html

#ifndef X_H
来源：http://dali.cashguo.top/Article/details/gt2adtkrcae.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gt2xbatoisl.html

#endif
来源：http://dali.xziqi.cn/Article/details/gt2vytmpwdq.html

[S31] C++：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2dqqequll.html

#include <iostream>
来源：http://dali.hnxiangtu.top/Article/details/gt2ebwdoktc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tian-w.cn/Article/details/gt2javzfjmc.html

[S32] C++：字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2rriylcqc.html

std::string s = "hi";  s += "!";
来源：http://dali.sufxvd.cn/Article/details/gt2razndmap.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gt2adwdqjrx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gt2rtvpqbwu.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gt2catdvepq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guannengcc.top/Article/details/gt2cidwgdct.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gt2zhobnjgh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2crhhvzai.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gt2nhynvomz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbghjuac.html

[S37] C++：set
来源：http://dali.dashuyun.cn/Article/details/gt2uozoifnj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gt2navrxkco.html

[S38] C++：排序
来源：http://dali.tian-w.cn/Article/details/gt2qpjxihil.html

std::sort(v.begin(), v.end());
来源：http://dali.zdqjudy.top/Article/details/gt2eczkwylg.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gt2yfvgbthc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gt2bqyzdjcy.html

[S40] C++：查找元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jesvkvai.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2itzkigni.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gt2whjcaldr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gt2cmskibnk.html

[S42] C++：继承与虚函数
来源：http://dali.cqqwz.cn/Article/details/gt2eelsnpcf.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gt2uuzqajom.html

[S43] C++：智能指针
来源：http://dali.nanxinkj.top/Article/details/gt2lufwzjjy.html

auto p = std::make_unique<int>(5);
来源：http://dali.sxryk.cn/Article/details/gt2kmfqcgta.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gt2tstjfaau.html

void inc(int &x) { ++x; }
来源：http://dali.cdnleiting.top/Article/details/gt2dyhpypjd.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gt2dqthmemn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gt2pjnkiyef.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gt2tugilebb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gt2cjgqwpca.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gt2lsgemywf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gt2ejawhswg.html

[S48] C++：逐行读文件
来源：http://dali.sweek.top/Article/details/gt2cemssxvi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivdyfxub.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gt2cvmudhli.html

[S49] C++：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzzctajr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gt2lwdjbzfk.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gt2ecbqnvci.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zcokcvhc.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2jmlkczbh.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkkilvas.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqwgbjz.html

int size() const noexcept { return n_; }
来源：http://dali.jiagoushi.top/Article/details/gt2urxgqoxo.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gt2urcwrdqk.html

std::vector<int> w = std::move(v);
来源：http://dali.shangyingyoupin.top/Article/details/gt2matsmqgq.html

[S54] C++：异常处理
来源：http://dali.yueranfly.top/Article/details/gt2kwiwpnyk.html


<!-- 参考信息 -->