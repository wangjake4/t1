代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.iojbl.cn/Article/details/gt2wecomyyy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgfzy.top/Article/details/gt2tklgjfww.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gt2odbipnbs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzidtsba.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gt2kdmywabl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gt2mzohrgcl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2gncpfqdc.html

[Q89] 判断表是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2encgpwic.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gt2iqmgigzd.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gt2kgrucvwk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj202588.top/Article/details/gt2mcbghjix.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2vpiapqoo.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gt2gboudijw.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2bsvvjzbv.html

[R01] shebang 与严格模式
来源：http://dali.jinqigufen.top/Article/details/gt2gsklvqgd.html

#!/usr/bin/env bash
来源：http://dali.fengsongda.top/Article/details/gt2zcafvzru.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gt2mecmiohz.html

[R02] 变量赋值与使用
来源：http://dali.mhx1999.top/Article/details/gt2wzrceknh.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gt2pkfavcwk.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gt2sqsmqfsn.html

readonly PI=3.14
来源：http://dali.gogol.net.cn/Article/details/gt2nbnlcfvx.html

[R04] 位置参数
来源：http://dali.shzxlz.cn/Article/details/gt2mjggetpt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gt2gmhycqlp.html

[R05] 参数默认值
来源：http://dali.yuanzhike.top/Article/details/gt2glxsegbj.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gt2gxjgiwbd.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gt2mtzonfxq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gt2ncrsmqam.html

[R07] if 判断文件
来源：http://dali.yuxming.cn/Article/details/gt2arzvgyrk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xylfe.cn/Article/details/gt2dfgvtgzr.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gt2gtbnondp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ydzc1.top/Article/details/gt2mpvocjts.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2bcqjqqio.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gt2uaockglu.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gt2vayexbnk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gt2dsdgcsbk.html

[R11] case 多分支
来源：http://dali.hysaishi.cn/Article/details/gt2thezjgtt.html

case "$1" in
来源：http://dali.tanke756.top/Article/details/gt2wxrhbvnb.html

start) echo "启动" ;;
来源：http://dali.gaohongyu789.top/Article/details/gt2ohzjxwpp.html

stop)  echo "停止" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2jqzbfnla.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2diwjtysz.html

esac
来源：http://dali.cucudq.cn/Article/details/gt2inhzznxb.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xezynnrp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xziqi.cn/Article/details/gt2jfchlatr.html

[R13] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2awcirbqv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gt2vrgcbiqy.html

[R14] C 风格 for
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxmiortp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gt2vunldums.html

[R15] while 逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2sadsvkxr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gt2imkgucit.html

[R16] until 等待条件
来源：http://dali.zycfv.cn/Article/details/gt2xjfkckyd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gt2vwdjglxn.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gt2kmqfluch.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2wwetrhtz.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gt2kwxtxchj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gt2cfxhndzk.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2gamhfypx.html

echo "${#arr[@]}"
来源：http://dali.sufxvd.cn/Article/details/gt2llsqthne.html

[R20] 关联数组（字典）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmbilfwe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gt2qouczjqj.html

[R21] 字符串长度
来源：http://dali.shuidangran.top/Article/details/gt2axqlmwwp.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eshjontl.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vackmuoi.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2kawiuvas.html

[R23] 字符串替换
来源：http://dali.ivvv.top/Article/details/gt2nrbdxfub.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gt2uzgdtkhn.html

[R24] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqyaohye.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnzdtlvb.html

[R25] 去后缀 / 去前缀
来源：http://dali.tian-w.cn/Article/details/gt2bobexljc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gt2rrzzpmcm.html

[R26] 命令替换
来源：http://dali.ivvv.top/Article/details/gt2dsekvsax.html

now=$(date +%F); echo "$now"
来源：http://dali.yvedp.cn/Article/details/gt2aazfgwlh.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gt2rwrqeenr.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gt2gkcsmpnk.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gt2dgtlsvuy.html

echo "scale=2; 10/3" | bc
来源：http://dali.hammf.cn/Article/details/gt2buhdcsis.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tttmhdwk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gt2fgvltabb.html

