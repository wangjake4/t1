代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2scsvlxqh.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gt2moimcstr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gt2qddslmld.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcdblpou.html

R. Bash 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ruzqutdf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2kpphdeht.html

[R01] shebang 与严格模式
来源：http://dali.smart0.xyz/Article/details/gt2kwjaswik.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gt2ehppuayb.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gt2mzqrimez.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gt2vlbgmdiw.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmxrbuee.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gt2mmmzdgnd.html

readonly PI=3.14
来源：http://dali.yonumen.top/Article/details/gt2poaozdzs.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gt2xqhveplm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gt2hiejfkin.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gt2cnlqnlqk.html

name="${1:-default}"
来源：http://dali.fengsongda.top/Article/details/gt2lxdgkbly.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2fblnmeac.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gt2pgneisak.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gt2lyrbocih.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.iojbl.cn/Article/details/gt2ujtierok.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gt2zrkgkqsg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuanzx.com/Article/details/gt2sgwycutx.html

[R09] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gt2mglikzbg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2fyzdglgp.html

[R10] 正则匹配
来源：http://dali.hywenlv.cn/Article/details/gt2xlxfzjfp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gt2fysewaqw.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gt2cbldrsaa.html

case "$1" in
来源：http://dali.fengsongda.top/Article/details/gt2uajwrcvb.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gt2xpncdybw.html

stop)  echo "停止" ;;
来源：http://dali.xziqi.cn/Article/details/gt2cihsbxlr.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gt2grszvauz.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcrunjvf.html

[R12] for 遍历文件
来源：http://dali.nanxinkj.top/Article/details/gt2pznfquav.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigufen.top/Article/details/gt2nvydkbmw.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gt2ljnaymnn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gt2psehhzoy.html

[R14] C 风格 for
来源：http://dali.kuanghao11.cn/Article/details/gt2dcpzrfcl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gt2vrmumhzh.html

[R15] while 逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2rkvhdzpx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ppjwa.cn/Article/details/gt2ugkpyoik.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gt2sfujqaur.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gt2xnonnaro.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gt2uyrsxmrz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gt2deyfpkox.html

[R18] 遍历数组
来源：http://dali.hammf.cn/Article/details/gt2mmsrpdwp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zycfv.cn/Article/details/gt2vnanxgkz.html

[R19] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhufpayi.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gt2exljjkgh.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gt2sfyhiqjq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gt2boupkivg.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gt2opsoecxs.html

echo "${#s}"
来源：http://dali.yj202588.top/Article/details/gt2mlghgvlq.html

[R22] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gt2ixmpehij.html

echo "${s:0:5}"
来源：http://dali.daria6918.cn/Article/details/gt2daqqjqsv.html

[R23] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gt2zcshpnbf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gt2sfldyvfm.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2gbatwjtz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2fcuxsnjg.html

[R25] 去后缀 / 去前缀
来源：http://dali.fzhhl.top/Article/details/gt2tcvcamkn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gt2zzscxezv.html

[R26] 命令替换
来源：http://dali.gzhubu.top/Article/details/gt2uniqmbym.html

now=$(date +%F); echo "$now"
来源：http://dali.xuetiantiany.cn/Article/details/gt2wkpsepqy.html

[R27] 算术展开
来源：http://dali.mhx1999.top/Article/details/gt2bgiimnfu.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gt2slwvuvdf.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gt2mkqgozwg.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gt2nhjqiivx.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gt2ngddndqv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gt2vssncbmm.html

[R30] 函数返回状态码
来源：http://dali.ppjwa.cn/Article/details/gt2vukllzgu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangdashe.top/Article/details/gt2exxqbnoc.html

[R31] 局部变量
来源：http://dali.ybcxt.top/Article/details/gt2xosqvmjq.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2yarqkacw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jpprenoz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gt2gvrdvjfj.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gt2nywnhhoc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gt2fiwtglyc.html

[R34] 退出时清理
来源：http://dali.hywenlv.cn/Article/details/gt2cdqavrtm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gt2azaxtldr.html

[R35] 后台执行并等待
来源：http://dali.xuetiantiany.cn/Article/details/gt2ycayisda.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cashguo.top/Article/details/gt2wnbwegpw.html

[R36] 并发执行多个任务
来源：http://dali.havefunace.top/Article/details/gt2tcmxnoly.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gt2dkeoptzm.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxxnosmp.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gt2gwiutqik.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gt2qzthxmfg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gaohongyu789.top/Article/details/gt2utnnwygz.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxuanxn.top/Article/details/gt2csayuskm.html

cmd > out.log 2>&1
来源：http://dali.haohaochexian.top/Article/details/gt2jclkfgys.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gt2grjfnoxb.html

echo "log" >> out.log
来源：http://dali.yonumen.top/Article/details/gt2koxqfssl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrokayi.html

cmd >/dev/null 2>&1
来源：http://dali.hywenlv.cn/Article/details/gt2dadzzrro.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gt2dvutlykg.html

