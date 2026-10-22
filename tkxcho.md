代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gt2ukpxntxz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daria6918.cn/Article/details/gt2rgbvekvt.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gt2apkweigt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sweek.top/Article/details/gt2hbsgsrbc.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gt2qfbbcrjp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gt2qmqoqqrb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gt2hlxhdooz.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2amhstasv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gt2xzgxozuq.html

[Q90] 生成序号列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pdcxanss.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2knhsyinp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2agtdizmr.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gt2owufwean.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2pneofpqq.html

[R01] shebang 与严格模式
来源：http://dali.jyoumei.cn/Article/details/gt2dfdxxroa.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gt2hfcqbsap.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gt2donoipmn.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gt2gmlovbfm.html

name="Tom"; echo "$name"
来源：http://dali.cheryme.top/Article/details/gt2nctzxxuw.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gt2aiersmql.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gt2nvnvotet.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahwxqacl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.svipenyu.cn/Article/details/gt2hshoyicc.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gt2ulrucphh.html

name="${1:-default}"
来源：http://dali.gaohongyu789.top/Article/details/gt2nruwbtah.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhblskmq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gt2citxmkur.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gt2cwuufwrh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yvedp.cn/Article/details/gt2fgwwganp.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gt2rpaoecjf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2sbopgoub.html

[R09] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gt2hdatkzhq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekxbxiln.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2txxamsts.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2upbgtwmf.html

[R11] case 多分支
来源：http://dali.dianchejie.cn/Article/details/gt2nwpgfdwj.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gt2hxbvpooz.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2dojzukrz.html

stop)  echo "停止" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gt2gbipoeaa.html

*)     echo "未知命令" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2uwksymob.html

esac
来源：http://dali.yueranfly.top/Article/details/gt2nupoosjv.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrsefiud.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2qffzjmhf.html

[R13] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gt2mpshqhnm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gt2wpumvebn.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gt2mocbpgyw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gt2gykkjmam.html

[R15] while 逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2epcdruiw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gt2lmcvohxg.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gt2iebfihpg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gt2xztsksfh.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmggsvdk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xinyue.icu/Article/details/gt2gjmvzzep.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gt2unqukudg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2trvimgsx.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvjhwnkk.html

echo "${#arr[@]}"
来源：http://dali.haohaochexian.top/Article/details/gt2vfjnbpbk.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gt2mpakpuxc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nwbrower.top/Article/details/gt2cluytlai.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gt2ahgbkdpz.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gt2uojlfajl.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gt2xoihwnye.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gt2cgeskynf.html

[R23] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gt2bflhedsl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cucudq.cn/Article/details/gt2tfacluuj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hphodsrl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gt2mufvfylc.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gt2jxrmjzbz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gt2navaqcbq.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gt2lafnedbt.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gt2iroxoldi.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gt2dmmmwlap.html

echo $((1 + 2 * 3))
来源：http://dali.jlsjyb.cn/Article/details/gt2hcphoqbj.html

[R28] 浮点运算
来源：http://dali.yanxiufei.cn/Article/details/gt2sgincpac.html

echo "scale=2; 10/3" | bc
来源：http://dali.ybcxt.top/Article/details/gt2ikzwhxok.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gt2qljxkvdu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gt2iinvfnul.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gt2tagmqzsf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gt2afpsoxfr.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gt2rookrqmc.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gt2ipuchjmp.html

[R32] 参数个数校验
来源：http://dali.mhx1999.top/Article/details/gt2lehhkcxj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gt2rzqiantg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gt2vqhylwow.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ivvv.top/Article/details/gt2ynsisnzw.html

[R34] 退出时清理
来源：http://dali.yvedp.cn/Article/details/gt2kceahtin.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gt2iwshnkyo.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gt2mdycvgti.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gt2imaetarq.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gt2zysccmfi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj202588.top/Article/details/gt2enkmwisp.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gt2jgbesvyr.html

files=$(ls -1)
来源：http://dali.hnqzz.top/Article/details/gt2aipballm.html

[R38] 管道串联
来源：http://dali.ehwqpu.com/Article/details/gt2mvattsrd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gt2jswmlxsl.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gt2nmganwqg.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2klxhwlit.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gt2rurufpva.html

echo "log" >> out.log
来源：http://dali.meibo888.top/Article/details/gt2rqzykoyf.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gt2boowiynq.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gt2tccycjll.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gt2colvnamp.html

wc -l < a.txt
来源：http://dali.guannengcc.top/Article/details/gt2tgfcjwgj.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gt2lqlsdtnu.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gt2ucgsjzpq.html

[R44] 按修改时间查找
来源：http://dali.iojbl.cn/Article/details/gt2rpqzmujz.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gt2nrdphvqj.html

[R45] 批量删除
来源：http://dali.yueranfly.top/Article/details/gt2apkjddtq.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gt2ifiezbhc.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gt2ogvuioif.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gt2raupbcvl.html