[R30] 函数返回状态码
来源：http://dali.redwolf501.top/Article/details/gt2emgaebbl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258.top/Article/details/gt2vreteeby.html

[R31] 局部变量
来源：http://dali.guowangkeji.top/Article/details/gt2aqkwiqok.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgfzy.top/Article/details/gt2rvbufsqt.html

[R32] 参数个数校验
来源：http://dali.zhoulong.xyz/Article/details/gt2kjeebrdf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ursewzff.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcgdwndo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gt2gncnnnly.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtfkiaej.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gt2mamivrsn.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gt2nqlddcos.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cqqwz.cn/Article/details/gt2dgfdferc.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gt2mipqhigm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gt2coekevfq.html

[R37] 把输出赋给变量
来源：http://dali.hnxiangtu.top/Article/details/gt2qhjmvman.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gt2wsclbfsw.html

[R38] 管道串联
来源：http://dali.ehwqpu.com/Article/details/gt2nfqskftc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shzxlz.cn/Article/details/gt2ecmrewpt.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gt2vtwxzyfn.html

cmd > out.log 2>&1
来源：http://dali.sxryk.cn/Article/details/gt2ubfzzzsc.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gt2nmpuuvid.html

echo "log" >> out.log
来源：http://dali.gaohongyu789.top/Article/details/gt2dxjhznby.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gt2oaulythw.html

cmd >/dev/null 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebvrboyv.html

[R42] 输入重定向
来源：http://dali.yj20258888.top/Article/details/gt2amhnqeoz.html

wc -l < a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2bzeivpka.html

[R43] 按名字查找文件
来源：http://dali.316326.xyz/Article/details/gt2ugnqvdao.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gt2kgqhnmmj.html

[R44] 按修改时间查找
来源：http://dali.chenlongwang.top/Article/details/gt2ajobsjzo.html

find . -mtime -7 -type f
来源：http://dali.svipenyu.cn/Article/details/gt2ncvcomvy.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gt2lgfdscfh.html

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gt2cajnnxwl.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gt2vozctpmt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yvchxhrr.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gt2lobsrieu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2eqrqktwl.html

[R48] awk 取指定列
来源：http://dali.hfpthk.cn/Article/details/gt2wfxitkgc.html

awk '{print $1, $3}' a.txt
来源：http://dali.cucudq.cn/Article/details/gt2eyyblllw.html

[R49] awk 带条件
来源：http://dali.cdnleiting.top/Article/details/gt2mmswfpng.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.quarkkingdee.top/Article/details/gt2mjmeoekr.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gt2xxuizwgz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yongpay.top/Article/details/gt2gctynvwd.html

[R51] 排序去重取前几
来源：http://dali.jinqigfzy.top/Article/details/gt2gmaqthoa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gt2wcxievop.html

[R52] 统计行数
来源：http://dali.chenlongwang.top/Article/details/gt2kkavblec.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gt2yyrkdmrv.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxinkj.top/Article/details/gt2mdoceqpl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cdnleiting.top/Article/details/gt2ewofwzzw.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gt2pugrhpdk.html

diff a.txt b.txt
来源：http://dali.yuxming.cn/Article/details/gt2qjyjvolq.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gt2qmgthmin.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guannengcc.top/Article/details/gt2lnnldpnk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rwutdkaf.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gt2lzpzzmec.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gt2npckhzuc.html

ssh user@host 'uptime'
来源：http://dali.chenjidiqi.icu/Article/details/gt2xootehpk.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gt2czevlapc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258.top/Article/details/gt2mkewygjt.html

[R59] 发 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gt2cpmlsnsl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gt2qdffwonu.html

[R60] 只看 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gt2yzmqhdsb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gt2oarxliug.html

[R61] 磁盘占用
来源：http://dali.sweek.top/Article/details/gt2xbzxivhw.html

df -h;  du -sh *
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhyajnbm.html

[R62] 找最占空间的文件
来源：http://dali.pycfn.com/Article/details/gt2wcpooszk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gt2atalcxjx.html