wc -l < a.txt
来源：http://dali.xziqi.cn/Article/details/gt2dibjlhnh.html

[R43] 按名字查找文件
来源：http://dali.yueranfly.top/Article/details/gt2dofblzvv.html

find . -name "*.log" -type f
来源：http://dali.yj202588.top/Article/details/gt2ssitqjgq.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtbiabwa.html

find . -mtime -7 -type f
来源：http://dali.mhx1999.top/Article/details/gt2jsfakjnt.html

[R45] 批量删除
来源：http://dali.meibo888.top/Article/details/gt2sxbpnupy.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebiilkts.html

[R46] 递归替换文件内容
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwqzjbpb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gt2cvrndpgc.html

[R47] sed 单行替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecszsalx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2lumskeiv.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xxjaxkgs.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gt2gphijayo.html

[R49] awk 带条件
来源：http://dali.tanke756.top/Article/details/gt2whpcklcv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dhylwcmh.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gt2isgzmhkm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2zpstpfli.html

[R51] 排序去重取前几
来源：http://dali.zhoulong.xyz/Article/details/gt2xnnbprbi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zycfv.cn/Article/details/gt2wvhrdrbn.html

[R52] 统计行数
来源：http://dali.cashguo.top/Article/details/gt2brdftowd.html

wc -l a.txt
来源：http://dali.xinyue.icu/Article/details/gt2cxsbonel.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gt2kitdfncr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yueranfly.top/Article/details/gt2xdkvzozt.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gt2iowbbdtd.html

diff a.txt b.txt
来源：http://dali.sysykeji.top/Article/details/gt2fuqnfvoj.html

[R55] 压缩与解压
来源：http://dali.shangyingyoupin.top/Article/details/gt2lozwnrpq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gt2twsedlqb.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gt2gdbtnmif.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gt2zifyqlfx.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gt2viyjwhfv.html

ssh user@host 'uptime'
来源：http://dali.iojbl.cn/Article/details/gt2yotutinp.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gt2xetzmbsz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cqqwz.cn/Article/details/gt2kjadedhb.html

[R59] 发 POST JSON
来源：http://dali.cashguo.top/Article/details/gt2mqdjkgrl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258888.top/Article/details/gt2aigykqzb.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2jhxgacia.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gt2ydqqfmck.html

[R61] 磁盘占用
来源：http://dali.kuanghao11.cn/Article/details/gt2nvulamwu.html

df -h;  du -sh *
来源：http://dali.zhoulong.xyz/Article/details/gt2hgnyamaq.html

[R62] 找最占空间的文件
来源：http://dali.fzhhl.top/Article/details/gt2lkzhvgxo.html

du -ah . | sort -rh | head -10
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlnzhqsg.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gt2ftpakuhc.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gt2yjzfhjek.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gt2fnqmumoe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gt2iennbnls.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gt2yjawbbzw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fengsongda.top/Article/details/gt2llnrbnrj.html

[R66] 定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjubewhv.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2lskxjfaw.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gt2hranygzn.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gt2voiuzckv.html

[R68] 计算文件校验值
来源：http://dali.dashuyun.cn/Article/details/gt2wreezkwg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gzhubu.top/Article/details/gt2hycmfncx.html

[R69] 生成随机密码
来源：http://dali.gaohongyu789.top/Article/details/gt2qvaursnp.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gt2xrjyggjh.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gt2eybcgzqm.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gt2cbmogvvy.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gt2afpiugdv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gt2kaoedmyd.html

[R72] 等待端口就绪
来源：http://dali.jlsjyb.cn/Article/details/gt2wkpubmts.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gt2kyjcnpkl.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gt2pncojjbc.html

split -l 1000 big.log part_
来源：http://dali.sysykeji.top/Article/details/gt2ifdhfuof.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxjuzabu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gt2hacvwxow.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gt2vzcfkggq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gt2moqoajfy.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gt2vzobfjwh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gt2jszceggx.html

[R77] 读取用户输入
来源：http://dali.ybcxt.top/Article/details/gt2unzywypw.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gt2fhaidbcw.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gt2pxqgaxbq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gt2mbeinrfv.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gt2chbkvpvc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gt2xnilpqpy.html

[R80] 查看脚本执行耗时
来源：http://dali.xziqi.cn/Article/details/gt2dhzhwonv.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gt2kdgvhmxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmscptvz.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gt2tppvuhsj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2vffqeksj.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2glwouaim.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ografcdh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gt2eetqapmr.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2kkamlhhd.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnxiangtu.top/Article/details/gt2rnkvtjxw.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gt2ryhllvsh.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gt2jytpakbe.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gt2epjeigfq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2thrxntnw.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gt2ywbmihth.html

strlen(s)
来源：http://dali.andypj.xyz/Article/details/gt2xdadtdhy.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gt2evhurgyg.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gt2tciydnsx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2swdgtvyk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gt2sdkuwawl.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gt2dvpyggym.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gt2ndjaptyp.html