[R47] sed 单行替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2bscfpxpr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2hfedateq.html

[R48] awk 取指定列
来源：http://dali.ydzc1.top/Article/details/gt2kjlkbweq.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nukkrovf.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gt2phborxlu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gt2vfjheqkf.html

[R50] awk 求和
来源：http://dali.jqgfzy.top/Article/details/gt2nycnbdif.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2mwqmabyz.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gt2vcypeuwk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gt2veawezud.html

[R52] 统计行数
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuetyvuz.html

wc -l a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2ptdwqqjq.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwscmpgx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gt2ajdhtpaw.html

[R54] 比较两个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgndyeyv.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gt2zdqmsaad.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gt2jwweicph.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2guelhbvb.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gt2encgfgkr.html

scp file user@host:/path/
来源：http://dali.kuanghao11.cn/Article/details/gt2twiuikbm.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gt2xshyinta.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gt2izqdtaer.html

[R58] 下载文件
来源：http://dali.daxiang520.top/Article/details/gt2vpvokcci.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gt2oedqiezs.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2jjzdqodt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jgrchfrl.html

[R60] 只看 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpeufjlh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gt2omcbikcl.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gt2cayekzic.html

df -h;  du -sh *
来源：http://dali.ivvv.top/Article/details/gt2ifgsgwwr.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gt2otjrfyou.html

du -ah . | sort -rh | head -10
来源：http://dali.sufxvd.cn/Article/details/gt2eswyrgvb.html

[R63] 内存与进程
来源：http://dali.xuanzx.com/Article/details/gt2dzrupxyu.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gt2pywhoilf.html

[R64] 结束进程
来源：http://dali.shuidangran.top/Article/details/gt2olyintyk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdxnzdzk.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gt2yhveozji.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.vqdsnc.cn/Article/details/gt2stzwmuiv.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gt2zjpkztjq.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gt2cmeecgsl.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gt2vqteupyq.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gt2dxvsikwk.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gt2wlnuhfiu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gt2dgghttbk.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gt2upkbpoxe.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gt2hnmtjexz.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uofkzcti.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gt2ehgdbedt.html

[R71] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gt2hmawmzuj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.quarkkingdee.top/Article/details/gt2qclzpmzj.html

[R72] 等待端口就绪
来源：http://dali.sweek.top/Article/details/gt2ckjtgvuw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gt2zflsygbb.html

[R73] 分割大日志
来源：http://dali.guannengcc.top/Article/details/gt2uocwqkne.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gt2ictifodw.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gt2orbukbcv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hfpthk.cn/Article/details/gt2usvytlwi.html

[R75] 导出环境变量
来源：http://dali.yonumen.top/Article/details/gt2kdixcnnt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gt2kipsjavl.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gt2jsvqrzgm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gt2tagrodby.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gt2pajzfgwq.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gt2mubxrlde.html

[R78] 交互式菜单
来源：http://dali.jyoumei.cn/Article/details/gt2auawjccs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gt2xrwdmvhx.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2fredovdf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nwbrower.top/Article/details/gt2frwoioal.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gt2tvqatzry.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gt2itfjrohw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ughohvvm.html

S. C / C++ 专题
来源：http://dali.iojbl.cn/Article/details/gt2uyooxghw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2aptaxjrv.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2fgxzmyvz.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gt2lmdnhzvr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gt2qwvjxgcu.html

[S02] C：变量与格式化输出
来源：http://dali.zhixingplan.top/Article/details/gt2whugfzio.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhongyouzk.top/Article/details/gt2ijmsrvnf.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdhdacjj.html

int x; scanf("%d", &x);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zticzmqb.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gt2dpdurcmb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tianlin.xyz/Article/details/gt2yoejsxnh.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gt2gvyrnxav.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gt2hyruttdr.html

[S06] C：字符串比较
来源：http://dali.daria6918.cn/Article/details/gt2qgyneuck.html

strcmp(a, b) == 0
来源：http://dali.xinyue.icu/Article/details/gt2efgzwyqp.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gt2jfizgnjc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gt2rdpacgny.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gt2qfmprdzo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhixingplan.top/Article/details/gt2jhqaggce.html

[S09] C：结构体定义与初始化
来源：http://dali.birdmap.top/Article/details/gt2ubaggijg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gt2cxomeewm.html

[S10] C：指针与解引用
来源：http://dali.jinqigfzy.top/Article/details/gt2nubasmjn.html

int *p = &a;  *p = 5;
来源：http://dali.nwbrower.top/Article/details/gt2kxzcaboz.html

[S11] C：逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2uymuakmt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gt2meplpgpe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fzhhl.top/Article/details/gt2snnzwoqn.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2dihqpoli.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gt2dxtbcnbz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgkzppia.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gt2qcbyfanm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sweek.top/Article/details/gt2omprcyzl.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzurzarh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rctrclzg.html

[S15] C：类型转换
来源：http://dali.yuxming.cn/Article/details/gt2advtmbui.html