[R63] 内存与进程
来源：http://dali.mhx1999.top/Article/details/gt2hjdefuos.html

free -h;  ps aux | grep nginx
来源：http://dali.pengpengdd.cyou/Article/details/gt2scywclta.html

[R64] 结束进程
来源：http://dali.yuanzhike.top/Article/details/gt2uewbmlyl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gt2kztehfbn.html

[R65] 查看端口占用
来源：http://dali.chenzaomai.com/Article/details/gt2opsiakii.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gt2seieiism.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gt2xlhwfnbv.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gt2afrrzhhp.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aowacmmy.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gt2gydivuog.html

[R68] 计算文件校验值
来源：http://dali.yj202588.top/Article/details/gt2ahffyoiy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hammf.cn/Article/details/gt2pekczuln.html

[R69] 生成随机密码
来源：http://dali.zhengqikj.top/Article/details/gt2qmbnbxpj.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gt2txlzlojq.html

[R70] 时间戳与互转
来源：http://dali.c1oappe.top/Article/details/gt2dxqlxivk.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gt2ltthbdik.html

[R71] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gt2oqxyvmen.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qvvtkxqz.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gt2fkrihabc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gt2scnsohmw.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gt2mnlfxeam.html

split -l 1000 big.log part_
来源：http://dali.nanxuanxn.top/Article/details/gt2zkukazjg.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gt2zexsoqsf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gt2zfocnhtr.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gt2uzblpxsc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gt2mwmvtfdp.html

[R76] 使用临时文件
来源：http://dali.pycfn.com/Article/details/gt2mixgdgau.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gt2tishbvqt.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gt2oawibqco.html

read -rp "请输入: " ans
来源：http://dali.quarkkingdee.top/Article/details/gt2hmqsiozp.html

[R78] 交互式菜单
来源：http://dali.shzxlz.cn/Article/details/gt2ieikvuvy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gt2fbknmwrw.html

[R79] 解析命令行选项
来源：http://dali.yj20258888.top/Article/details/gt2wejmnobh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jyoumei.cn/Article/details/gt2nzcxufbb.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gt2elqfdntn.html

time ./run.sh
来源：http://dali.ehwqpu.com/Article/details/gt2ukafrojd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2karucwgj.html

S. C / C++ 专题
来源：http://dali.shuidangran.top/Article/details/gt2mffsqcip.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2pflfluro.html

[S01] C：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2dnmsfqgz.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxbnvbpk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gt2hxmrlsrx.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gt2azdpvhko.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smqqatgj.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gt2hupqzwzn.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gt2absnlnwg.html

[S04] C：字符串复制
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdiyyymd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxefvtxc.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iogldhil.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gt2jfxruuvc.html

[S06] C：字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gt2wfccqvua.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gt2byfisihu.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gt2izzybodc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gt2dlpwmtmw.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gt2qznbxjks.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gt2myracjsd.html

[S09] C：结构体定义与初始化
来源：http://dali.cdnleiting.top/Article/details/gt2bafgfmsi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gt2sjrxcloq.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gt2nbsjnbbu.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gt2wrwrswtm.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2knrugylh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gt2auqpyxgw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gt2qunzycgo.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gt2jxotedlx.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2jjxhpkoa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gt2oanksppg.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gt2pimdldzo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gt2fidmivma.html

[S14] C：枚举
来源：http://dali.sxryk.cn/Article/details/gt2jczevenx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gt2evzbbbwu.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gt2fcelufuy.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gt2ppvcogoz.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gt2vfxcdsyd.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gt2uosbqmmt.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gt2udfdnwlo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwtgrfdd.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2xfhjjnry.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gt2fybzkxhm.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gt2rrorvutv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnklggaj.html

[S20] C：二分查找
来源：http://dali.sufxvd.cn/Article/details/gt2vlodxzex.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gt2hwvrbprx.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gt2sewighqr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gt2pwtagoby.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gt2bakpmxlg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gt2xlxnwlot.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gt2ilbavigq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gt2vbvhxnhi.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gt2eqntjtrs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gt2lvxzgpou.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gt2pokhjahi.html