[S09] C：结构体定义与初始化
来源：http://dali.shuidangran.top/Article/details/gt2cesibufz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daxiang520.top/Article/details/gt2bobdjkrx.html

[S10] C：指针与解引用
来源：http://dali.gaohongyu789.top/Article/details/gt2svsibmfp.html

int *p = &a;  *p = 5;
来源：http://dali.meibo888.top/Article/details/gt2czllcgfi.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2nkbwkozx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.birdmap.top/Article/details/gt2lrofdqjg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2yhtwkiiv.html

fclose(f);
来源：http://dali.bjfxy.top/Article/details/gt2vedmgtyw.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gt2sqtbfpkv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gt2iqjfzzfa.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gt2omcmafta.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2errpuxpp.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gt2itpkpzfd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gt2wyhnllkj.html

[S15] C：类型转换
来源：http://dali.zhixingplan.top/Article/details/gt2bsbogykt.html

(double) a / b
来源：http://dali.hysaishi.cn/Article/details/gt2wxlvhscz.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gt2wylknpmz.html

x |= (1 << 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qimoolgn.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gt2ixeqeqlp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtkrtciy.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gt2gyamvrxx.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gt2ppcrensa.html

[S19] C：快速排序
来源：http://dali.sxryk.cn/Article/details/gt2fylxhkfk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gt2qzageern.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gt2flhctnuj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gt2gryfqlln.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gt2qbtsafdw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zdqjudy.top/Article/details/gt2vxhvarsu.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gt2ooitdpny.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gt2unhwzpzr.html

[S23] C：随机数
来源：http://dali.ydzc1.top/Article/details/gt2qosjhtbz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gt2eltghfoo.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vwxznfvw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gt2dqhpvzms.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gt2egibvsmv.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gt2pwugiciw.html

[S26] C：内存清零
来源：http://dali.hysaishi.cn/Article/details/gt2gyjdsrli.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gt2zhtopbat.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gt2fyqhgfsl.html

const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2ixtamjqw.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gt2diosqxxz.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gt2nbrtzvah.html

[S29] C：变参函数
来源：http://dali.zdqjudy.top/Article/details/gt2zhjuzjfa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gogol.net.cn/Article/details/gt2zxnrnzjz.html

[S30] C：头文件保护
来源：http://dali.jyoumei.cn/Article/details/gt2kaxgawyp.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gt2jgcrbrpj.html

#define X_H
来源：http://dali.shzxlz.cn/Article/details/gt2xgjwkfgh.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gt2mamyubrh.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2frkfdzrd.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gt2pcfnltpq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2prggcdfp.html

[S32] C++：字符串
来源：http://dali.cucudq.cn/Article/details/gt2huzyayda.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gt2wopmycno.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gt2lqzfizel.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxinkj.top/Article/details/gt2pzovscac.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovpimetl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgfzy.top/Article/details/gt2xvluuosb.html

[S35] C++：map
来源：http://dali.sysykeji.top/Article/details/gt2okmnyjkj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gt2igiglahi.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gt2jhzkdxuu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2sihdqxot.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gt2qngkblls.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gt2plusbjls.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gt2kjsohviz.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gt2xwmclyjs.html

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gt2wgkfsgzj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.0kj1m.cn/Article/details/gt2docdrayy.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gt2rgsncdab.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.svipenyu.cn/Article/details/gt2mspszuas.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gt2yawwoqki.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gt2ndmwznuo.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gt2lurhmztz.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gt2zqjlquco.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gt2vnkldsol.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxpedfxf.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gt2ziilyucl.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gt2bkpvvtnw.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gt2vowcvosx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gt2oghbkitb.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gt2pqdpvpnx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gt2ihemqhnb.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gt2izzrjbyg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxvqzkmw.html

[S48] C++：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2haluisoe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gt2rewgnnby.html

while (std::getline(in, line)) { }
来源：http://dali.yuanzhike.top/Article/details/gt2tdbmcqpf.html

[S49] C++：写文件
来源：http://dali.haohaochexian.top/Article/details/gt2qjbudhfd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gt2wytqmymw.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gt2tksoepes.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2ucdhaswj.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gt2kxqbzusn.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gt2lleephof.html

[S52] C++：const 与 noexcept
来源：http://dali.yuanzhike.top/Article/details/gt2pppkbhnm.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gt2sjuutrtp.html

[S53] C++：移动语义
来源：http://dali.zhiwuduotai.top/Article/details/gt2pubvbyod.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gt2ulkxgiqq.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdtnlvbl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gt2ufsqtoek.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gt2clrhwlth.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gt2cugsaotu.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gt2awcnfqvx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xylfe.cn/Article/details/gt2vwduvrfc.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gt2gddcrdtg.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gt2xipbwtrw.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gt2olmdarop.html

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gt2qmmxufjx.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gt2klsaepob.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnqzz.top/Article/details/gt2zoxnvopo.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gt2qglultff.html


<!-- 参考信息 -->