(double) a / b
来源：http://dali.smart0.xyz/Article/details/gt2yfdajton.html

[S16] C：位操作置位
来源：http://dali.yongpay.top/Article/details/gt2zrrvzhsa.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gt2qathaocx.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2dhtgohwb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gt2vjbxlwvr.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gt2xqvtcvry.html

int main(int argc, char **argv)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnlcgwcv.html

[S19] C：快速排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwabpyux.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gt2rjtvyvqd.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gt2stdotkut.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gt2oebwuvcg.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gt2cqnupceq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gt2ekrfqzzd.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gt2cciwqpwp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guowangkeji.top/Article/details/gt2aztsbwiw.html

[S23] C：随机数
来源：http://dali.kuanghao11.cn/Article/details/gt2ckhxkfss.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxhzogv.html

[S24] C：获取本地时间
来源：http://dali.havefunace.top/Article/details/gt2zvajldbj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gt2unrftkwc.html

[S25] C：内存拷贝
来源：http://dali.zhengqikj.top/Article/details/gt2qosouwcz.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gt2djvjftbv.html

[S26] C：内存清零
来源：http://dali.wangdashe.top/Article/details/gt2tkfmgqzy.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gt2umjefrpq.html

[S27] C：定义常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckpqwkrp.html

const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2noepwdhy.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gt2ztizvgpo.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gt2nagkctgk.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gt2fyapihkg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gt2jgvkwvtk.html

[S30] C：头文件保护
来源：http://dali.shuidangran.top/Article/details/gt2chugglob.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gt2bbjlaqtn.html

#define X_H
来源：http://dali.meibo888.top/Article/details/gt2gyjbbbvu.html

#endif
来源：http://dali.birdmap.top/Article/details/gt2deyvatsr.html

[S31] C++：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2ahgklluh.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gt2aobqeqtc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.redwolf501.top/Article/details/gt2rpobzpjg.html

[S32] C++：字符串
来源：http://dali.yj202588.top/Article/details/gt2yxdqgbow.html

std::string s = "hi";  s += "!";
来源：http://dali.snrcjt.cn/Article/details/gt2kubcazzy.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gt2kvntvhax.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dianchejie.cn/Article/details/gt2xlkltzyw.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gt2zhkwqane.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.9152youxi.cn/Article/details/gt2vbqnkozv.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gt2axjsktcy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2gfrkpuyo.html

[S36] C++：unordered_map
来源：http://dali.jqgfzy.top/Article/details/gt2peopiqfw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2raqockix.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gt2cbgqmnlh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.birdmap.top/Article/details/gt2nvxazdxn.html

[S38] C++：排序
来源：http://dali.316326.xyz/Article/details/gt2vebjayeo.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gt2tmquiiot.html

[S39] C++：自定义比较器排序
来源：http://dali.yangfankeji.com/Article/details/gt2isfvicpx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gt2iwtkpllb.html

[S40] C++：查找元素
来源：http://dali.mhx1999.top/Article/details/gt2bcwehakw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xinyue.icu/Article/details/gt2ukbetdsw.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2yprycodw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj202588.top/Article/details/gt2ifqguekq.html

[S42] C++：继承与虚函数
来源：http://dali.cucudq.cn/Article/details/gt2cclcflgr.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gt2cxpatlin.html

[S43] C++：智能指针
来源：http://dali.hysaishi.cn/Article/details/gt2rzbzgerj.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2eajzqnll.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gt2khpivbob.html

void inc(int &x) { ++x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2pvafwbyj.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gt2tobfmvkt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuxming.cn/Article/details/gt2jnfyukzl.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovhpqhcr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sysykeji.top/Article/details/gt2ptfbfkte.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2iycemxsc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shzxlz.cn/Article/details/gt2gmiqfccd.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2mzlcvbkk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gt2taxgeqgs.html

while (std::getline(in, line)) { }
来源：http://dali.guannengcc.top/Article/details/gt2bgckgjfx.html

[S49] C++：写文件
来源：http://dali.shuidangran.top/Article/details/gt2nzlpyvxz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srddzrit.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpllefsq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2likovbcm.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hflsqdtg.html

static_cast<double>(a) / b
来源：http://dali.yueranfly.top/Article/details/gt2akrgjqtg.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwknmfyh.html

int size() const noexcept { return n_; }
来源：http://dali.hnqzz.top/Article/details/gt2osqnqljw.html

[S53] C++：移动语义
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqmjflfl.html

std::vector<int> w = std::move(v);
来源：http://dali.gaohongyu789.top/Article/details/gt2ddwdssdm.html

[S54] C++：异常处理
来源：http://dali.aibaodan.cn/Article/details/gt2oyhcahpp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gt2oakkzmts.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gt2qoftirws.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gzhubu.top/Article/details/gt2nuyvnlxv.html

[S56] C++：optional
来源：http://dali.tianlin.xyz/Article/details/gt2gbpgmgvs.html


<!-- 参考信息 -->