memcpy(dst, src, n);
来源：http://dali.xylfe.cn/Article/details/gt2spgwrgjf.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gt2zbcoonvr.html

memset(a, 0, sizeof a);
来源：http://dali.vqdsnc.cn/Article/details/gt2ymwkwlur.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gt2stonkntr.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2tsrpzggj.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gt2mtbfgtbw.html

static int counter = 0;
来源：http://dali.chenzaomai.com/Article/details/gt2snnaiind.html

[S29] C：变参函数
来源：http://dali.svipenyu.cn/Article/details/gt2wqokqysy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cheryme.top/Article/details/gt2lzpxxfff.html

[S30] C：头文件保护
来源：http://dali.ydzc1.top/Article/details/gt2lpbqagjk.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gt2aeysksto.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gt2osxolcqh.html

#endif
来源：http://dali.cheryme.top/Article/details/gt2kdxyhocx.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2mzyfrrrh.html

#include <iostream>
来源：http://dali.haohaochexian.top/Article/details/gt2cetlxlfx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gt2wxdivyhy.html

[S32] C++：字符串
来源：http://dali.chenlongwang.top/Article/details/gt2eazcxueg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lrwkzrqs.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gt2cdwldkxm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangdashe.top/Article/details/gt2xivnghnq.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gt2nfnxtdpq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckqmciwd.html

[S35] C++：map
来源：http://dali.jqgufenzy.top/Article/details/gt2eseurjpb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2daenudzp.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gt2byfehswv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2amhvbtsq.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gt2jnmogsse.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.birdmap.top/Article/details/gt2yvmqhqco.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gt2tufeuoyk.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gt2kekjgqbg.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gt2ozeqfyuj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gaohongyu789.top/Article/details/gt2xqpqrrkg.html

[S40] C++：查找元素
来源：http://dali.sweek.top/Article/details/gt2rmfcdmdv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuanzx.com/Article/details/gt2qqprlpwx.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gt2jenpcvvg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gt2ztcpqlpt.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djlpndms.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenzaomai.com/Article/details/gt2hkrewpkc.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gt2ftjmmudr.html

auto p = std::make_unique<int>(5);
来源：http://dali.ybcxt.top/Article/details/gt2uojvdbng.html

[S44] C++：引用传参
来源：http://dali.zdqjudy.top/Article/details/gt2hvytfkds.html

void inc(int &x) { ++x; }
来源：http://dali.fengsongda.top/Article/details/gt2nlegehyz.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gt2ezwnswjk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nwbrower.top/Article/details/gt2xyvjtwuf.html

[S46] C++：函数模板
来源：http://dali.zhixingplan.top/Article/details/gt2mxqwhcjc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gt2xlcbpube.html

[S47] C++：结构化绑定遍历
来源：http://dali.jyoumei.cn/Article/details/gt2lpchzbod.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gt2xxlmoynn.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2cepvxrsf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2juekfxtc.html

while (std::getline(in, line)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2ukplzyus.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gt2lmdthuzz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gt2ropzexvq.html

[S50] C++：格式化数字
来源：http://dali.cashguo.top/Article/details/gt2caanqwri.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2uisdvmqs.html

[S51] C++：显式类型转换
来源：http://dali.quarkkingdee.top/Article/details/gt2zjnifqyt.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gt2huumtmcw.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gt2sjgkjtkk.html

int size() const noexcept { return n_; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmbkyznd.html

[S53] C++：移动语义
来源：http://dali.xziqi.cn/Article/details/gt2dunhfgwz.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gt2ehmjyyby.html

[S54] C++：异常处理
来源：http://dali.hywenlv.cn/Article/details/gt2ndbvzdoz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gt2vmxfefah.html

[S55] C++：结构化绑定
来源：http://dali.shangyingyoupin.top/Article/details/gt2phnrrdap.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gt2jgbmjzio.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gt2tdyzmybl.html


<!-- 参考信息 -->